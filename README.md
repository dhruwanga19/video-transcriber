# A Simple Voice to Text application with Google AI Speech to Text API

Upload a video you want to transcribe and let AI give you a full transcript of the video in the side panel. Make changes to the transcribed text in the built-in text editor according to your preferences.

## Settting up the application

1. git clone this repo
```
git clone https://github.com/dhruwanga19/video-transcriber.git
```
2. go to `backend` directory
```cd backend```
3. create a `uploads` folder
```mkdir uploads```
4. run the `npm install` command to install all modules from `package.json` 
```npm install```
5. start the node.js server
```node server```
6. go to `frontend` directory
```cd ./frontend```
7. run the http server which serves the index.html page
```npx http-server ./frontend```
8. Open `localhost:8080` in your browser
9. Upload the video file and hit the `transctibe` button and wait for the video to load
10. See the text in the text editor on the right, edit the text according to your preference, Copy the text use it wherever you want!
