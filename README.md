# First install dependencies
npm i

# Start on VSC
ionic start

# Generate the www folder
ng build

# Generate the native project, if it does not already exist
ionic capacitor add android

# Develop the Ionic app and sync it to the native project
ionic capacitor copy android

# First install dependencies
ionic capacitor sync android

# Prepare app to run on Android studio
"target": "es6" (tsconfig.json)
