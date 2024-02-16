# SWAT-Bot-Commands
An experimental feature that allows collaborators to create and implement commands in a sandbox using a unique and simple Discord bot script, for the SWAT Discord bot.

## Reference and Resource
Please feel free to use the wiki of the Discord bot script as a resource. The script is known as **BDScript**, which stands for **Bot Designer Script**.
The latest version of this script is **BDScript 2**. In SWAT Bot, all commands use **BDScript 2**.

https://nilpointer-software.github.io/bdfd-wiki/

## Basics
BDScript is primarily made up of functions. A function starts with a `$`, followed by its name. An example of a function is `$nomention`, which can be used to not mention or ping the author. Another example of a function is `$dm`, which can be used to send the message to the author's DM.

However, functions may need a value. You do not need to provide data in the `$dm` function. But, if we talk of the `$title` function, which adds a title to an embed, it needs a value. You need to provide the text of the title, which can be done by using square parentheses (`[]`) to give it a value.

```
$nomention
$title[This is a title of an embed!]
```

In this case, `$nomention` did not mention or ping the author. And, `$title` created an embed and set its title to "This is a title of an embed!"

## Examples
```
$nomention
$dm
Hi! I am now in your DMs!
```

```
$nomention
Your user ID is `$authorID`!
And, your username is `$username`!
```

```
$nomention
**See my DM!**
<#$dmChannelID>
```

Please message the bot developer to gain access to the `.eval` command, which allows you to execute BDScript on Discord.
