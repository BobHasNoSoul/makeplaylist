# makeplaylist
create a .m3u playlist for each folder in the directory containing the mp3 files to be used for a itunes or music player playlist.

This creates a .m3u playlist in the name of the directory it is found in e.g.

```
/music/spice girls/spice girls.m3u
```

# Installation
just copy the "makeplaylist" and "folderlist" files to your "/usr/bin/" folder and make it executable with "chmod + x"

`sudo cp makeplaylist /usr/bin/makeplaylist && sudo cp folderlist /usr/bin/folderlist && sudo chmod +x /usr/bin/makeplaylist`

# Usage
go to the directory with all of your music folders you want turning into playlists (this will make one playlist for the files inside each of the folders)

run this command `makeplaylist` simple as that

example of the results if ran from /music directory in this made up example
```
/music/spice girls/spice girls.m3u
/music/avenged sevenfold/avenged sevenfold.m3u
/music/dr dre/dr dre.m3u

```
if ran from inside a single folder i.e. "/music/spice girls" you will only get the one playlist for that folder `/music/spice girls/spice girls.m3u`
