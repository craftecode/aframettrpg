# Aframe TTRPG test using Networked Aframe by haydenjameslee / @HaydenLee37

Built with [Networked-A-Frame](https://github.com/haydenjameslee/networked-aframe), a web framework for building multi-user virtual reality experiences. Works on Vive, Rift, desktop, mobile platforms.

Click and drag on desktop. Open it on a smartphone and use the device motion sensors. Or [plug in a VR headset](https://webvr.rocks)!

Activities for me to look at
 - new NAF version? package.json is indicating that there is a version 6.1 of networked aframe
 - Firebase: for getting scene changes to persist on the server (e.g. so a GM could connect, arrange things then have players join and see models in the new positions) Hayden suggested using Firebase (https://github.com/networked-aframe/networked-aframe/issues/139)
 - Aincraft - check it out for making things appear  https://glitch.com/edit/#!/aframe-aincraft?path=index.html:1:0
 - understand this thing on creating networked entities - https://www.npmjs.com/package/networked-aframe - I tried it with initing a position animation on one client but it didn't show up on the other.
 - Sandbox Citybuilder by @kfarr
 - Tools - WebVR Studio @webvrstudio
 - data visualization - Adit @datatitian
 - tutorial https://github.com/networked-aframe/networked-aframe/blob/master/docs/getting-started-local.md
 - boardgame.io might have something cool https://github.com/nicolodavis/boardgame.io
 - state component for aframe - https://github.com/supermedium/superframe/tree/master/components/state/
 - networked grabbable - this might be relevant for me -https://www.youtube.com/watch?time_continue=125&v=Gd-Qc9TuHZ0

Hayden's examples to check out
- Tracked controllers shows controllers to other participants as little cubes - https://haydenlee.io/networked-aframe/tracked-controllers.html
- Allow for different rooms to be created so different groups of people can use it at the same time and put a username above your head - https://glitch.com/edit/#!/naf-form-example


https://github.com/supermedium/superframe#readme
see this for some more things

Thinking to use some paper minis to start for greatest ease for customisation by others
 - https://printableheroes.tumblr.com/
 - https://drive.google.com/drive/folders/0B9wKLjixK7DHd3pMZk92Z2xhdVk (https://www.reddit.com/r/DnD/comments/5gpodp/oc_free_dd_paper_miniature_resource/)
 https://www.dmsguild.com/product/218395/Old-School-Adventurers-Paper-Miniatures
 ! One issue with using transparent backgrounds is that depending on order in the html some things using transparency might be hidden by the transparent parts of other things. 
 If Sam is behind Jordan in the scene then Sam will need to be above Jordan in the HTML to avoid being hidden.
 This may be a fix - https://github.com/supermedium/superframe/tree/master/components/render-order#aframe-render-order-component
 
 Added superhands https://github.com/wmurphyrd/aframe-super-hands-component
 
 Big & Small - how to have some players be big and some be small at the same time. - Possibly using this - https://github.com/supermedium/superframe/tree/master/components/firebase
 Don't broadcast the scale of the map
 That means one person could be looking at the map like it's on a tabletop, another could be looking at it like it's lifesize.
 