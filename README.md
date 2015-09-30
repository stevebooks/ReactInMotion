# ReactInMotion
Demo app showing how to integrate React Native into RubyMotion. This is a simple proof of concept repository. It also contains an xCode version and an Android version of the same project so you can compare implementation differences.

## Install
1. Install RubyMotion
2. Install React Native: https://facebook.github.io/react-native/docs/getting-started.html
  * Install node: `brew install node`
  * Install watchman: `brew install watchman`
  * Optional: Install React Native CLI: `npm install -g react-native-cli`
3. Install bundler: `gem install bundler`
4. Install gems (motion-cocoapods): `bundle`
5. Initialize cocoapods: `pod setup`
6. Install cocoapods: `rake pod:install`

## Run
1. Run React Native server from the base directory (run this in a separate terminal tab): `npm start`
2. cd into motion_ios and build your app: `rake` or `rake device`

