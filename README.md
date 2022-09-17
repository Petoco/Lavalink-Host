# Instalation

- Install last version of [Lavalink](https://github.com/freyacodes/Lavalink/releases)
- Install the repository's files
- Put them in the same folder
- Run the .bat file

# Connect

For connect the lavalink host with your app you will need to set this:

```js
Lavalink: {
    id: "Main", //- Used for indentifier. You can set this to whatever you want.
    host: "localhost", //- The host name or IP of the lavalink server.
    port: 3000, // The port that lavalink is listening to. This must be a number!
    pass: "petoco", //- The password of the lavalink server.
    secure: false, // Set this to true if the lavalink uses SSL. if not set it to false.
    retryAmount: 9999999, //- The amount of times to retry connecting to the node if connection got dropped.
    retryDelay: 40, //- Delay between reconnect attempts if connection is lost.
}```
