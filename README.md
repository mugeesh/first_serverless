# first_serverless


## create project
```
mkdir serverless-nodejs-app && cd serverless-nodejs-app
sls create -t aws-nodejs -n serverless-nodejs-app
npm init -y
serverless config credentials --provider aws --key key  --secret secretKey --overwrite

serverless deploy -v

npm install --save express serverless-http
npm install serverless-offline --save-dev
serverless offline start
```
