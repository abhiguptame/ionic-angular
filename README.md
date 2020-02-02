# ionic-angular

### Install Ionic Tooling
```$ npm install -g @ionic/cli native-run cordova-res```

### Create an App
> Create an Ionic Angular app that uses the “sidemenu” starter template and adds Capacitor for native functionality:

```$ ionic start my-app sidemenu --type=angular --capacitor```  

### Change into App Folder
```$ cd my-app ```

### Install PWA elements
> Capacitor plugins, including the Camera API, provide the web-based functionality and UI via the Ionic PWA Elements library.

```$ npm install @ionic/pwa-elements```

### Build Project
```$ ionic build```

### Run The App
```$ ionic serve```

### Create New Service
```$ ionic g service services/myAppService```

### Create Andriod Project
```$ ionic cap add android```

### Create iOS Project
```$ ionic cap add ios```

### Copy Changes
> Every time we perform a build (e.g. ionic build) that updates your web directory (default: www), we will need to copy those changes into our native projects:

```$ ionic cap copy```

### Sync Changes
> After making updates to the native portion of the code (such as adding a new plugin), use the sync command:

```$ ionic cap sync```

### Open the native Android project in Android Studio:
```$ ionic cap open android```

### Open the native iOS project in Xcode:
```$ ionic cap open ios```

### Live Reload Android App
```$ ionic cap run android -l --external```

### Live Reload iOS App
```$ ionic cap run ios -l --external```
