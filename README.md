### How to use this on Windows

1. Install PHP (yes, really)
   1. Download x64 non thread safe zip from here: https://windows.php.net/download/     
   2. Extract zip to `C:\php\`
   3. Extract the contents of this program to the same folder 
   
2. Install and enable `curl` extension in PHP
   1. Open php.ini-production in a text editor
   2. Find ;extension=curl and delete the semicolon
   3. Save as php.ini
   
3. Join https://steamcommunity.com/groups/summersaliens  (needed to represent captures)
4. Grab `token` from https://steamcommunity.com/saliengame/gettoken and put it in `token.txt` (replace all content there)
5. Run the script: `php cheat.php`
   1. open command prompt (Windows key + R, cmd, enter), then type `cd C:\php\`, then see above
