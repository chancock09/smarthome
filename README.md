# Smarthome Setup

## House of Roast Beef

1. Homebridge UI

Running on http://localhost:8581/

Install:
- [Setup Homebridge UI](https://github.com/ebaauw/homebridge-hue#installation)
- Add Hue Plugin
  - Install through Plugins UI
  - Add IP Address for Hue Bridge
  - Check settings to expose lights
 
- Debugging
  - [Can't hide bridge from favorites](https://github.com/ebaauw/homebridge-hue/issues/767#issuecomment-695763159)

2. Airconnect

- [Install Airconnect](https://github.com/philippe44/AirConnect)
- Download from [here](https://github.com/philippe44/AirConnect/blob/master/bin/airupnp-osx-multi)
- I ran this:

```
10188  mv ~/Downloads/airupnp-osx-multi .
10189  chmod a+x airupnp-osx-multi
10190  ./airupnp-osx-multi
```

3. Other

Keep computer alive with:

```
sudo pmset -a disablesleep 1
```