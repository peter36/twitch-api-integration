# twitch-api-integration

Example to show Twitch-API-integration using pubsub.

A fork from: https://github.com/twitchdev/pubsub-javascript-sample

The Twitch API endpoint is updated to the latest one as of 2021-09-20

## How to use:
1. Update main.js's first few lines with your own Twitch userId and clientId.  ClientId can be obtained from Twitch from this URL: https://dev.twitch.tv/console/apps/create

2. Start `http-server` (you can install it by `npm install -g http-server`

3. Open browser to http://localhost:8080

## From the original repo's README
Here you find a simple JavaScript PubSub implementation with client-side authentication using the Implicit Grant Flow. The project structure section will give you a quick overview of this code.

## Structure
`index.html`
Provides the view of all incoming and outgoing pubsub messages.

`main.js`
Provides the actual functionality of the PubSub client.  If you are not authenticated, you will see the Connect to Twitch button and will be prompted through the authentication flow.  After authenticating, you will be able to send and receive raw PubSub messages.

## License

Copyright 2017 Amazon.com, Inc. or its affiliates. All Rights Reserved.

Licensed under the Apache License, Version 2.0 (the "License"). You may not use this file except in compliance with the License. A copy of the License is located at

    http://aws.amazon.com/apache2.0/

or in the "license" file accompanying this file. This file is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

