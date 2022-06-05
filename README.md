Streamy is a simple app designed for hosting user's streaming. 
Users can login/logout with outside service providers like Google, Facebook, Linkedin, etc.
Users have abilty to add, edit, delete streams, display streaming video with help of OBS.

Tech stack:
- React
- Redux
- React-Redux
- OAuth authentication
- Redux Form
- React Router

To start the project:
- open project in IDE and run command in terminal: npm start
Set up json-server:
- open new terminal window, navigate to folder Api and run again command: npm start
Set up RTMP Node Media server:
- open new terminal window, navigate to folder rtmpserver and run again command: npm start

Additionally to stream a video set-up for OBS is required:
 - URL for hosting: rtmp://localhost/live
 - Stream key: id of the stream that is actually viewing in the browser
