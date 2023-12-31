# electron-game
Testing if electron is a good platform for html5 games. Who knows? Maybe it won't be great but let's find out what can be done.

## :warning: Nothing to see here as of now :warning:

Will remove this notice when there actually is a small game and some steamworks integration.

## TODOs

- [ ] :space_invader: Add some kind of game (probably 2D)
- [ ] :video_game: Implement and test gamepad compability
- [ ] :green_circle: Implement steamworks.js and check if steam overlay works
- [ ] :sparkle: Test three.js and/or babylon.js

## Test platforms
- :deer: Ubuntu 22.10 (yes, I should upgrade) with various game controllers
- :green_circle: Steam Deck with built in controller and touch screen
- :apple: macOS with various game controllers

## Resources

Some things I've found while researching this topic. 

- [Drew Conley Youtube](https://www.youtube.com/@DrewConley) - Game Dev Tutorials for Web Developers.

- [Game Dev Tycoon Credits](https://www.greenheartgames.com/credits/game-dev-tycoon/) - Famously using [node-webkit](https://github.com/nwjs/nw.js) for their game. I guess [CrossCode](http://www.cross-code.com/en/home) should be mentioned too.

- [steamworks.js](https://github.com/ceifa/steamworks.js)

## Random notes

### Gamepads

Xbox Series controller print out from usb-device-added 

```
usb-device-added FIRED WITH {
  deviceClass: 255,
  deviceId: 'f2dbc8e5-f737-4c4d-a389-240e57891d49',
  deviceProtocol: 208,
  deviceSubclass: 71,
  deviceVersionMajor: 5,
  deviceVersionMinor: 0,
  deviceVersionSubminor: 9,
  manufacturerName: 'Microsoft',
  productId: 2834,
  productName: 'Controller',
  serialNumber: '3039564C32303335303535303438',
  usbVersionMajor: 2,
  usbVersionMinor: 0,
  usbVersionSubminor: 0,
  vendorId: 1118
}
```