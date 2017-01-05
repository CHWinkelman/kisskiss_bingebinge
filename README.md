# kisskiss_bingebinge
A serial tracker and binge-enabler for shows from illicit content streamer KissCartoon

This is my first project so I don't yet know how this will go.
My intent is to create a chrome extension which would allow for seamless play of HTML5 video from the website KissCartoon. Perhaps at some point more websites will be added. It should also enable set-and-forget for video quality. Finally (possibly), it should track which episode was last watched and be able to correctly point to the next episode.
Work will have to be done to figure out how to mess with Kiss's settings and possibly how to play HTML5 video in its own tab. Work will also go into the indexing of episodes for a series, possibly with filtering for shows with different naming conventions. Possibly some sort of option should be available to either randomize episodes while still holding its place, a complete random playing of the entire series, and also the ability to change season order if the program is messing it up. 
There should be a process which runs on initialization of a show, which indexs episodes and creates a proper order to episodes and seasons. 
Another process should run at watch time which will advance a counter for current episode and also provide continuous play after the end of each episode, maintaining video quality (360, 480, 720, 1280, largest available, smallest available). 
