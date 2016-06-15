# MLportal

This is a blog on the most important machine-learning algorithms.

## Steps to Get Started

### One

Download and install [Node.JS](https://nodejs.org/en/download/) and [MongoDB](https://www.mongodb.com/download-center) before continuing.

Also, we'll want to install Yeoman.

```
npm install -g yo
```

### Two

```
git clone https://github.com/kelsonic/MLportal.git

cd /MLportal

npm install

touch .env
```

Inside of the .env file:

```

COOKIE_SECRET=EnterYourSecretCookieKeyHere
CLOUDINARY_URL=EnterYourCloudinaryURLHere
MANDRILL_API_KEY=EnterYourMandrillAPIKeyHere

```

### Three

In one terminal run `mongod` to start your database.

### Four

In another terminal run `node keystone.js` to start your server.

### Five

Navigate to `http://localhost:3000/`. All done!

## Contributing

Do you see some errors? Want to create a new feature? **Simple!** 

Just fork the repo, make your changes, and send up a pull request.

## License

MIT License. View it in the LICENSE file.