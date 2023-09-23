# Unofficial NotITG VSCode Documentation

Based off of [FiguraVSDocs](https://github.com/GrandpaScout/FiguraRewriteVSDocs) (thank you GS)

Requires the following to work:
- [Lua Server Extension](https://marketplace.visualstudio.com/items?itemName=sumneko.lua)
- [Save and Run Extension](https://marketplace.visualstudio.com/items?itemName=wk-j.save-and-run)
- Lua 5.1 installed on your machine

Recommended:
- [XML (Stepmania) Extension](https://marketplace.visualstudio.com/items?itemName=fms-cat.xml-stepmania)

## Installing Lua:
### Windows
https://www.lua.org/ftp/lua-5.1.5.tar.gz

### Mac
http://lua-users.org/wiki/MacOsxLua  
or via brew:
```bash
brew update
brew install lua
```

### Linux
```bash
sudo apt install lua
```
or whatever package manager you have

## Setting this up
1. Download all the files in here by clicking [here](https://github.com/SpiritAxolotl/NotITG_VSDocs/archive/refs/heads/main.zip)
2. Unzip, copy the files, inside, and paste them into the same directory as the modfile you want to use this with
3. Go into the `.vscode` folder, rename `yourname.code-workspace` to something with your name (optional but why not)
4. Open the code-workspace file. Change the `<PATH>` on the 14th line to the filepath to your modfile.
5. Profit.

## License
BBHL  
https://lifning.neocities.org/BBHL

## Credits
- [Spax](https://github.com/SpiritAxolotl) for starting this project  
- [GS](https://github.com/GrandpaScout) for his [FiguraVSDocs](https://github.com/GrandpaScout/FiguraRewriteVSDocs) that inspired this project to begin with, as well as answering many VSCode and Lua questions  
- [CraftedCart](https://gitlab.com/CraftedCart) for her [unofficial NotITG documentation](https://craftedcart.gitlab.io/notitg_docs/) that was used for most of the API  
- [XeroOl](https://github.com/XeroOl) for making the [mirin template](https://xerool.github.io/notitg-mirin/) and the [`converter.lua`](https://github.com/XeroOl/notitg-xml-to-emmylua) file  
- [Oatmealine](https://oat.zone) for general help  
- [Taro](https://github.com/TaroNuke), [Sora](https://heysora.net), and the rest of the team that created NotITG and the community surrounding it