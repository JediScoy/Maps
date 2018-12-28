STANDARD SETUP

Step 1 - go to this file address 
C:\Users\User\AppData\Roaming\Wonderdraft\assets\

Step 2- create a new folder named whatever you want it to be named.
C:\Users\User\AppData\Roaming\Wonderdraft\assets\myassets\

3. Create the folders the same way as the initial folder is

C:\Users\User\AppData\Roaming\Wonderdraft\assets\myassets\sprites\symbols\symbols

Each folder inside of the “sprites” folder will be named according to the section it belongs in

\sprites\mountains\mountains

\sprites\trees\trees

When creating a new “mountain” you will need to place the png files in different folders. Every file placed into one folder will be shuffled between when placing.  If you want to only have one mountain asset you will be better off placing it in the symbols folder


ADVANCED

* Running Wonderdraft after you have added your assets creates new meta files called .wonderdraft_symbols. Inside are various options you can modify.

* The radius is the collision or exclusion radius around an asset. The bigger your symbol, typically, the bigger your radius.

* The offset allows you to move a symbol's center of gravity/pivot. Useful for tall symbols or asymmetrical ones. The offset is used to help sort the symbols and determine where the collision radius emanates.

There are 3 different draw modes--normal, sample_color, and custom_colors
- normal draws your symbol as is
- sample_color adapts your symbol to the ground color
- custom_colors uses the RGB channels to colorize your symbol inside Wonderdraft