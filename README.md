# Nativescript Vue Starter Theme

Currently I'm in development process of an app. As soon as I finish with it I'm going to upload the files.

## Install Nativescript CLI

Before starting development in this project, make sure you have environment ready explained in  [nativescript documentation](https://docs.nativescript.org/angular/start/quick-setup) .

## My current environment


 ##### node v10.16.0 
 ##### Yarn 1.16.0 [Install from here](https://yarnpkg.com/en/docs/install#mac-stable) .
 ##### nativescript 5.3.4
 ##### Xcode 10.0 - Build version 10A255
 ##### Vue-CLI 3.4.0
 


## Simple steps to make it work

```bash
 #Clone this repo 
 Cd to 'repo'
 yarn install

#Change APP ID in package.json 
"nativescript": {
    "id": {
        "ios": "{appID1}" ,
        "android": "{appID2}"
    }
 }

 #Build for Android
 tns run android --bundle

 #Build for iOS
 tns run ios --bundle (For iOS)

```

## Other commands 
```bash
# Link the app you’re developing locally to the NativeScript Playground app for your iOS or Android device
tns preview 

# Debugging your android application using Vue-Devtools
tns run android --debug --bundle

# Debugging your iOS application using Vue-Devtools
tns run ios --debug --bundle 

```

## Usage


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)