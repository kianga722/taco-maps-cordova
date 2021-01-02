# taco-maps-cordova

Conversion of [taco-maps](https://github.com/kianga722/taco-maps-serverless) to Android/iOS app with Cordova

## Notes

- Conversion required tweaks to various React files, package.json (iOS has extra steps needed)
- Reminder that this is a different context (installed app vs web browser)
- Needed to install Cordova geolocation plugin to get location
- Need location turned on device beforehand (add prompts to handle these scenarios?)
- Location error messages different for Android/iOS compared to web, need to modify React code
- iOS has its own gotchas (API server needed to be modified to handle preflight requests but was responding fine on Android/web browsers)
