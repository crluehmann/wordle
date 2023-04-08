# wordle

This is a simple configuration to quickly run wordle using docker.

Run commands are simple:

```docker
cd wordle
docker-compose up -d
```

Nginx assumes http://wordle so be sure to point a local DNS record to your docker host.

localhost should work too.
