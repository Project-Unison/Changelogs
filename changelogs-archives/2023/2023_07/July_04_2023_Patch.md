# July 04, 2023 Patch (Public Test Servers ONLY)
This one is kinda maintenence update to prevent weird things happening due to out-of-memory kernel panics. Hoping for server not to break... Unless?

An update for Project Unison **Public Test** servers was released. Changes will automatically apply after a map change. Major changes include:

* Added swap workaround to fix out-of-memory crash to all test servers
* Added [Auto-Restart system](https://github.com/TitanTF/server-refresh) from [Titan.TF Community](https://titan.tf). The system will try to restart server when following criteria are met:
    * It is now 17:00 JST / 00:00 PT / 09:00 AM CEST
    * Servers are empty (Except Sunday scheduled shutdown, the server will restart on Sunday regardless of player count to avoid any server issue)

**Note: This patch only applies to servers marked with `(Public Test)`.**
