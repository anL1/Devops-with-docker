FROM ruby:2.6.0

COPY . /usr/src/myapp
WORKDIR /usr/src/myapp
RUN bundle install
RUN rails db:migrate
EXPOSE 3000
CMD ["rails", "s"]
