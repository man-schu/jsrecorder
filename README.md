# jsrecorder
Recording audio, video and screen

Find the application here: https://man-schu.github.io/jsrecorder/

It even works without a webserver. So, if you do not trust the github website, the best is to copy the whole  folder "recorder" to another place on your local PC and then just double click on index.html. However, if you have a look at the file types it is using, it is obvious that it is all running only on the local PC. Nothing is being stored on a server.

Use cases are:

* audio recording, for instance to save the audio of a meeting
* video recording, for instance to grab a speech of yours
* screen recording, for presentations, if users want to show an incident to their helpdesk etc.

The downside is that it can only record in the webm format. Otherwise it would need additional software.

The disadvantages of the webm format are basically the file size and that it is not so easy to jump to a specific moment when you reproduce it.

However, for small files the filetype webm is ideal to embed in web pages as any modern browser can play it without the need of further software.



## Credits

Credits go to https://github.com/dhruv479/recorder, from where I have taken the actual application. Nevertheless I decided to create my own project based on it, in order to work on the layout, adding some help pages, remarks and hopfully features.
