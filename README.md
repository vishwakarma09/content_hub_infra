# content_hub_infra

Infra repo for Content hub project

some containers added for testing:

steps:

docker login

docker build -t vishwakarma09/mysql_client:latest -f dockerfiles/mysql_client.dockerfile .

docker build -t vishwakarma09/alpine_bare:latest -f dockerfiles/alpine_bare.dockerfile .

then push

docker push vishwakarma09/mysql_client:latest

docker push vishwakarma09/alpine_bare:latest
