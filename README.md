# Install `now`

```
yarn global add now
```

or
```
npm i -g now
```

Make sure you have a `{ "payload": {` object at the top of data.json.

# Deploy
```
now kaydwithers/dummy-data
```

Once deployed, go to your new `now.sh` site and add `/payload` to the url. i.e
```
https://todos-lgxdzqpmzy.now.sh/payload
```