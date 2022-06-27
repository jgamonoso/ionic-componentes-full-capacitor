# First install dependencies
npm i

# Start on VSC
ionic serve

# Generate the www folder
ionic build

# Generate the native project, if it does not already exist
  # Install the Capacitor platform package
  # Copy the native platform template into your project
ionic capacitor add android

# Develop the Ionic app and sync it to the native project
  # Perform an Ionic build, which compiles web assets
  # Copy web assets to Capacitor native platform(s)
<!-- ionic capacitor copy android -->

# Update dependencies
  # Perform an Ionic build, which compiles web assets
  # Copy web assets to Capacitor native platform(s)
  # Update Capacitor native platform(s) and dependencies
  # Install any discovered Capacitor or Cordova plugins
<!-- ionic capacitor update android -->

# Copy + update dependencies
  # Perform an Ionic build, which compiles web assets
  # Copy web assets to Capacitor native platform(s)
  # Update Capacitor native platform(s) and dependencies
  # Install any discovered Capacitor or Cordova plugins
ionic capacitor sync android

# Prepare app to run on Android studio
"target": "es6" (tsconfig.json)


ionic capacitor run android -l --host=172.21.192.1