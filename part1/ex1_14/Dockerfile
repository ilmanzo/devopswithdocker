FROM ruby:2.6.0
# nodejs is required for execjs ruby gem
RUN apt-get update ; apt-get install -y git nodejs 
RUN git clone https://github.com/docker-hy/rails-example-project
WORKDIR /rails-example-project
RUN gem install bundler && gem install execjs && bundle install && rails db:migrate
ENTRYPOINT ["rails"]
CMD ["s"]
