# Project Timeline 
this file is going to be all text pictures will be in the two file

## Day 1  
early sketch of my keyboard added
9 hours later, free again
i made the schematics for my keyboard thou it's still missing two functions  
(editing matthew here) don't add one cap for each led it's overkill

<img src="https://github.com/Mattiplex/RAINBOW-DASH-Keyboard-/blob/9811351db7481c3b1548433b4f07e169f08a4c62/early%20sketch%20of%20my%20keyboard.jpg" width="200" height="300" > <img src="https://github.com/Mattiplex/RAINBOW-DASH-Keyboard-/blob/e17458b3d952d75ce4bb5f7b2738ad60cd80e742/Screenshot%202026-08-28%20003423.png" width="420" height="420">

## Day 2  
finished wiring up my schematics , added a mcp23008 extension chip, rotary encoder and OLED Display  

<img src="https://github.com/Mattiplex/RAINBOW-DASH-Keyboard-/blob/e17458b3d952d75ce4bb5f7b2738ad60cd80e742/Screenshot%202026-08-29%20013725.png" width="420" height="420"> <img src="https://github.com/Mattiplex/RAINBOW-DASH-Keyboard-/blob/e17458b3d952d75ce4bb5f7b2738ad60cd80e742/Screenshot%202026-08-29%20193702.png" height="420" width="420">

## Day 3
run the electric test , found some problems , got feedback on led wiring , fix it while waiting for more feedback on #keeb 

<img src="https://github.com/Mattiplex/RAINBOW-DASH-Keyboard-/blob/e17458b3d952d75ce4bb5f7b2738ad60cd80e742/Screenshot%202026-08-29%20unsure%20led%20circuit.png" height="420" width="420" >   

## Day 4     
didn't do anything today, i was working on another project   

## day 5  
finish solving the led problem and schematics, research abt footprints, will assign them tmr  
 <img src="https://github.com/Mattiplex/RAINBOW-DASH-Keyboard-/blob/e17458b3d952d75ce4bb5f7b2738ad60cd80e742/Screenshot%202026-09-01%20004836.png" height="420" width="420" >
## day 6  
finished assigning the footprint , now welcome to wiring hell , also i'll be gone for two days so day 7 & 8 won't be any update    
<img src="https://github.com/Mattiplex/RAINBOW-DASH-Keyboard-/blob/e17458b3d952d75ce4bb5f7b2738ad60cd80e742/welcome%20to%20wiring%20hell.png" height="420" width="420" >  

# now from this point on i made lots of stupid mistake and time consuming that would have not happen if i do more research before hand 

# day9&10  
change my switch to kalih HS switch , started the layout for my keyboard , wondering how to add usb c power to my pcb  
(editing matthew here) yeah so i didn't know kle placer exist at this point so i manually align all my keys which is very time consuming and not consistent at all   

<img src="https://github.com/Mattiplex/RAINBOW-DASH-Keyboard-/blob/e17458b3d952d75ce4bb5f7b2738ad60cd80e742/Screenshot%202026-09-06%20021131.png" height="420" width="600">  

# day11  
i opted to switch to clone pico that have usb C , i'm also finished with the layout of the switches but i still got some question so imma wait for some feedback from #keeb (ouff turns out my capacitors are wrong , i switched to ceramic ones) and i also you're suppose to flip the HS Socket and the Led   

<img src="https://github.com/Mattiplex/RAINBOW-DASH-Keyboard-/blob/ead4a26a6a4bc74087bea5c91484bb2e52153a54/Screenshot%202026-09-06%20193636.png" height="420" width="420">   

# day 12    

did nothing particular today   

# day 13    

routed the first row of the keyboard , will continue tmr.   
<img src="https://github.com/Mattiplex/RAINBOW-DASH-Keyboard-/blob/ead4a26a6a4bc74087bea5c91484bb2e52153a54/Screenshot%202026-09-09%20010851.png" height="420" width="420" > 

# day 14 15 16 17   

ok so i didn't do much these four days because i was soldering my blinker which didn't work :(  
# day 18   

ok so big update so i deleted all my trace that i wire on day 13 bcs it's too messy and the 5v trace is too thin. i also change my
diode to smd components. i also placed more components down and i decide to switch the diodes position to the side of the switch instead of on top.   
<img src="https://github.com/Mattiplex/RAINBOW-DASH-Keyboard-/blob/ead4a26a6a4bc74087bea5c91484bb2e52153a54/Screenshot%202026-09-13%20235950.png" height="420" width="420" >
# day 19  
alright so i work on the led placement and holy hell i made a mistake   
(editing matthew here) so i think the mistake i made here was not flipping the switch and led so i have to delete the trace that i made , also check out this absolute ridiculous capacitor.  
<img src="https://github.com/Mattiplex/RAINBOW-DASH-Keyboard-/blob/a1cfaf54834bf63aefc0b2363b2067371121c933/photo%20folder%20unlabel/Screenshot%202026-09-06%20191534.png" height="420" width="420" > <img src="https://github.com/Mattiplex/RAINBOW-DASH-Keyboard-/blob/a1cfaf54834bf63aefc0b2363b2067371121c933/photo%20folder%20unlabel/Screenshot%202026-09-06%20192130.png" height="420" width="420" >   

# day 20  
contemplating my design choice   
(editing matthew here) so i thought i show u guys how i been arranging my HS socket , im basically eyeballing it with a refrence image   

<img src="https://github.com/Mattiplex/RAINBOW-DASH-Keyboard-/blob/a1cfaf54834bf63aefc0b2363b2067371121c933/photo%20folder%20unlabel/Screenshot%202026-09-17%20011624.png" height="420" width="420" >   

# from this point on is where i did a lot redesigning and i also did a theme change , what theme ? well it's in the name 

# day 21   
ok after watching a few tutorial , i refined the schematics of my key switch matrix and switch out the mcp23008 extension chip with mcp22017 chip and as for the pcb it itself it's back to square one.   

<img src="https://github.com/Mattiplex/RAINBOW-DASH-Keyboard-/blob/a1cfaf54834bf63aefc0b2363b2067371121c933/pictures%20in%20descending%20order%20%3D%20date/1.%20refined%20design%20of%20matrix.png" height="520" width="520" > <img src="https://github.com/Mattiplex/RAINBOW-DASH-Keyboard-/blob/a1cfaf54834bf63aefc0b2363b2067371121c933/pictures%20in%20descending%20order%20%3D%20date/2.%20PCB%20back%20to%20square%20one.png" height="420" width="420" >  

# day 22  
ok so today i log a small section like 35min , so i learn how to use a placer to help me place my keyswitch to my KLE layout that i want , i also have some issue with the layout as the keyswitch number don't match when i do geographical reannotation  

<img src="https://github.com/Mattiplex/RAINBOW-DASH-Keyboard-/blob/a1cfaf54834bf63aefc0b2363b2067371121c933/pictures%20in%20descending%20order%20%3D%20date/3.%20it%20look%20so%20much%20better.png" height="420" width="420" > <img src="https://github.com/Mattiplex/RAINBOW-DASH-Keyboard-/blob/a1cfaf54834bf63aefc0b2363b2067371121c933/pictures%20in%20descending%20order%20%3D%20date/4.%20weird%20layout%20error.png" height="420" width="420" >  

# day 23    

today i work on more of my layout and finished placing all the components for my layout , but when i run DRC there seem to some issue with LED board edge clearance so i ask on #keeb and haven't started to route my pcb yet  

<img src="https://github.com/Mattiplex/RAINBOW-DASH-Keyboard-/blob/a1cfaf54834bf63aefc0b2363b2067371121c933/pictures%20in%20descending%20order%20%3D%20date/5.%20weird%20drc%20error.png" height="420" width="420" > <img src="https://github.com/Mattiplex/RAINBOW-DASH-Keyboard-/blob/a1cfaf54834bf63aefc0b2363b2067371121c933/pictures%20in%20descending%20order%20%3D%20date/6.%20finished%20placing%20components.png" height="420" width="420" >  

# day 24    

ok so today i solve the clearance issue and route the pcb thou im only like 45% done    
<img src="https://github.com/Mattiplex/RAINBOW-DASH-Keyboard-/blob/a1cfaf54834bf63aefc0b2363b2067371121c933/pictures%20in%20descending%20order%20%3D%20date/7.halfway%20there.png" height="420" width="420" >   

# day 25    

ok so today i finish most of the wiring just the led that is still unroute   
<img src="https://github.com/Mattiplex/RAINBOW-DASH-Keyboard-/blob/a1cfaf54834bf63aefc0b2363b2067371121c933/pictures%20in%20descending%20order%20%3D%20date/10.%20led%20route%20ongoing%2C%20fix%20some%20issue.png" height="420" width="420">   

# day 26
did nothing, fr really tired that day    

# day 27  
so today i routed the led (ongoing) and i fix some issue col7 unrouted and added two capacitor for both the OLED screen and the Mcp23017 controller  
<img src="https://github.com/Mattiplex/RAINBOW-DASH-Keyboard-/blob/a1cfaf54834bf63aefc0b2363b2067371121c933/pictures%20in%20descending%20order%20%3D%20date/9.add%20two%20new%20cap.png" height="420" width="420" >   

# day28  

today i added a ground plane to my pcb and finish routing the led and buddy there's tons of issue with gnd between the led ps: i totally forgot abt journaling yesterday so there won't be any picture today    

# day29   

so today i did lots of work i fix the ground issue and now im working to place the capacitor at the ideal position so we're at the very last stage of pcb designing , and oh the deadline is approaching fast. i wonder if i'll finish in time .  <img src="https://github.com/Mattiplex/RAINBOW-DASH-Keyboard-/blob/a1cfaf54834bf63aefc0b2363b2067371121c933/pictures%20in%20descending%20order%20%3D%20date/9.%2098%25%20done.png" height="420" width="420">   

# day 30    

alright today i got my finish routing my PCB and ran into issue with the capacitor , but other than i decided to do a major theme change to go more inline with the theme of my setup. i fix the capacitor issue and now placing the 3d key switch model manually one at a time   
<img src="https://github.com/Mattiplex/RAINBOW-DASH-Keyboard-/blob/a1cfaf54834bf63aefc0b2363b2067371121c933/pictures%20in%20descending%20order%20%3D%20date/11.%20well%20no%20(blood)%20but%20mostly%20sweat%20and%20tears.png" height="420" width="420">  

# day 31     

today i finished my pcb and place all the 3d models , started on the case but there's an issue with fusion stp file import, but i found a workaround so no biggie thou there's not much time left.    
<img src="https://github.com/Mattiplex/RAINBOW-DASH-Keyboard-/blob/a1cfaf54834bf63aefc0b2363b2067371121c933/pictures%20in%20descending%20order%20%3D%20date/12.%20finished%20PCB.png" height="420" width="420" > <img src="https://github.com/Mattiplex/RAINBOW-DASH-Keyboard-/blob/a1cfaf54834bf63aefc0b2363b2067371121c933/pictures%20in%20descending%20order%20%3D%20date/13.3d%20model.png" height="420" width="420" >  


# day 32     
this is the last day before the deadline, so i pushed hard and hit a new record for time spend in front of a computer almost 6 hours and half of the time is just me failing and trying again
. i made the bottom case and the plate and boy do i fail a lot, it's so hard to judge the distance and sometimes i even get the range wrong and i have to redo everything, there's also random miniusclue gaps that will left out when i extrude and it's always so frustating to fix it  
anyway i think i have some pictures of the progress i made but idk.  

# day 33   
alright so today i decided to switch to the stardance challenge and ship my keyboard there.  

 # Devblog 1 
 so today i went back to the pcb and added more graphics cause why not , i got more time now   
 (editing matthew here) every blog from now  on will follow this format.    

 # Devblog 2   
 so what i did today, i continue working on my keyboard cad files today, boy o boy is tiring , i have to manually place and align each keycap and it took a while bcs im such a perfectionist. anyway i decided to use a top mount layout for my keyboard so there will three layer a bottom case , the plate and the upper case. im so impatient , i want to finish this quickly !!!  

# Devblog 3   
so this few days i just been doing CAD , the plate finish , i got the top case rough shape finish and i almost finish the bottom case just the usb-c port left. i went through three different design variations and eventually settle down for the design for the bottom case (in picture). i also model my own custom rotary encoder knob. i want to import a knurl design at first but then the model i import was too large and when i scale it down it won’t fit. either way we’re getting close to finishing the design phase.  

# Devblog 4   
this is it im done with my case

this is it we’re done with the designing phase ,
things i did:

   -changed the 3d model of the pi pico with a usb c
   -cut out the upper case heatset insert hole
   -cut out space for the screw head sticking out at the plate
   -cut out the usb-c charger hole
   -rounded the case edges
   -oooo idk if u notice but there’s a big hole on top of pico
   -and that’s there on purpose so i can add a clear acrylic plate there.
   -oh yeah and the text there also have space below to insert some light dispersing material.


