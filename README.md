# Chatwoot on Dokku

Deploy Chatwoot easily to Dokku with Dockerfile deployment.

## Prerequisite

- Dokku app
- Postgres instance
- Redis instance
- Adjusted env variables taken from [the .env.example](https://github.com/chatwoot/chatwoot/blob/develop/.env.example)

## Usage

```sh
$ git clone https://github.com/mvr-studio/chatwoot_on_dokku.git
$ cd chatwoot_on_dokku
$ git remote add dokku dokku@[YOUR DOKKU INSTANCE ADDRESS]:[APP NAME]
$ git push dokku main
```
