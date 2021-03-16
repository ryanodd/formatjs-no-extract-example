# Formatjs extract test

1. clone this repo
1. `yarn install`
1. `yarn extract`
1. check if any strings were populated in `src/lang/en.json`

On Mac OS, this results in one string extracted :
```
{
  "stringId": {
    "defaultMessage": "hellooooooo world!"
  }
}
```

On Windows, however, this results in an empty json:
```
{
}
``` 