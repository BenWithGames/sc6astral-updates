# Soul Calibur VI: Astral

## How to install
Download an alpha build [here](https://github.com/BenWithGames/sc6astral-updates/releases). Extract anywhere and run `Install.cmd`. The prompt will ask you for the path to your SoulcaliburVI installation. Enter your path and press enter. Exit the command line when finished. Open Soul Calibur VI. **Make sure to set your game to borderless windowed mode to see the overlay**. The overlay will let you know if there is a new build to download. If there is, it will install it and you will have to restart your game to activate the new build.

The overlay automatically checks for new builds when you start the game and will check every 15 minutes to see if there is a new build. **You must be on the same build as your opponent to play rollback**.

## How does it work

The Astral mod right now is still in an alpha state, so some features are still in a work of progress. Currently, the game is hardcoded to be 3 frames **MAX**. This does not mean every correction will happen in three frames. It also has hardcoded 0-2 frames of delay based on ping. Each round, both computers will agree what the frames of delay will be based on the ping at the start of each round. 

**Transatlantic and transpacific connections have not been tested.** Use at own risk.

The mod only supports 1v1 private lobbies and ranked mode. 3+ lobbies are not supported, but will be a priority once rollback is finished. The Astral mod will automatically detect if the opponent also has the Astral mod and enable rollback. If your opponent does not have the mod, you will be defaulted to the native SC6 netcode, so you can take this mod into ranked with no issues.

## Replays

Replays are desynced from the rollback input history. End of round replays and in-game, full match replays will show what the game would've been like had it been native delay based netcode. It will not replay the rollback game. And honestly, spectating in lobbies will probably be desynced as well. This is not a priority to fix right now.

## Known issues

There are still bugs being discovered that freeze the game. When this happens, failure logs will be saved to `~/path/to/sc6/SoulCaliburVI/Binaries/Win64/Mods/SC6Rollback/logs/fail`. Send the latest `.zip` file for both players. The `.zip` file will have matching id's on them to indicate what match it is. Send them to my discord @benwithvees and tell me which characters and stage you used for that match.

There's also an issue when activating CE and SC can flip the camera 180 degrees and swap sides of the screen. This is a weird bug caused by the mod. Since this doesn't necessarily effect gameplay since it happens right when tha animation pops and not during gameplay, this currently is not a priority to fix, but something I do plan on fixing eventually

