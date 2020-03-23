# Twitch-clone || Streamer
This is a simple react clone of twitch. The purpose of this project is to help me solidify the concepts of react and redux

Open Broadcast Software => Real Time Messaging Protocol (RTMP) server => Viewer's Browser

# Features
> A user that's not logged in is limited to doing the following:
 - view a list of all streams/channel
 - view a video for a single stream

> A user that's logged in can:
 - create a new stream/channel
 - edit a stream/channel they own (i.e created)
 - delete a stream/channel they own (i.e created)

# Dependencies
> Tools and Libraries used
 - [React](https://reactjs.org/)
 - [React-Redux](https://react-redux.js.org/)
 - [Redux-Thunk](https://www.npmjs.com/package/redux-thunk)
 - [React-Router-Dom](https://www.npmjs.com/package/react-router-dom)
 - [Google OAuth](https://support.google.com/a/answer/162106?hl=en)
 - [Redux-Form](https://redux-form.com/8.3.0/)
 - [Json-server](https://www.npmjs.com/package/json-server)
 

# Streams Components
 - index Page (StreamList)        
    `'/'`
 - Show Stream (StreamShow)       
    `'/streams/show'`
 - Create Stream (StreamCreate)   
    `'/streams/new'`
 - Edit Stream (StreamEdit)       
    `'/streams/edit'`
 - Delete Stream (StreamDelete)   
    `'/streams/delete'`
