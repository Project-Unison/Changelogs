# August 22, 2023 Patch
An update for Project Unison servers was released. Changes will automatically apply after a map change. Major changes include:

* Added `!votescramble` command, replacing existing scramble and restart vote menu
    * You can type `!votescramble` in chat to request votescramble
    * If two or more players type `!votescramble` in chat, the vote menu will appear asking to scramble team after round end
    * If 66% or more players vote 'Yes', the game will scramble the team after the end of the round
* Disabled spectator mode due to team stacking exploits, you can still change your team at any time as long as there is space
* Now inactivity for two minutes will result in immediate kick
* Fixed server restart features not working properly
* Fixed issue where typing `!votekick` would display Vote slay menu
* Fixed issue where typing `!voteslay` would not display the Vote slay menu
* Added 'Abusive Chat Behaviors' category to `!call`, the 30 minutes of chat history will be logged after report
* Disabled auto team scramble as the feature no longer works properly due to bug
