# docker-laravel-handson
version: "3.9"
services:
  app:
    build: ./infra/php
    volumes:
      - ./src:/data
