## Coalesced.ini
The coalesced.ini is an encoded configuration file that contains settings and object properties for the game, such as controls, ability data, difficulty scaling, and graphics settings. In FOC it contains all of the multiplayer customization data, allowing you to unlock parts for all classes, add custom colors, or merge parts together.

On PC, it can be found inside **`game folder\TransGame\Config\PC\Cooked`**

![](/media/coalesced_directory.png)

## Decoding & Encoding
In order to view and edit the coalesced, it must first be decoded using [this tool](https://community.pcgamingwiki.com/files/file/547-tf-games-configuration-utility/). 

Make sure to place it inside of the same folder as your coalesced.

> [!WARNING]
> Before making any changes to it, make a backup of the coalesced.ini in another folder!

### Decoding
1. Open **TFGames_Util_4.0**  
2. Type `d`
3. For input file name, type `coalesced.ini`
4. For output file name, type `coalesced.txt`

![](/media/coalesced_decoding.png)

### Editing
If decoded correctly, a new text file should appear in the folder. For WFC and FOC, this can be opened in any text editor such as Notepad and edited from there.

However for ROTDS, the text file <ins>must</ins> be opened in [Notepad++](https://notepad-plus-plus.org/downloads/) to prevent corruption. If you accidentally save changes to it with regular Notepad, delete the text file and decode the .ini again.

After editing, you must re-encode it for the game to read your changes.

### Encoding
1. Open **TFGames_Util_4.0**  
2. Type `e`
3. For input file name, type `coalesced.txt`
4. For output file name, type `coalesced.ini`

![](/media/coalesced_encoding.png)

Once done, you can launch the game as normal and your changes will be applied.
