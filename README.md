# socketio-client-ue4

This is a fork of <https://github.com/getnamo/socketio-client-ue4> trying to update the plugin to work with the latest version of the C++ socket.io client from <https://github.com/socketio/socket.io-client-cpp>.

The original version would disconnect after 25 seconds from the socket.io server because of incorrect ping-pong heart beat messages.

## How to Install
### Via Git clone

1. Create a new project or choose project to add plugin.
2. Browse to your project folder (typically found at `Documents/Unreal Project/{Your Project Root}`)
3. Create a `Plugins` folder in your project root folder and use that path for step 4. command.
4. Git clone. Repository uses submodules, so recommended command is:

``` git
git clone https://github.com/MarcG-TUE/socketio-client-ue4 --recurse-submodules
```
