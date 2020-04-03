# Streamy

RESTful webservice which allow users to manage and read video streams.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

You need to create OAuth2 credential. Check the official documentation here : https://developers.google.com/adwords/api/docs/guides/authentication?hl=fr

One you get your OAuth2 credential, do the following instructions.

```
cd client
echo "REACT_APP_GAUTH_ID=YOURCREDENTIAL" > .env
```

Once you create the .env file you can run the backend server and the frontend server with npm start.

## Built With

* [React.js] (https://reactjs.org) - The frontend library used
* [Redux] (https://redux.js.org/) - State manager library 
* [JSON Server] (https://www.npmjs.com/package/json-server) - The backend REST server
* [Semantic UI] (https://semantic-ui.com/) - CSS Framework

## Authors

* **Khelil Bezzouh** - *Initial work* - [kbezzouh](https://github.com/f1re69)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
