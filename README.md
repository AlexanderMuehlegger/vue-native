
# Vue-Native Installation Guide

### Step 0 - Check if Node.js is installed 

    node -v 

- If a Version is getting returned you can jump to **``Step 1``**
    
- Download Node.js with the link below:

  **https://nodejs.org/en/**

### Step 1 - Install ``yarn``

    npm install -g yarn

### Step 2 - Install required dependencies
- Install the Vue-Native CLI

        npm install -g vue-native-cli
    
        yarn global add vue-native-cli

- Install the Expo CLI

        npm install -g expo-cli
            
        yarn global add expo-cli

### Step 3 - Create Project
- Create Vue-Native Project
    
        vue-native init <project-name>
    
- Open Project Directory and start the Application

        yarn expo start

### Step 4 - Open Project on Smartphone
- Download ``Expo Go`` from the ``Play Store`` or ``App Store``
- Scan the Provided QR-Code in the Terminal
