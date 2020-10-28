# Redux-store-sample-API

This API is built in case someone wants to test the [Redux-store-sample](https://github.com/YordanovDnA/Redux-store-sample), or someone who needs simple API which contains USERS and CUSTOMERS lists.

The API is deployed at Heroku and you can access:

**USERS:** [https://github.com/YordanovDnA/Redux-store-sample/api/users](https://github.com/YordanovDnA/Redux-store-sample/api/users)

**CUSTOMERS:** [https://github.com/YordanovDnA/Redux-store-sample/api/customers](https://github.com/YordanovDnA/Redux-store-sample/api/customers)

**AUTH:** [https://github.com/YordanovDnA/Redux-store-sample/api/auth](https://github.com/YordanovDnA/Redux-store-sample/api/auth)

You can use the **auth** path to send post http request for authorization of user. For example:

Using [Postman](https://www.postman.com/) send a post request to the **/auth** endpoint and it will return a [jwt](https://jwt.io/). Then you can use [jwt-decode](https://www.npmjs.com/package/jwt-decode) to decode the token. The token is encripted information about the user.

For more examples look at the [documentation](https://).

## Installation

If you'd like to modify feel free to clone this repository and change whatever you want.

Use the package manager [npm](https://docs.npmjs.com/about-npm) to install the dependences.

```bash
npm install
```

## Start the API

```bash
npm start
```

The API will run on localhost port 9002.

**Example accessing the users**: [http://localhost:9002/api/users](http://localhost:9002/api/users)

## Usage

You can use [axios](https://www.npmjs.com/package/axios) or any other http requests library to send http requests to the API's endpoints.

[Documentation](https://)

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
