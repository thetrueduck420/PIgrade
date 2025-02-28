this is in no way affiliated with the "pigrade-pro" repo thingy
i dont even know what pigrade pro is
no offense of course, it seems pretty cool

developement started in 25.02.2025

it can only display information using screens if:
 you have an OLED screen thats compatible, or
 you can use your phone as a screen

but its recommended to just use the serial monitor provided by the Arduino IDE

this is a repository about bringing more functionallity to the Raspberry PI Pico

how will i do that??
SIMPLE
I WILL REPROGRAM ALL OF LINUX
well, not ALL of it, but rather program a small shell and a very small kernel to create a fake linux enviroment

although this is mainly focused on linux, i will also remake MS-DOS
why?
cause i LOVE ms-dos, and its very easy to make for a raspberry pi pico

this project will also work on arduino

this will have its own filesystem, if you have no sd card, not to worry, BetterFS lite (which comes in the no-sd version) stores files inside ram, but be aware, this isnt persistent storage, it dies off after a reboot

this isnt THAT optimized, but im one teenager,i need to make a BASIC interpreter, 2 filesystems (betterfs,and betterfs lite), my own assembly language, an assembler, and a way to compile basic cause its fun

i guess i didnt mention im making that stuff, but yea, im working on it

i promise its still gonna be good

and if no one uses it, at least i can, which is enough for me i guess

its pretty much meant for putting linux on small things or using as a CPU that comes with linux
for example, i plan to gut a broken phone, replace the screen and replace its insides with the pico

also, i didnt mention this, but the second stage bootloader that comes after the built in one, can dualboot other operating systems

all you need to do, is make a function that you store your os in, put its name in the BOOT_OS variable
but you will also need to put its name in the pointers, but its easy, the code has a lot of comments that explain everything

i might also work on real time task processing, but i dont know

so, sit tight, and lets make an operating system!
on a side note, my stomach hurts
it doesnt matter, i just wanted to say it

anyways, this is coming out soon enough
im getting very close to a demo

current status: im remaking the whole OS, along with the second stage bootloader, this is for optimization and ease of use, its not gonna take long