FROM ubuntu:latest
ADD app.rb Gemfile Gemfile.lock /code/
ADD views/* /code/views/
WORKDIR /code
RUN bundle install
CMD ["bundle", "exec", "ruby", "app.rb"]
