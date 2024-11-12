FROM google/dart:2.15

WORKDIR /app

COPY . /app

RUN dart compile exe calc.dart -o calc

CMD ["./calc"]