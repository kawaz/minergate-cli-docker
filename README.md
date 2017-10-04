```
# build
docker build . -t kawaz/minergate-cli

# push
docker push kawaz/minergate-cli

# run
docker run -d --log-driver json-file --log-opt max-size=5m --log-opt max-file=3 kawaz/minergate-cli
```
