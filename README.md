# docker-images

## ruby 2.4.7

```
docker build -t graysonchen/ruby:2.4.7-olympic -f ./ruby/2.4.7/Dockerfile-olympic .
docker push graysonchen/ruby:2.4.7-olympic
```

## ruby 2.2.3

https://hub.docker.com/r/graysonchen/circleci-ruby/


circleci-ruby:2.2.5-jessie

```
docker build -t graysonchen/circleci-ruby:2.2.5-jessie -f ./ruby/2.2.3/Dockerfile-circle .

docker push graysonchen/circleci-ruby:2.2.5-jessie
```

circleci-ruby:2.2.5-jessie-custom

```
docker build -t graysonchen/circleci-ruby:2.2.5-jessie-custom -f ./ruby/2.2.3/Dockerfile-circle-custom .

docker push graysonchen/circleci-ruby:2.2.5-jessie-custom

```


Ref:

  https://github.com/Daniel-ltw/ruby-node-alpine

  https://github.com/circleci/circleci-images

  https://github.com/docker-library/ruby
