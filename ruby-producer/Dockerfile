FROM ruby
COPY . ./usr/src
WORKDIR /usr/src
RUN gem install bunny
CMD ["ruby", "producer.rb", "150"]
