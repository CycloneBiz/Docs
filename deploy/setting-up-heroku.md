# Setting up Heroku

Using Heroku is not recommended, but is supported. You can still use OpenLoop as a feeder for other IoT devices or create a fork of OpenLoop with the plugins you want (remember to change `.gitignore`).

### Deploying

As of creating, Heroku has turned off direct Github syncing, so you will have to sync it using a cli or just have a local git server.

```shell
heroku login # Login to heroku
heroku git:remote -a myproject # Connect to git server
git push heroku master # Push contents to heroku server, OpenLoop should work out of the box
```

### Restarting Heroku

After updating [system variables](system-variables.md) you will need to restart OpenLoop.

```shell
heroku restart -a myproject
```

### Connecting Atlas

When connecting Atlas, it will ask you for Whitelistable IPs. Sadly, you will have to whitelist all IPs `0.0.0.0/0` because of how Heroku works.&#x20;
