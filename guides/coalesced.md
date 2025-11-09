## Coalesced.ini
The coalesced.ini is an encoded configuration file that contains settings and object properties for the game, such as controls, ability data, difficulty scaling, and graphics settings. In Fall of Cybertron it contains all of the multiplayer customization data, allowing you to add custom colors or merge parts together.

On PC, it can be found inside `game folder\TransGame\Config\PC\Cooked`

## Decoding & Encoding
> [!WARNING]
> Before making any changes, make a backup of your coalesced in another folder!

In order to view and edit the coalesced, it must first be decoded using [this tool](https://community.pcgamingwiki.com/files/file/547-tf-games-configuration-utility/). 

Make sure to place the tool inside the same folder as your coalesced.

### Decoding
1. Open **TFGames_Util_4.0**  
2. Type `D`
3. For input file name, type `coalesced.ini`
4. For output file name, type `coalesced.txt`

![](/media/coalesced_decoding.png)

### Editing
If decoded correctly, a new text file should appear in the folder. This can be opened in any text editor such as notepad.

> [!WARNING]
> For Rise of the Dark Spark, the text file **must** be opened in [Notepad++](https://notepad-plus-plus.org/downloads/) to prevent corruption. If you accidentally open and save changes to it in regular Notepad, decode the .ini again.

### Encoding
