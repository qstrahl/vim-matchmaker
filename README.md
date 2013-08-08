#Matchmaker v0.1.7

Automatically highlight keyword matches as the cursor moves over them.

#Usage

* `:Matchmaker` turns it on
* `:Matchmaker!` turns it off
* `:MatchmakerToggle` toggles it

**Note:** this behaviour will change in version **1.0.0**; be aware! When it
does, the new usage will look like `:Matchmaker on` / `:Matchmaker off`.
`:Matchmaker!` will toggle it. This is to make way for more commands, like
maybe `:Matchmaker someOtherMatchingMethod` to change the matching behaviour.
Also, I like it more.

#Configuration

Add `let g:matchmaker_enable_startup = 1` to your `~/.vimrc` to enable
Matchmaker when vim starts.

#Contributing

This project uses the [git 
flow](http://nvie.com/posts/a-successful-git-branching-model/) model for 
development. There's [a handy git module for git 
flow](//github.com/nvie/gitflow). If you'd like to be added as a contributor, 
make some well-formatted pull requests (against the `develop` branch) and let 
me know.

#License

Same as Vim; see `:help license`
