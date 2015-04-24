 ▄████▄   ▄▄▄      ▓█████▄  ▄▄▄    ██▒   █▓▓█████  ██▀███      ██▓███   ▄▄▄       ██▀███  ▄▄▄█████▓▓██   ██▓
▒██▀ ▀█  ▒████▄    ▒██▀ ██▌▒████▄ ▓██░   █▒▓█   ▀ ▓██ ▒ ██▒   ▓██░  ██▒▒████▄    ▓██ ▒ ██▒▓  ██▒ ▓▒ ▒██  ██▒
▒▓█    ▄ ▒██  ▀█▄  ░██   █▌▒██  ▀█▄▓██  █▒░▒███   ▓██ ░▄█ ▒   ▓██░ ██▓▒▒██  ▀█▄  ▓██ ░▄█ ▒▒ ▓██░ ▒░  ▒██ ██░
▒▓▓▄ ▄██▒░██▄▄▄▄██ ░▓█▄   ▌░██▄▄▄▄██▒██ █░░▒▓█  ▄ ▒██▀▀█▄     ▒██▄█▓▒ ▒░██▄▄▄▄██ ▒██▀▀█▄  ░ ▓██▓ ░   ░ ▐██▓░
▒ ▓███▀ ░ ▓█   ▓██▒░▒████▓  ▓█   ▓██▒▒▀█░  ░▒████▒░██▓ ▒██▒   ▒██▒ ░  ░ ▓█   ▓██▒░██▓ ▒██▒  ▒██▒ ░   ░ ██▒▓░
░ ░▒ ▒  ░ ▒▒   ▓▒█░ ▒▒▓  ▒  ▒▒   ▓▒█░░ ▐░  ░░ ▒░ ░░ ▒▓ ░▒▓░   ▒▓▒░ ░  ░ ▒▒   ▓▒█░░ ▒▓ ░▒▓░  ▒ ░░      ██▒▒▒ 
  ░  ▒     ▒   ▒▒ ░ ░ ▒  ▒   ▒   ▒▒ ░░ ░░   ░ ░  ░  ░▒ ░ ▒░   ░▒ ░       ▒   ▒▒ ░  ░▒ ░ ▒░    ░     ▓██ ░▒░ 
░          ░   ▒    ░ ░  ░   ░   ▒     ░░     ░     ░░   ░    ░░         ░   ▒     ░░   ░   ░       ▒ ▒ ░░  
░ ░            ░  ░   ░          ░  ░   ░     ░  ░   ░                       ░  ░   ░               ░ ░     
░                   ░                  ░                                                            ░ ░     
Cadaver Party: Episode 1 - localization files guide

// ==================
// How to edit .lang files:

The .lang files use in fact xml language so it's easy to edit them. Here is an example of what you can change inside:
<Entry Name="SpecialEvent">Wow, a special event for me tonight!</Entry>
The only thing you have to edit is the text between the Entry tags, which here is: "Wow, a special event for me tonight!".

Don't edit anything else, like the category names (Inventory, LoadingText, Dead, Messages, Journal, Signs, Ending, etc.).
Don't touch the [br] tags, they are used as line breaks.
Leave the <!-- commentaries --> in files plus keep the formatting intact and this should be perfect.

// ==================
// Installation and in-game testing:

To begin with, download a .zip archive of this repository, open your \Cadaver_Party_Ep_1\ game folder then browse to \config\.

The base translation files go here, they contain general texts like menus, options, UI...
These files are base_english.lang, base_french.lang, etc.

The game translations containing dialogues, inventory texts and so on must be copied into the \lang\ folder inside \config\.
These files are english.lang, french.lang, etc.

Thanks for your participation!
-Yanka S.

Twitter: @Yanka_Prod
URL: http://www.moddb.com/mods/cadaver-party/
