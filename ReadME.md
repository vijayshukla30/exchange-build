## create a .env in root project and enter below line

```
APP_PORT=5002
ORGANIZATION_ENGINE_URL=http://localhost:8090/api/
UPLOAD_DIR_PATH=/home/gaurav/nexthoughts/var/nocode
APP_DOMAIN=webconnect.today
AWS_SECRET_ACCESS_KEY=KUREXTOpxZd42JjojDrHmG8BnuVVhChcn/ewPCWx
AWS_ACCESS_KEY_ID=AKIAX4BKOZ6FHUQHT4KH

AWS_SES_SECRET_ACCESS_KEY=AKIAX4BKOZ6FMGGFTZE6
AWS_SES_SECRET_SECRET_KEY=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
AWS_SES_REGION=ap-south-1
AWS_SES_ADMIN_EMAIL=webconnect@prodeless.com
AWS_SES_ADMIN_FROM_EMAIL_NAME=WebConnect <webconnect@prodeless.com>
LOG_FOLDER_PATH='/var/www/html/log'
```

where APP_PORT where this node application will run
and CORS_SERVER is the url of GrapesJS application

--removed verifyJwt ---server.js
