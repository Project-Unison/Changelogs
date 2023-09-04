# September 4, 2023: September Midseason Update
Welcome to yet another Midseason Update! As we announced this changes earlier, this update brings tons of adjustment and improvements, heavy refactoring of whole map rotations, and addressing the issue of ongoing server issues and much more. This update brings 3 new community maps, 2 new Live TF2 community maps, 4 new map updates and tons of adjustments, improvements and fixes. I know, it is midseason update but for me fixing things was very important. Also, trust me, this wiil be the last migration, and we will stay there longer no matter what happens. New IP for TF2C server: `45.76.192.35`

* Added three new community maps: A/D Outflow, KOTH Shorelight, PL Fifthcurve
* Added two new Live TF2 maps that were missing on Live TF2 category addition update: A/D Altitude, PL Swiftwater
* Added back A/D DeGroot Keep, CP Sulfur, CTF Isotope, PL Effigy to rotation as 'Specialty' category
* Added `!translator` command, which allows you to enable translation that translates your language to others automatically
> Communication is key of the game - If you are non-english user who cannot speak English or barely speaks English, enabling this feature is highly recommended! It allows you to translate messages to others while using your native language in chat. Hopefully this feature should help users understand the language that you are speaking natively.
* Goodbye, TF Birthday - TF Birthday event has ended, reverted changes made for TF Birthday
* Made clarification for consequences of violating the server rules
* Renamed server name to Hi-Speed Custom Weapons (Was Hi-Speed New-Old Weapons Pack!)
> Due to people frequently leaving the server while downloading the weapons assets, we had no choice but had to change server name to be more appropriate so people will acknowledge that server is using custom weapons.
* Changed hosting provider to previous one, as the current one was lacking performance and caused frequent Out-of-Memory error, hopefully this should give more server performance
* Updated TF2C Dedicated Server to 2.1.2
* Updated CP Entropy
    * Version updated to b5
    * Slightly improved nav mesh, bots should work flawlessly than before
    * Mid
        * Z is changed to be far more spacious.
        * The geometry by tetris is much "cleaner"
        * Scouts cant double jump to dropdown from mid
        * Sniper cant reach dropdown from choke
        * The midpoint is lower and easier to jump up on
    * Second
        * The tower looks different
        * Side entrance to lower lobby is now a broken wall
        * Stairs to point are 50% wider
        * Point is bigger
        * Sighline from flank is slightly more covered up (not fully)
        * Wax + grass is paved
        * The truck is a crate removing the hidingspots and making rotating between the two choke doors easier
    * Last
        * Point caps slightly slower (3.9 sec 1x)
    * General
        * Blu is bluer
        * New textures and props
        * Push brushes replaced
        * Removed tons of maps that are not on the Steam Workshop, poor map quality, lack of popularity
    * [Changelog from TF2Maps page](https://tf2maps.net/downloads/entropy.15499/updates#resource-update-43876)
* Updated CP Mannbase
    * Version updated to rc2b
    * Improved nav mesh, bots should work flawlessly than before
    * Gameplay
        * Opened up choke to allow for more creative jumps.
        * Fixed one sided hp/ammo packs.
        * A few new spots around the map to allow for some interesting opportunities. Most notably the new platform in lobby to help hero shot into last.
    * Detailing
        * Yuh there is.
        * New 2d skybox for those that turn off the 3d skybox.
* Updated CP Mist
    * Slightly improved nav mesh, bots should work flawlessly than before
* Updated CP Sultry
    * Version updated to b8a
    * Slightly improved nav mesh, bots should work flawlessly than before
* TFBots now have 12 players in total (was 10)
* TFBots now have 20% chance to taunt on player kill
* Increased maximum player count to 32 (Highly experimental, will revert this change if issue arises)
* Reduced respawn wave time to 3 (was 5)
* Reduced speed increasement from 25% to 20%
* Re-enabled the spectating feature
* Cleaned up tons of community maps not meeting the criteria
> As part of improving our map rotations quality, we had no choice but to remove tons of community maps that have poor map quality, and not on Steam Workshop, and lack of popularity. The following criterias are required to be met to be added into rotation: Must have maps featured on Steam Workshop, have average map quality, and have more popularity.
* Removed Special Delivery, Domination, Territorial Control, Territorial Domination from map list
> We made decision to shift focus on 5 Core game modes: Attack & Defend, Capture the Flag, Control Point, King of the Hill, Payload. Because of that these following maps has been removed to focus more on these game modes. Some of popular alternative gamemodes like Medieval Mode, Payload Race, VIP Mode will remain. We plan to bring back domination if there is more maps that have two-team maps.
* Fixed which Arctic/Warmtic map was placed on Official Map category, it should now be placed on Community Maps
* Greatly reduced server size thanks to `wget` and `unzip`
