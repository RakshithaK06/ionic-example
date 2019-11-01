# KintoHub Ionic WPA Example

## Overview
Ionic is an amazing mobile app framework making it easy to make native apps for any operating system. They support Web Progressive Apps which can easily be built and used on KintoHub!
The conference app example shows off the power of Ionic, thus we have forked it with *zero* modifications so you can see it in action with KintoHub.

[Live Example](https://ionic-example-96bf9-65a24.web.staging.kintohub.com/)

__About KintoHub:__

KintoHub aligns teams to ship & operate cloud native apps with ease. [Learn More](https://www.kintohub.com)

## Deployment
1. Apply this template to your [Github](/generate)
2. Create a [Website KintoBlock](https://staging.kintohub.com/app/dashboard) and include:

2a. Connect your GithubApp to KintoHub and select the Repository you just generated on your account.
2b. Set the *name* of your kinto block
2c. Choose *Static from build* as your type
2d. Choose `Node.js` as the *language* and `11.7.0` as the *version*
2e. Set the *Build Command* as `npm install && npm run build`
2f. Set the *Build Output Folder* as `/www`

You're now good to go! Click *Create Website*. Now click *Build Latest Commit*.

... The build takes about 5 minutes. Once complete, Click *Add to Project*

Follow the instruction to creating a new project. Once created, you can then click *Open* on your Ionic block and see it running live!

## Installation & Local Run
Ensure you have node 6 or higher.

1. `npm install -g ionic`
2. `npm install`
3. `ionic serve`

## Test

1. `npm run test`

## Usage
You can view a live example [here.](https://ionic-example-96bf9-65a24.web.staging.kintohub.com/):
