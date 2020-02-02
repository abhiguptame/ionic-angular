# ionic-angular

# Install Ionic Tooling
<p>$ npm install -g @ionic/cli native-run cordova-res</p>

# Create an App
<p>Create an Ionic Angular app that uses the “sidemenu” starter template and adds Capacitor for native functionality: <p>
<p>$ ionic start my-app sidemenu --type=angular --capacitor</p>  

# Change into App Folder
<p>$ cd my-app </p>

# Install PWA elements
<p>Capacitor plugins, including the Camera API, provide the web-based functionality and UI via the Ionic PWA Elements library.</p>
<p>$ npm install @ionic/pwa-elements</p>

# Build Project
<p>$ ionic build</p>

# Run The App
<p>$ ionic serve</p>

# Create New Service
<p>$ ionic g service services/myAppService</p>

# Create Andriod Project
<p>$ ionic cap add android</p>

# Create iOS Project
<p>$ ionic cap add ios</p>

# Copy Changes
<p>Every time we perform a build (e.g. ionic build) that updates your web directory (default: www), we will need to copy those changes into our native projects: </p>
<p>$ ionic cap copy</p>

# Sync Changes
<p>After making updates to the native portion of the code (such as adding a new plugin), use the sync command:</p>
<p>$ ionic cap sync</p>

# Open the native Android project in Android Studio:
<p>$ ionic cap open android</p>

# Open the native iOS project in Xcode:
<p>$ ionic cap open ios</p>

# Live Reload Android App
<p>$ ionic cap run android -l --external</p>

# Live Reload iOS App
<p>$ ionic cap run ios -l --external</p>
