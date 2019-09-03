# "I only upload high quality video game rips."
## - SiIvaGunner

This is some kind of (wip) database thingy I'm building for a command for my bot, [Hitomi Manaka#4825](https://discordapp.com/oauth2/authorize?client_id=431495393520386068&scope=bot&permissions=8), which will include a list of all of [SiIvaGunner's](https://www.youtube.com/channel/UC9ecwl3FTG66jIKA9JRDtmg) albums and it will also allow you to see their descriptions and mega/bandcamp/drive links and everything.

Sounds cool, right? Thanks hehe

You're free to contribute too (cuz I keep forgetting to finish this), just keep in mind this:

- Follow the format that is present in the other albums
- Don't add anything in the `songs` part of each album. Yet
- The `description` object of each album refers to the description that appears on the announcement video for each album, skipping the download links and the catchphrase
- In case anything in the album does not exist (like, the download links for mega or drive):<br/>
  - If it's the description of the album announcement video, either don't change it or just change to something like "[no description]" or something<br/>
  - If it's the album cover, replace it with [this image](https://media.discordapp.net/attachments/573889654273736704/610407729902649372/resize-17.png)<br/>
  - If it's the mega/drive/bandcamp links because the announcement video says something like "(Coming soon)", change them to that. Or if they're missing, just put something like "none"
  - If there isn't anything to add in the `other` array from each album, just don't add anything
- Most of the album themselves ARE added, and you just need to put in them the missing links and the other stuff inside them
