FROM dart:3.0

WORKDIR /app

ADD pubspec.yaml /app/

RUN dart pub get --no-precompile

ADD . /app/

RUN dart pub get --offline --no-precompile

WORKDIR /app

CMD {{command}}
