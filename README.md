# AWS IoT Core SigV4 
## Introduction 
- This repo contain basic example on how to create Signature V4 for **IoT Core**.
- Use this signature to connect to AWS IoT Core Mqtt Over Websocket.
- Feel free to explore the code at your own risk. :stuck_out_tongue_winking_eye:

## Tech
This repo uses open source projects to work properly:
- [node.js] - used for the backend
- [AWS CLI] - used for enviroment

## Installation
- Requires latest [Node.js][node.js] to run.
- Requires latest [AWS CLI][AWS CLI] to run.

Fill up `SECRET_KEY`,`ACCESS_KEY` and `END_POINT` in config.js

Install the dependencies and devDependencies.
```sh
cd AWS_IoT_Core_Signature_V4
npm install
```

Run test.js to execute lambda function in index.js
```sh
node test.js
```


## License
MIT

**Free Software, Syukran Alhamdulillah Thank to Allah!**
    
   [awssdk]: <https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/Rekognition.html>
   [node.js]: <http://nodejs.org>
   [SAM CLI]: <https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/serverless-sam-cli-install.html>
   [AWS CLI]: <https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html>
