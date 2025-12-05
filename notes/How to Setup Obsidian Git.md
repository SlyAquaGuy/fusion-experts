#Documentation #Admin 
*Author: Aquaguy*
# 1 Installation
1) Make Sure Obsidian and Git are both installed on your host machine
2) Install the [Obsidian Git](https://github.com/Vinzent03/obsidian-git) plugin (can be done through the community marketplace, it's just called *Git*)
# 2 Github+Permissions
On the github website when logged in:
1) Click your profile picture
2) Click settings
3) Click Developer Settings
4) Click Personal Access tokens->Tokens (Classic)
5) Generate a new token with relevant access settings for the *fusion-experts* repository
*Read and Write access to code, commit statuses, custom properties for repositories, discussions, issues, merge queues, pages, pull requests, and repository hooks*
6) Copy the token ID. This will be stored in plaintext in your obsidian repo so don't share your config publically.
# 3 Syncing
Inside obsidian with the git plugin enabled:
1) Create a "Fusion" folder in the sidebar of obsidian- this will be what is synced and is separated from personal notes.
![](media/Pasted%20image%2020251205194554.png)
2) Change the following setting in the "git"
3) Hit Cmd+P to access the command pallette
4) Run the following command:  "Git: Clone an existing remote repo"
![](media/Pasted%20image%2020251205194306.png)

5) For the URL, type in:
```
https://<PERSONAL_ACCESS_TOKEN>@github.com/SlyAquaGuy/fusion-experts.git
```
5) Type in the same folder as above when prompted.
6) Restart Obsidian.
7) Cmd+P and run the command "commit and sync" to sync changes, bind to *Cmd+S* if you're feeling quick


# 4 Recommended Plugins and Settings
This is all personal preference, but after a couple years of using obsidian and trying a bunch of the plugins, this is what I've landed on as the most useful combination. I do *everything* in obsidian including reference management, latex exports/rendering, basic drawings, latex equations, etc.
## 4.1 Plugins
Mostly my preference, but here's what I use.
- Excalidraw
- Git
- Image Captions
- Ink (optional)
- Latex Suite (key)
- mousewheel image zoom
- number headings
- omisearch
- pandoc plugin
- pandoc reference list
- table to csv exporter
- templater
- zotero integration

A lot of these require a good bit of config, tuning and getting used to- reach out if you want a tut but i might write some more up.

## 4.2 Settings
- Turn off Wikilinks. This allows image insertion in latex and for github publishing
- Add a /media/ folder path for images, etc
- customise and toy around! will at tweaks and more tips soon.




