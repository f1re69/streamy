# Streamy

RESTful webservice which allow users to make and read video stream.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

Once you created your stream, you can feed the stream by adding the custom server url into your streaming software : rtmp://localhost/live/id.

### Prerequisites

You need to create OAuth2 credential. Check the official documentation here : https://developers.google.com/adwords/api/docs/guides/authentication?hl=fr

One you get your OAuth2 credential, do the following instructions.
Make sur to replace "YOURCREDENTIAL" by your credential ID given by Google OAuth2.

```
cd client
echo REACT_APP_GAUTH_ID=YOURCREDENTIAL > .env
```

Once you create the .env file you can run the backend server, the rtmp server and the frontend with npm start.

## Built With

* [React.js] (https://reactjs.org) - The frontend library used
* [Redux] (https://redux.js.org) - State manager library
* [node-media-server] (https://www.npmjs.com/package/node-media-server) - RTMP server
* [JSON Server] (https://www.npmjs.com/package/json-server) - The backend REST server
* [Semantic UI] (https://semantic-ui.com) - CSS Framework

## Authors

* **Khelil Bezzouh** - *Initial work* - [kbezzouh](https://github.com/f1re69)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
