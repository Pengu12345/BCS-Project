# BCS Project

## Requirements

* Docker
* Node
* A phone emulator (via Android studio) / Expo Go application

## Setting up the server

Via the CMD, open the *bcs-server* folder, and type the following command:
```
docker compose up --build
```

The database and API will be automatically set up and ready to be used.

## Setting up the client

Via the CMD **and in parallel to the server**, open the *bcs-client* folder and type the following command:

```
npm install
```

* You may need to change the IP address to your machine IP in order for the client to work. The address is located in the `src/API.ts` file.

Once everything is set up, simply run the command:

```
npm run android
```

If you have the Android emulator ready (Through the Android Studio software), it should start automatically.

Else, use the Expo Go application to emulate it directly on your phone. (Make sure to be connected to the same network)
