# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

# 프로젝트 생성
# docker image pull
docker pull ruby:3.3.1

# docker ruby run 
docker run -v /Users/work6189/Documents/project:/share -p 3000:3000 -it ruby:3.3.1 /bin/bash

# gem install rails && install rails project File(database postgresql)
gem install rails 
rails new reservation --database=postgresql

docker build . 