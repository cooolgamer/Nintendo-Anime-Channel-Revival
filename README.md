# Nintendo-Anime-Channel-Revival
Hello and welcome to this template of Nintendo Anime Channel revival! It mean that you have to edit it to add your own videos on it.

## How to use?
* Go to the [releases page](https://github.com/cooolgamer/Nintendo-Anime-Channel-Revival/releases),
* Download the "Anime Channel" archive,
* After extracting, copy the "luma" folder in the root of your SDcard,
* Make sure game patching is enabled on luma config (hold select while booting, check "enable game patching" then press start),
* Make sure it's connected to internet,
* Enjoy!

## How do I edit local contents?
* Edit luma\titles\0004000000141200\romfs\bootapp\resources\scripts\content\debugcatalog.lua file and that's it.
* If you have a error or a infinite loading screen after editing it, then something is wrong in the code or server.
* Enjoy!

## How to setup online catalog/videos?
* Edit the catalog content (server side\front\catalog.json file) and put it to your server,
* Edit luma\titles\0004000000141200\romfs\bootapp\resources\scripts\content\cataloghandler.lua file, line 5, set useDebugCatalog to false, and edit line 18 to your catalog path that is on your server.
* If you have a error or a infinite loading screen after editing it, then something is wrong in the code or the server.
* Enjoy!

## How do I edit catalog content?
You can [Go here](https://github.com/MettleSphee/3DS_EpisodeGenerator_AnimeTemplate) to know how it works and edit it easily thanks to MettleSphee :)

## More informations (Please read this!)
* Anime channel seems to use a special thing that make many websites like github, google drive etc. not working. The only website that use currently tested to work is archive.org.
* This use the [SSL patch](https://github.com/InternalLoss/3DS-SSL-Patch) to make it working, big thanks to the creator of it!
* 2DS/New 2DS only: 3D videos will shake on your screen while playing, to fix this on new 2ds, Enable the new 3DS CPU to clock+L2 (on luma config or rosalina menu), for old 2DS, there is no fix for now sadly. Note that anime channel doesn't support 3D videos and this is why this happens.
* Discord server for 3DS apps revival team: https://discord.gg/yGYe6ncSVQ .
* My discord server for my projects: https://discord.gg/r3xtwxb2nQ .
* Don't ask for the cia of Nintendo Anime Channel, I am not giving it.
