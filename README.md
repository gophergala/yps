yps - Youtube Playlist Synchronizer
===

yps helps you get your Youtube playlist saved as mp3s so you can listen your favorite video lectures while on the move.

A good example for this would be: [Computer Science 61B - Fall 2006](https://www.youtube.com/playlist?list=PL4BBB74C7D2A1049C) or
[Google NYC Tech Talks](https://www.youtube.com/playlist?list=PLAD8A7B6D66DDD297)

TODO
---

In priority order:

- [ ] Implement a way to get the video in mp4 format from YouTube
    - [ ] If not possible, check what other services are doing
- [ ] Convert the mp4 into a mp3 file
- [ ] Save mp3 file into user destination
    - [ ] Google Drive (check if they have an API)
    - [ ] Dropbox (maybe? check if they have an API)
- [ ] Implement an interface to receive a single video ID
- [ ] Implement an interface to receive the playlist ID
- [ ] Process playlist request and divide items into tasks (using a MQ) to save file independently
- [ ] Make a pretty interface

Technologies used
---

***TODO*** Check if this is what we need or we need more

- [ ] AppEngine
    - [ ] Task Queue
- [ ] Go
    - [ ] GorrilaWebToolkit - [http://www.gorillatoolkit.org/](http://www.gorillatoolkit.org/)

Legal stuff
---
This should be a way to save material for later listening, while on the move. Please respect the copyright of the authors of the respective videos.
