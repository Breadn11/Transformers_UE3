# Binds
Due to the games having their developer consoles stripped, adding custom keybindings (or "binds" for short) in the Coalesced is the most common way to use console commands. 

> [!TIP]
> Before continuing, make sure you've read [this guide](./coalesced_decode&encode.md) on how to edit the coalesced!

## Layout of a Bind
Let's use this bind as an example:

`Bindings=(Name="F1",Command="showhud",Alt=True)`

**F1** is the key that you need to press in order to activate it.

**showhud** is the command that's being executed.

**Alt=True** requires you to hold "Alt" at the same time as F1 in order to activate the command. Other modifier keys include **Shift** and **Control**.  

## How to Add Binds to the Coalesced
Open the coalesced text file, and search (Ctrl + F) for `Engine.PlayerInput`

A few lines below, you should see a bunch of entries starting with `Bindings=`. You can add your binds here with the default ones. 

I recommend placing them above the existing binds like this for organization and ease of access.

![](/media/coalesced_bind_invert.png)

# List of Console Commands

`qdwqdwdq`
