# Mario Kart 8 Kart Optimizer
Kart Optimization Program. Will prioritize three stats and choose parts accordingly. 

The user may select first, second, and third priority stats for their vehicle. The algorithm then chooses parts first by whichever one gives the highest bonus to the first priority stat, then if there is a tie it goes by second, and then third in the event of another tie. 
The user must change the parameters of the buildKart function in the code. The function takes three integer parameters that represent the index of the first, second, and third priority stats. 
Stats are sorted as they are in the game, starting at 0:
0 - Speed
1 - Acceleration
2 - Weight
3 - Handling
4 - Traction

Many parts have identical effects on statistics and so are sorted as such:


#############################################################
####VEHICLES###############
##############################################################

[0, 0, 0, 0, 0] - Standard Group
Standard Kart
Cat Cruiser
Prancer
Sneeker
300 SL Roadster
The Duke
Teddy Buggy

[0, .25, -.25, .5, -.5] - W25 Standard Bike
Pipe Frame
W 25 Silver Arrow
Standard Bike
Flame Rider
Varmint
Day Tripper
Wild Wiggler

[0, -.25, .25, -.25, .25] - Tanooki Rattler
Tanooki Kart
Bone Rattler

[.5, -.25, .25, 0, -1] - Group 4
Mach 8
Circuit Special
Sports Coupe
B Dasher
P-Wing

[.25, .25, -.25, 0, -.5] - Blue Falcon
Blue Falcon
Streetle

[.25, 0, 0, .5, -.75] - Master Cycle
Master Cycle

[0, -.5, .5, -.5, .5] - Steel Driver
Steel Driver
Tri-Speeder
Badwagon
Mercedes GLA
Standard ATV

[0, .75, -.25, .75, -1.25] - Sport Bike
Comet
Sport Bike
Jet Bike
Yoshi Bike

[-.75, +1.25, -.5, .5, -.25] - Biddybuggy
Biddybuggy
Landship
Mr. Scooty


#############################################################
####WHEELS###############
##############################################################
[0, 0, 0, 0, 0] - Standard Group
Standard
Off-Road
Blue Standard
Retro Off-Road
GLA Tires

[0, -.5, .5, -.75, .75] - Monster
Monster
Hot Monster

[-.5, 1, -.5, .25, -.25] - Roller
Roller
Button
Azure Roller
Leaf Tires

[.25, -.25, 0, .25, -.5] - Slim
Slim
Crimson Slim
Triforce Tires

[.5, -.25, .25, 0, -1] - Slick
Slick
Cyber Slick

[.25, -.5, .5, 0, -.5] - Metal
Metal

[-.25, .25, -.25, -.25, .5] - Sponge
Sponge
Wood
Cushion

########################################################
###GLIDERS########
#######################################################
[0, 0, 0, 0, 0] - Standard
Super Glider
Wario Wing
Waddle Wing
Plane Glider
Paper Glider

[0, .25, -.25, 0, 0] - Alternative
Cloud Glider
Peach Parasol
Parachute
Parafoil
Flower Glider
Bowser Kite
MKTV Parafoil
Hylian Kite
