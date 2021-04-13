# Planned Features & Ideas

1) new node types (spreadsheets, 3D models, events, reminders, timelines, video, mini text cards, empty nodes, etc)

and of course some of this stuff, like the empty nodes idea, might imply a bit of refactoring to how the overall node creation UI works, possibly. or at least the possibility is there

2) additional views & sorting

right now there is the association browser and the graph visualizer, but there could be other views! for example, there could be a view which renders a 3D graph instead of the 2D one, or a view which lets you edit parts of the database directly. there could also be more types of visualizations

3) theming

this is a planned feature, kind of just a quality of life thing tho

4) social features

will need a way to set node sharing level. anything from private to local to friends only to public. at this point there will also need to be a security review of the site

a big feature here is that whatever nodes you make "public" would be able to be seen by anyone nearby even in public...well. something like that. details would be worked out at time of implementation

5) quality of life stuff

ability to reset password, error logging so when something breaks users can send me the logs (i should add logs asap tbh), keyboard shortcut for creating nodes

6) LAN update

this already technically almost works, but won't really be possible until the groundwork is there for the social update. once the social features are added it will be ready to tweak, in node js, the code necessary to allow sharing between devices, like apple's airdrop except as a social platform

7) a plugin system

maybe should have listed this earlier, because it kind of ties into adding node types & views & stuff. basically, the entire app could probably be made of plugins, it could be 99% plugins. this would require a redesign though and maybe breaking changes. i don't know what to do about the possibility for breaking changes since they might require a custom importer for old data exports or something. might be extra work

8) phone application (synthona portable)

this would be able to connect over LAN connection to the desktop node server, with a proper login. which would allow you to sync data between your phone and laptop seemlessly, and take it with you on the phone

the phone version could also have a lot of custom events and node types based on things like siri, accelerometer data, location data, etc

the thing to keep in mind though is that the synthona client is already almost a progressive web app, and so that could be another route to portable phone access

9) P2P update 

this would come after the LAN update, after everything was settled with that, secure, working well. some protocol for connecting 2 computers directly to each other via IP address or whatever

10) websocket update

i guess i am writing these all out of order lol. this should probably be part of the LAN update. this will be a big win allowing react and node to pass information in real time for better notifications, progress meters, and synchronization between client and server

11) synthona email

pretty self explanatory really

12) better organizational structures

maybe there are more ways besides pinning things to keep things organized

13) auto-association

right now you create all associations by hand, but it would be trivial to have programmable events which associate or unassociate nodes. for example, as you click through from one to another, they could be associated in a chain to each other if they already weren't

14) chat

i think chat was always planned. something like discord, except with the ability to associate nodes with messages or conversations

15) linking & launching external software & programs

ability to do things like launch games or other programs or files with synthona

16) circular infinite scroll

had thought about how the main page could be circular, where when you get to the top it takes you back to the bottom, & vice versa in a loop. idk lol

17) graph editor

updates to the graph visualizer to allow things like associating nodes directly on that screen, creating new nodes there, etc. also other things might be interesting like directional links, custom icons, etc

18) allowing other programs to use synthona as a file picker

19) slideshows

actually maybe this is unnecessary since the app can kind of already do this? i think there is room for pulling in inspiration from powerpoint tho

20) automatic updates

this would be nice but requires buying expensive code signing certificates

21) CLI tool

extremely unnecessary though could be fun

22) additional export types

option to export notes as pdfs, docx, etc. same with images

23) image editor

HTML5 canvas should make this actually pretty easy to implement

24) you could basically make a whole creative cloud around this project really

25) integration with unity or unreal engine via the sqlite? idk how this would work tho or if it's worth pursuing, however i think it would be nice to be able to access the synthona db from other programs and from a game

26) additional configuration options and settings for users

27)  figure out how to make .synth files open in synthona when you double click them, and how to set an icon for them

28) allow drag and drop files into synthona

29) synthona media server?

this is basically something you sort of get for free with the P2P and social updates, provided video streaming and audio streaming are implemented. not too difficult really
