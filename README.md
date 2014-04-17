download minecraft
set profile to run 1.6.4
open the start.command and make sure it's set up to run the right folder.
open ops.txt and add in your minecraft name. this gives you access to run commands in game. 
run the start.command 
open minecraft
multi player
new -> localhost:25555 or where you are running the bukkit server

in game press '/'
/js castle()
/js ranibow()

plugins -> scriptcraft -> plugins -> make a folder (see emily)
have a play. 

reload the js files
/js refresh() 

/js emily()

--------------

http://arghbox.files.wordpress.com/2013/06/minecraftbook.pdf

--------------
for python. 
<code>
create a file something like:
# Sample program to create a pillar
import mcpi.minecraft as minecraft
import mcpi.block as block
# Connect to the Minecraft server
world = minecraft.Minecraft.create()
# Get the player's current position and store the coordinates
[x,y,z] = world.player.getPos()
# Set some variables to customize your pillar
height = 3
material = block.BRICK_BLOCK
# Build the pillar. It will be "height" blocks high and located one step away from the player.
for level in range(0, height):
 world.setBlock( x+1, y+level, z+1, material )
 level = level + 1;
</code>
Then run it in terminal. 
go back to the game, and see the result. 

