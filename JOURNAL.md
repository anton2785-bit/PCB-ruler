---
title: "PCB ruler"
author: "antondimitrov2785"
description: "A ruler that has most of the footprints that I frequently use"
created_at: "2026-09-01"
---

# 2026-09-10: Github

**Total time spent: 2.5 hours**

I had to reinstall gitbash (which took a bit of time) and configure it. 
After that I had to upload everything to github and write a README.md. That took a bit of time because I havent done tha in a while but I did it. ![image.png](https://cdn.hackclub.com/01a08d0b-1764-75f4-86cb-8549c099421e/image.png)

# 2026-09-10: Some refinng

**Total time spent: 0.5 hours**

I had moved I think the vias and some other components to look better. I also had to change some of the fooprints not to have holes in them and all of the trough hole pins to SMD because I dont want random holes everywere.
And here is the finished ruler:
 ![Screenshot_2026-09-10_133106.png](https://cdn.hackclub.com/01a08cbb-3b29-72a2-97f4-24b90bb84829/Screenshot_2026-09-10_133106.png)
![Screenshot_2026-09-10_133231.png](https://cdn.hackclub.com/01a08cbb-3db0-799d-870b-6119f757e81a/Screenshot_2026-09-10_133231.png)
![Screenshot_2026-09-10_133249.png](https://cdn.hackclub.com/01a08cbb-4c20-7e83-a033-91b9631c9180/Screenshot_2026-09-10_133249.png)

# 2026-09-10: Finishing the second layer

**Total time spent: 1 hour**

After the ESP32 that I added the entry before I placed 4 footprints of LED lights (some RGB some not). After that I placed some trough hole components like a buzzer, a TH diode and resistor and some capacitors (electrolitic). Below them are 3 sizes crystal which are not that used but are good to have.
The final thing I added is a 2.54mm headers (20pins long). I used them as a scale for the normal ESP32 devboard and a micro EPS32 because I didnt have the horizontal space for both of them and also the ESP32 devboard (not the micro one) is a bit wider than the ruler. ![Screenshot_2026-09-10_133004.png](https://cdn.hackclub.com/01a08cb9-3b83-786d-8766-4a41e4717655/Screenshot_2026-09-10_133004.png)

# 2026-09-10: More footprints

**Total time spent: 1 hour**

Now for thew buttosn I added a simple 4 pin button footprint that is mostly used on breadboards, an ON/Off switch, a rotary encoder and a MX style (keyboard) switch. I aldso added a XIAO style footprint, bvecause they are realy small for an ESP32. ![Screenshot_2026-09-10_122900.png](https://cdn.hackclub.com/01a08cb4-e0f0-7619-bd78-f5ebddf86092/Screenshot_2026-09-10_122900.png)

# 2026-09-10: The second layer

**Total time spent: 1 hour**

After I remade the cm scale on the other side (flipped) I wanted to have the most used USBs (A,C and micro for some reason). I had to download an another library just to have the footprints for the male PCBs on the A and C because I wanted them to be on the board (I wanted to have fooptrints that can be directly pluged into a port without souldering anything). ![Screenshot_2026-09-10_121130.png](https://cdn.hackclub.com/01a08b35-3e4d-7dd4-a67a-6540b8c7f237/Screenshot_2026-09-10_121130.png)

# 2026-09-10: Finishing the first layer

**Total time spent: 1.5 hours**

I had to think a bit before finishing this layer. I didnt have ideas on what other to place (other than some holes and vias) and then I saw a MPU-6050 laying on my desk and remembered that other chips like the rp2040 and the MPU have a shared "family"of footprints that is called QFN. I added one that was smaller than the MPU and one larger than the RP2040 although I dont now when or where they are used. 
![Screenshot_2026-09-10_030440.png](https://cdn.hackclub.com/01a08b30-61f6-7355-9ccf-f354031578f4/Screenshot_2026-09-10_030440.png)

# 2026-09-10: Adding more footprints 

**Total time spent: 2 hours**

Most of the time went by looking for footprints that are used in a big number of PCBs. After that I added 5 transistor sizes (from sot 23 to TO 220) and some more IC packages. I would have added 2 more IC packages, but they were pretty similar to the SOP-8 and SOP-16 (the SOIC 8 and 16).
Also on the far left I had to test almost every layer in KiCAD to see what is visible when I take it to JLCPCB for production. 
The cm and inch scales had to be done manualy because KiCAD doesnt have footprints for them, but it wasnt too hard (mostly duplicating the lines I drew by hand)
![Screenshot_2026-09-02_154427.png](https://cdn.hackclub.com/01a08b25-c2f6-77c7-a7e1-0a7fcc2367aa/Screenshot_2026-09-02_154427.png)

# 2026-09-01: Starting out

**Total time spent: 1.5 hours**

I made the outline of the ruler. I will use a 210 by 25.4 mm size (200 mm long ruller). After that I started to add some of the most important footprints: The SMD Metric sizes and some diode sizes. ![Screenshot_2026-09-02_000739.png](https://cdn.hackclub.com/01a05ef4-e847-7b09-b5fa-c3dbe8c5f4dc/Screenshot_2026-09-02_000739.png)

![Screenshot_2026-09-02_004713.png](https://cdn.hackclub.com/01a05ef4-f771-7a14-b675-236e349a0ce3/Screenshot_2026-09-02_004713.png)

