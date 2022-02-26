# Keeper

## About
Have you ever run a command that you thought was cool? Did you want to keep it forever? Meet my favorite alias `keeper`.  Running `keeper` will take the command entered prior and add it to a "hidden" file in your home directory called `.keeper.txt`

## Installs/dependencies 
None. Using standard POSIX components.

## How to Setup
In your shell's config (`~/.bashrc` for Bash and ~/.zshrc for ZShell) add this line:

`alias keeper='echo $(history -p !!) >>~/.keeper.txt'`

Then run this command to access the new alias right away:
`source .bashrc`
(I'm assuming you're using Bash in this example... swap for .zshrc if you're ZShell)

## How to Use
After running a command that you like, run `keeper` on the command line without any command line arguments. 

## Warnings/issues
Like all aliases, this is a per system and non-standard change. If you get used to it, you may need to take your shell rc config file with you on other systems.

## Thanks
To Josh Wright for suggesting a viable syntax! 
