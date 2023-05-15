# REST_Server-template-node

---

## Description

Template to generate the generic structure of a backend in Node

## Installation

One package.json contain now all neccessary for Nest and Angular, so server-side rendering with Angular is possible

```bash
$ npm install
```

## Running the app

```bash
# development - start - port 4000
$ npm run start
```

For another commands look to package.json

## Set enviroment

- Rename .env.example to .env

- Change mongoDB environment variables

```bash
	.
	.
	.

	MONGODB_CNN=mongodb+srv://user_node_cafe:R5bsf6A7FcjE8Rr4@miclustercafe.y7m8dsa.mongodb.net/cafeDB

	USER=user_node_cafe
	PASS=R5bsf6A7FcjE8Rr4
	.
	.
	.
```

- Change encryption key for your JWT

```bash
	.
	.
	.

	SECRETORPRIVATEKEY=Est03sMyPub1cK3y
	.
	.
	.
```

- Google Sign-In (Google Identity)
  Simply open the link that I leave below, which has to follow the steps and create the API for authentication
  [Google Sign-In (Google Identity) - Official Page](https://developers.google.com/identity/gsi/web/guides/get-google-api-clientid?hl=es-419)

after creating the API, replace the corresponding credentials

```bash
	.
	.
	.

	GOOGLE_CLIENT_ID=pasteToGoogleClientID
	GOOGLE_SECRET_ID=pasteToGoogleSecretID
```
