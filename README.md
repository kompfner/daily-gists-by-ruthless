# mattie ruth's gists for testing daily calls

99% of the time i use `basic-call-object.html` which just makes a simple call
object instance and puts it and some handy variables on the window for
manually joining a call or running various commands. I prefer using extremely
basic html + javascript gists like these for testing to remove all sorts of
variables while debugging.

## Setup

Setup your favorite rooms for testing:

```bash
$ cp _roomInfo.js.template _roomInfo.js
```

Then modify \_roomInfo.js to add/change room urls and tokens you like to use for
testing along with your API keys for some of the gists that will generate
tokens for you. This will keep all this sensitive info local and out of this
repo :)

## Running

1. Serve up this folder

```bash
$ ./run_server <port>
```

2. The above will open the folder in your browser. Simply find the gist you want
   to work with

## Changing your room or adding a token

Just change which room `window.ROOM_URL` points to or `window.JOIN_TOKEN` points
to in your `_roomInfo.js` file.
