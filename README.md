# Close addons for [Dragory's ModMail](https://github.com/dragory/modmailbot)

### Setup: ###
Make sure your running at least v3.0.3 of Modmail.
in your config.ini file, make a new line and add:  
```ini
plugins[] = npm:MMPlugins/CloseAddons
```
Restart your bot!

And that's it!
Use:  
(by default, your prefix is !)
[prefix]messageclose <content> in a thread to close with just a message  
[prefix]reasonclose <content> in a thread to close with a reason.  
