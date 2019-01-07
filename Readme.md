# TABLE OF CONTENTS

* [Welcome to the New Playable Subs Mod](#welcome-to-the-new-playable-subs-mod)
* [Current List of Playable Ships and Submarines](#current-list-of-playable-ships-and-submarines)
* [Other Important Changes **(MAKE SURE YOU READ THIS!)**](#other-important-changes)
* [Special Notes About Playable Surface Ships **(MAKE SURE YOU READ THIS!)**](#special-notes-about-playable-surface-ships)
---
* [**Mod Installation - Release Version**](#mod-installation-release-version)
* [**Updating the Mod**](#updating-the-mod)
---
* [Sonar Signature List Sorting](#sonar-signature-list-sorting)
* [Single Missions & Campaigns Color Coding](#single-missions-list-color-coding)



---
## Welcome to the New Playable Subs Mod

* This is modified New CaptainX's New Playable Subs Mod which follows a different development route.

* Although it is different branch, this mod will stay up-to-date with parent mod patches.


---
## Current List of Playable Ships and Submarines

* **United States**
  * Los Angeles (Flight I) Class SSN
  * Los Angeles (Flight II) Class SSN
  * Los Angeles (Flight III 688i) Class SSN
  * Narwhal Class SSN
  * Narwhal II Class SSN
  * Permit Class SSN (Early)
  * Permit Class SSN
  * Seawolf Class SSN
  * Skipjack Class SSN (Early)
  * Skipjack Class SSN
  * Sturgeon Class SSN (Early)
  * Sturgeon Class SSN
  * Virginia Class SSN
  * Improved Virginia Class SSN
  * Stingray Class SS
  * Ohio Class SSBN
  * Ohio Class SSGN (Conversion)
  * Ethan Allen Class SSBN
  * Washington Class SSBN
  * Nautilus Class SSN

* **United Kingdom**
  * Astute Class SSN
  * Trafalgar Class SSN
  * Upholder Class SS
  * Vanguard Class SSBN
  * Oberon Class SS
  * Resolution Class SSBN
  * Churchill Class SSN

* **Australia**
  * Collins Class SS
  * Oberon Class SS

* **Germany**
  * Type 209 Class SS
  * Type 212a Class SS

* **France**
  * Rubis Class SSN
  * Redoubtable Class SSBN
  * Triomphant Class SSBN

* **Italy**
  * Sauro IV Class SS
  * Toti Class SS

* **Netherlands**
  * Walrus Class SS

* **Norway**
  * Ula Class SS
  
* **Spain**
  * Galerna Class SS
  
* **Multi**
  * Scorpène Class SS

* **China (PLAN)**
  * Han Class SSN
  * Shang Class SSN
  * Sui Class SSN
  * Ming Class SS
  * Kilo Class SS
  * Romeo Class SS
  * Song Class SS
  * Xia Class SSBN

* **Republic of China (ROCN)**
  * Hai Lung Class SS

* **Vietnam**
  * Kilo Class SS

* **North Korea**
  * Romeo Class SS
  * Sinpo Class SSB

* **Japan**
  * Yushio Class SS
  * Oyashio Class SS

* **Russia**
  * Akula I Class SSN
  * Akula II Class SSN
  * Alfa Class SSN
  * Alfa II Class SSN
  * Mike Class SSN
  * November Class SSN
  * November II Class SSN
  * Sierra Class SSN
  * Sierra II Class SSN
  * Victor I Class SSN
  * Victor II Class SSN
  * Victor III Class SSN
  * Foxtrot Class SS
  * Kilo Class SS
  * Kilo II Class SS
  * Lada Class SS
  * Romeo Class SS
  * Tango Class SS
  * Whiskey Class SS
  * Borei Class SSBN
  * Delta III Class SSBN
  * Delta IV Class SSBN
  * Golf Class SSB
  * Hotel Class SSBN
  * Typhoon Class SSBN
  * Typhoon Class SSGN (Conversion)
  * Experimental Typhoon Class SSBN "Red October" (Conventional Drive)
  * Experimental Typhoon Class SSBN "Red October" (Silent Drive)
  * Yankee Class SSBN
  * Charlie I Class SSGN
  * Charlie II Class SSGN
  * Echo II Class SSGN
  * Juliet Class SSG
  * Oscar II Class SSGN
  * Papa Class SSGN
  * Yasen Class SSGN

* **Special Submarines**
  * Jive Turkey II Class SSN

* **Surface Ships**
  * Knox Class Frigate (United States)
  * Jiangwei Class Frigate (China)
  * Kirov Class Cruiser (Russia)



---
## Other Important Changes

* The Free Roam campaigns are set up so that the player is tasked with a SEAL insertion mission with an extremely long timeframe (2400-3600 hours) to allow the player to roam the map and sink enemies as their leisure. Once the player is ready, they can insert the SEAL team at the designated location and trigger the final SSBN hunting mission.
* Player home base in SCS campaign changed to Okinawa, since it is a much more likely location for a US sub base in this theater of operations, and hopefully will somewhat ease the issue of automatically failing your mission whenever you need to rearm. (Special Note: I am not changing the base back to Guam simply because there is no full base in Okinawa in the real world. The image used for the sub base in the SCS campaign is a simple submarine tender in an empty harbor, which means it could be anywhere.) 
* Minimum aircraft distance to allow exiting a mission (NearbyAircraftMinDistance) changed from 10000 to 3500, so you're not stuck waiting forever for aircraft to disappear after you sink their mothership.
* In this version of the mod, there is only ONE version of each sub instead of separate vanilla and playable versions like before. (This means that the playable Yasen you love will also be the Yasen you face in the campaigns and single missions.)



---
## Special Notes About Playable Surface Ships

Since the game is not designed for playable surface ships, we've had to make some special modifications to make them work properly and to make them fun to play. Below are some important special notes about them.

* The playable surface ships can only be used in the single missions and campaigns specifically designed for them. This is because we must set the starting depth for the ships to 0, otherwise they'd implode as soon as the encounter begins. This is why they are not available in the Quick Mission editor.
* As soon as you enter an encounter, all other surface ships in the area will instantly detect you. Submarines will generally take longer to pick you up, unless they raise their radar or periscope.
* The only weapons available for surface ships are the same as submarines: torpedoes and missiles. It is not possible to make their guns work because there is no coding in the game to allow a player to target a gun, and the game AI apparently won't work in any way on a player controlled ship.
* Although most of the playable ships do carry aircraft, there is no way that we can find to make these work for the player.
* We have not yet found any way to make the ship's anti-air defenses work at all, meaning you're going to take hits from enemy missiles almost 100% of the time (hence the massive tonnage mentioned below).
* All of the playable surface ships have been given a massive (obviously unrealistic) tonnage rating, in order to give them enough hitpoints to survive long enough to be enjoyable. This is especially important because torpedoes are much harder to evade than in a submarine, almost impossible really.
* They have also been given an unusually low self noise rating, to keep them from being instantly detected by every submarine in the area. If you keep your speed low enough, you might be able to evade detection by submarines for at least a little while.
* The playable ships have also been given special versions of their real life sonar suites that are MUCH more sensitive than anything else in the game. This will give the player a fighting chance of actually picking up the quieter enemy submarines, otherwise you'd be stuck in the encounter forever.
* All of the ships have also been given weapon loadouts that aren't actually used in real life. This is to allow them to fight properly, and give them proper loadouts when we release the playable surface ship campaigns. In addition, they do have wire guidance on their torpedoes to make things a little bit easier.



---
## Mod Installation (Release Version)

* STEP 1: [Click here](https://github.com/CaptainX3/CW-Playable-Subs/releases) to open the Releases page.

* STEP 2: Click on the **Source code (zip)** link to initiate the download. Save the ZIP file to your desktop or wherever you can access it easily.

* STEP 3: Double click on the ZIP file to open it. Inside you'll see a single folder called **CW-Playable-Subs** with the release date and version number. Click on this folder to open it.

* STEP 4: Now you'll see three files in the window - Readme.md, a Default UI folder, and an **override** folder. You want to extract ONLY the **override** folder to wherever you can easily access it.

* STEP 5: Open this directory **Steam\SteamApps\common\Cold Waters\ColdWaters_Data\StreamingAssets** and drag the **override** folder you just extracted into it. You should now see two folders here - **default** and **override**.

* STEP 6: You're done. Run the game and enjoy all of the new stuff!




---
## Updating The Mod

* To update the mod, follow STEPS 1 thru 4 in the installation instructions above for whichever version you want to use, and then navigate to **Steam\SteamApps\common\Cold Waters\ColdWaters_Data\StreamingAssets** and DELETE the existing **override** folder. Once you have deleted the old folder, you can then drag in the updated copy. **DO NOT DRAG THE NEW COPY AND TRY TO OVERWRITE THE OLD ONE - you will end up with major bugs this way!**



---
## Sonar Signature List Sorting

Sonar signatures have been reworked. You will see the entire vessel list when playing single missions, but the vanilla campaign signature libraries have been left as they were, since none of the new subs in this mod will appear in the campaigns. For single missions and modded campaigns, the signature list is sorted as follows:

* **Scrolling Right:**
  * Biologics
  * Civilians
  * NATO Subs
  * NATO Ships
  * Russian/Red Ships
  * Russian/Red Subs

* **Scrolling Left:**
  * Russian/Red Subs
  * Russian/Red Ships
  * NATO Ships
  * NATO Subs
  * Civilians
  * Biologics


---
## Single Missions List Color Coding

Single missions in the mod are color coded as follows:

* Red - These are custom missions for the Red side (Russia, China, etc) (Note: All playable subs will be available for the player to choose from, but the enemies will be from the Blue side.)
* Blue - These are custom missions for the Blue side (USA, UK, etc) (Note: All playable subs will be available for the player to choose from, but the enemies will be from the Red side.)
* Yellow - These are custom missions made specifically for the playable surface ships only.
* White - Vanilla missions from Killerfish, modified to allow all playable subs to be used.
* Orange - New missions sent to us by mod users, already designed with the mod's playable subs.
* Green - These are custom missions that are unique in some way, usually featuring only certain playable subs and/or a unique objective.


## Campaign List Color Coding

The campaigns in the mod are color coded as follows:

* Red - These are standard campaigns for the Red side (Russia, China, etc) (Note: All playable subs will be available for the player to choose from, but the enemies will be from the Blue side.)
* Blue - These are standard campaigns for the Blue side (USA, UK, etc) (Note: All playable subs will be available for the player to choose from, but the enemies will be from the Red side.)
* Green - These are free roam campaigns for both sides.
* Yellow - These are campaigns made specifically for the playable surface ships only.


