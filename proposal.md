# Seed Plotter

<img src="https://github.com/amyjchen/ch-ch-ch-chia/blob/master/example_plotter.png" width="25%">
<i>Above: example usage of plotter</i>

## Team members
Amy Chen: handle the plant aspect of the project and work on the G-code for determining plotter movement

Isaiah Smith: design models for and handle 3D printing of the seed plotter accessories

Jennifer Tao: handle converting user input into a planting pattern

## Project Description & Goals
Our idea is to extend the T-bot and create an attachment for plotting seeds in soil. This mechanism could also be used for doing things like pouring sand in specific designs or putting sprinkles on a large cake. It would work similar to how drop spreaders work. Much of the work involved in this project would be in creating and optimizing this seed-dropping mechanism works such that moderate the concentration of seeds at any area as well as stop the flow. 

We wanted to make use of materials and techniques learned in class and were interested in artistic applications of them. Partly inspired by the Telegarden —  an art project that ran from 1995 to 2004 in which online viewers could cultivate a garden using the internet —  we decided on making a seed plotter for geometric gardening. 

This extension of the T-bot is a fairly unique one. Other machines and processes that would be capable of producing similar seed/grass based designs rely on stencils for accuracy or extrude a paste of both soil and seed. Our plotter is also unique in that it accepts a certain amount of inexactness inherent from its plotting material. While we will be able to precisely and reproducibly plot paths for seed distribution, no two designs will ever be the same as the growth of each blade of grass will always be different.

One of the more difficult aspects of this project will be the milestones related to the seed dispensing mechanism, namely designing/fabricating the attachment and controlling the rate of the dispenser via G-code. Another potential challenge lies in the difficulty of troubleshooting with organic matter; it takes at least 7 days for chia seeds to germinate, and thus we won't be able to determine the accuracy of the plotter/seed dispenser immediately, as would be possible with the T-bot or a laser cutter.

## Plans & Milestones
0. Experiment with planting constraints of chia, i.e. germination, planting depth, watering...
1. Design a preliminary seed dispenser
2. Design plotter mounts/accesories for red wagon
3. Make decisions about seed density as it relates to graphic symbolism, i.e. shading, line weight, etc...
4. Tie seed distribution to plotter path in G-code or Arduino firmware
5. Create a design to be plotted
6. Select/Source/Modify a reliable progam to output vector graphics to G-code paths
7. Fabricate mounts/accesories and assemble plotter on board the red wagon
8. Plot/Plant our design
9. Wait for chia to sprout!

## Parts & Supplies Needed
To bring this idea to fruition, we’ll need a similar set of components as the XY plotter project. These will include v-slot extrusion, stepper motors, an arduino, a cnc shield, driver chips, jumpers, belts, bearings, and fasteners. Beyond the T-bot parts, we'll be using a classic red wagon as our planting bed, soil and fertilizer, and chia seeds because of their quick germination period. We'll also be building our seed dispenser from a combination of 3D printed and off the shelf parts, as well as a servo or stepper motor to control our seed drop rate.

## References & Attributions
As noted earlier, we are not the first to make plant-based maker tools. Telegarden (mentioned prior) was an art project using technology to grow plants. Others have made plotters that use seed and mud mixtures to print (https://makezine.com/2014/01/23/mud-seed-become-3d-printed-grass-art/), as well as made larger-scale versions similar to what we intend to build (http://www.nilskreter.com/ShotCode-Seed-Printer). 
