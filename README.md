# Realtime Document Collaboration
Realtime document sharing and editing web application for personal usage

## Demo
![Screencast from 18-07-21 04_31_33 PM IST](https://user-images.githubusercontent.com/44920607/126065438-95186507-1d6c-45ee-b186-7949c5452d05.gif)

## Features
- Generates link to start document
- Multiple users having link can edit the file
- Document is saved every 2s, ensuring persistent data across the link

## Installation
```bash
git clone https://github.com/nachiketkanore/realtime-document-collaboration.git
cd realtime-document-collaboration
npm install

# Run server
cd server
npm run devStart

# Start react app
cd ../client
npm start
```

Now the application will be running on `http://localhost:3000/`

## Packages
- Node.js
- React
- Socket.io
- Quill
