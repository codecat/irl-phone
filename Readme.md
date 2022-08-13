# Nimble IRL Mobile App
![](/backpack.jpg)

Read more about this build: https://codecat.nl/2022/08/irl-backpack/

This is the mobile app for Nimble IRL.

## Building
Run `npx cap sync` to synchronize the `www` folder with the native platform folder. From there you can build the app in XCode.

Run `npx cap run ios` to synchronize, build, and deploy the iOS app to a phone or simulator.

## Local testing
For local testing, install [Caddy](https://caddyserver.com/), run `caddy file-server --root www --listen :8080`, and navigate to http://127.0.0.1:8080/.
