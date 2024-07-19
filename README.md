# beatdash
This is the Beat Dash repository. It hosts files like the main levels, songs and much more!

# Pull Requests Guidelines
If you want to contribute on this repository, you can add songs. Levels and other modififcations will be denied.
## For songs 
The song to add must either be royalty free, or have licenses that can be followed with the current song system (Author, License and license link), or, alternatively have permission from their holders to be used in the Beat Dash Game.
You must add a mp4 video file with H264 for the video codec, and AAC for the audio, with a 1 by1  resolution. (MP4s are used since they're the most flexible type of file usable in GDevelop 5, the game engine used for developing this game.)

You should also make a JSON file like this:

{

    "name" : "Professor Umlaut",
    
    "author" : "Kevin MacLeod",
    
    "license" : "CC BY 3.0",
    
    "licenseLink" : "https://creativecommons.org/licenses/by/3.0/",
    
    "description" : "Super comedy action sequence. You'll know if you need this.",

    "downloadsizeMB" : 3.4
    
}

Make sure that the information **is all correct**.

Note that both the video and json file must have the same name, except for the file extension.

You shouldn't modify the AllSongs.json file to add the song, or do anything else, that's something that I will do.

# Notice
This doesn't host the entire game, this repository is for the client to fetch files and important stuff for the game to work.
