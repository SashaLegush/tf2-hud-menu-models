# VGUI Menu Models

This same setup is used in (currently in development branch of) [SolarLight-HUD Redux's](https://github.com/SolarLightTF2/solarlighthud-redux/tree/team-class-select-revamp) team menu

This repository uses the same method used there to compile almost every other VGUI menu model in tf2, with a few exceptions

# Usage

Let's say you want to get the class selection model in your custom HUD, you need to download the source of the repository, open the folder <ins>ui_class01</ins>, and drop the sub-folder named models inside of your HUD's root directory (where info.vdf is located)

Upon loading into the game, your class selection screen will be a missing texture mess, that is because you need to add the textures, simply go to materials/vgui/replay/thumbnails (if you dont have those folders, simply create them) and create a folder called models inside of it, put the vtf's and vmt's that you need and restart TF2/run a sv_cheats 1;mat_reloadallmaterials command in console, if you did everything correctly, it should use the textures you provided and work in every server, no matter what sv_pure value is set

In theory, this can also be used to load fully custom models, for example, to replace the round sign model with a fully custom one, complete with a custom animation
