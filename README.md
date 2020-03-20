# Twitch-clone
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
 - React
 - React-Redux
 - Redux-Thunk
 - React-Router
 - Google OAuth

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
