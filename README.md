# Slack Unfurl App

Example implementation of [spatricius/slack-unfurl-bundle](https://github.com/spatricius/slack-unfurl-bundle)

# Usage

### Set env variables
```env
SLACK_APP_TOKEN=
SLACK_APP_ID=
SLACK_REQUEST_TOKEN=
SLACK_ACCESSORY_IMAGE_URL=
SLACK_ACCESSORY_ALT_TEXT=

GITLAB_TOKEN=
GITLAB_API_URL=
GITLAB_DOMAIN=
```

### Run 
``` 
docker-compose up 
```

or run messenger manually
``` 
php bin/console messenger:consume -vvv 
```

or deploy to Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

### Screenshots

![image](https://user-images.githubusercontent.com/25185499/174646949-d95706ae-dad2-433b-b138-7bc51da36d7e.png)

![image](https://user-images.githubusercontent.com/25185499/174647345-45783386-32eb-46b8-8418-a66e9b2b8af8.png)
