FROM ruby

RUN gem install rails

WORKDIR /app

COPY app/Gemfile Gemfile
COPY app/Gemfile.lock Gemfile.lock

RUN bundle

CMD rails --version
