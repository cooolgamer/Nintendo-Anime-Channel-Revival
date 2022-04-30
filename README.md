# Nintendo-Anime-Channel-Revival
Hello and welcome to this template of Nintendo Anime Channel revival! It mean that you have to edit it to add your own videos on it...

## How to use?
* Go to the releases page (https://github.com/cooolgamer/Nintendo-Anime-Channel-Revival/releases),
* Download the "Anime Channel" archive,
* After extracting, copy the "luma" folder in the root of your SDcard,
* Make sure game patching is enabled on luma config (hold select while booting, check "enable game patching" then press start),
* New 2DS only: Enable the new 3DS CPU to clock+L2 (on luma config or rosalina menu), it fix videos glitching,
* Make sure it's connected to internet,
* Enjoy!

## How do I edit local contents?
* Edit luma\titles\0004000000141200\romfs\bootapp\resources\scripts\content\debugcatalog.lua file,
* Note that video format used by this app is .moflex
* If you have a error or a infinite loading screen after editing it, then something is wrong in the code.

## How to setup online catalog/videos?
* Edit the catalog content (server side\front\catalog.json file) and put it to your server,
* Edit luma\titles\0004000000141200\romfs\bootapp\resources\scripts\content\cataloghandler.lua file, line 5, set useDebugCatalog to false, and edit line 18 to your catalog path that is on your server,
* Note that video format used by this app is .moflex
* Enjoy!

## More informations
* This use the SSL patch to make it working, big thanks to the creator of it: https://github.com/InternalLoss/3DS-SSL-Patch
* Discord server for 3DS apps revival team: https://discord.gg/yGYe6ncSVQ
* My discord server for my projects: https://discord.gg/r3xtwxb2nQ
* Don't ask for the cia of Nintendo Anime Channel, I am not giving it.
