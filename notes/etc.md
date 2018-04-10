
### Slides: `https://goo.gl/1HHBA9`
### Videos: `vimeo.com/nruggeri`

## SSH
```
    ssh -i ~/.ssh/<key>.pem ubuntu@<ip_address from clipboard>
```

```
    ssh -i ~/.ssh/hoot.pem ubuntu@ec2-34-211-147-251.us-west-2.compute.amazonaws.com
```

## RDS End point Connection
```
    hoot-restore.cbgl6t9fq6nt.us-west-2.rds.amazonaws.com
```

## Change Heroku ENV
```
heroku config:add DATABASE_URL=postgres://<username>:<password>@<end point>:5432/<app name>_production

heroku config:add DATABASE_URL=postgres://ChewbaccaJerky:jlugtu69@hoot-restore.cbgl6t9fq6nt.us-west-2.rds.amazonaws.com:5432/hoot_production

```

# Ops Works

## Rootkeys
```
    AWSAccessKeyId=AKIAJ6QNP435MI75FBZA
    AWSSecretKey=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
```

## Stack ID
```
    6f82676c-7cba-48cc-8231-b1901ef1656f
```

## App Id
```
    66fb1c19-325c-4cf1-9b40-8b3a5950d53a
```


