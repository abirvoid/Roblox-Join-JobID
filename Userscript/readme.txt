Join a roblox game's specific server if you know the JobID.

To find a server's jobID from inside a Roblox game, you'll need to use an executor and run:
print(game.JobId)

And then in your messages box write:
/console

This will show you a JobID example like:
3d93f8dd-0314-4856-8993-62449002e206

Use this Job ID with this userscript to later on run the game in same server.
Especially useful if you are using lua scripts which only run on specific server versions.
And you need to get into those servers at a later date.

Sometimes if you get error "This experience is restricted". It means server no longer exists or ID has been assigned to someone's private server etc.