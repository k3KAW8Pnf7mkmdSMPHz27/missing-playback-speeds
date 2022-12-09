# Playback speeds bookmarklets

Quick links for adding [bookmarklets](https://www.freecodecamp.org/news/what-are-bookmarklets/) that increase the playback speed of the first video player, e.g., fullscreen on YouTube.
Inspired by this [Quora answer](https://www.quora.com/Is-there-a-way-of-watching-YouTube-videos-at-higher-than-2x-speed).
To use, drag the link/image to the Bookmark bar and click it when you are on the page where you want to increase the playback speed.

<a href='javascript:(()=>{document.getElementsByTagName("video")[0].playbackRate=prompt("Playback speed","1.0");})()'><img alt="Bookmark for x times playback speed" src="https://img.shields.io/badge/Playback%20speed-x%20times-lightgrey"></a>

[![Bookmark for 2.5 times playback speed](https://img.shields.io/badge/Playback%20speed-2.5%20x-lightgrey)](javascript:Array.from(document.querySelectorAll('video')).forEach((v,b,c)=>v.playbackRate=2.5))

[![Bookmark for 3.0 times playback speed](https://img.shields.io/badge/Playback%20speed-3.0%20x-lightgrey)](javascript:Array.from(document.querySelectorAll('video')).forEach((v,b,c)=>v.playbackRate=3.0))

[![Bookmark for 3.5 times playback speed](https://img.shields.io/badge/Playback%20speed-3.5%20x-lightgrey)](javascript:Array.from(document.querySelectorAll('video')).forEach((v,b,c)=>v.playbackRate=3.5))

[![Bookmark for 4.0 times playback speed](https://img.shields.io/badge/Playback%20speed-4.0%20x-lightgrey)](javascript:Array.from(document.querySelectorAll('video')).forEach((v,b,c)=>v.playbackRate=4.0))

## Note

Many embedded videos use iFrames which cannot be accessed by the bookmarklet in order to prevent [Cross Frame Scripting](https://owasp.org/www-community/attacks/Cross_Frame_Scripting).

## Lasted tested in

Chrome Version 97.0.4692.99 on Ubuntu 20.04.

[GitHub repository](https://github.com/k3KAW8Pnf7mkmdSMPHz27/missing-playback-speeds)
