---
title: "RC Car Build"
author: "stolen_username"
description: "Remote Controlled Car with an Arduino Nano and an nRF module."
created_at: "2026-09-11"
---

# 2026-09-12: added build pics in github repo

**Total time spent: 5 minutes**

# what did i do?
- added build images
- added build video


![Screenshot_2026-09-12_at_1.59.17_PM.png](https://cdn.hackclub.com/01a094bc-439d-7fef-89a0-c7aa41581cd6/Screenshot_2026-09-12_at_1.59.17_PM.png)

# 2026-09-12: uploaded the firmware in both and tested the car

**Total time spent: 10 minutes**

# what did i do?
- uploaded the firmware using arduino ide in both arduinos
- holy shit it works

video link: https://cdn.hackclub.com/01a094ab-44b6-7a4d-9bb2-7d6f78714119/video_clip_2026-08-30_16-27-05-290.mp4

![IMG-20260826-WA0008.jpeg](https://cdn.hackclub.com/01a094ab-c652-708c-a25a-4106445da732/IMG-20260826-WA0008.jpeg)

# 2026-09-12: made the entire receiver

**Total time spent: 2 hours**

# what did i do?
- soldered in the nrf24l01 module
- soldered in the arduino nano headers
![IMG_20260823_002606.jpg](https://cdn.hackclub.com/01a09497-e51c-70a8-860b-b6520db0027d/IMG_20260823_002606.jpg)

- also i messed up using a 9v battery and it wasn't working (instead of 18650 batteries i had planned in the circuit)
- i later purchased 2 18650 batteries from a local vendor and used that instead of the 9v battery
![IMG_20260823_170151.jpg](https://cdn.hackclub.com/01a094a4-3fc7-7434-a8b1-5c1f589da1a7/IMG_20260823_170151.jpg)
![IMG-20260826-WA0008.jpeg](https://cdn.hackclub.com/01a09498-a83e-7138-983d-b85fd6b89dcf/IMG-20260826-WA0008.jpeg)
![IMG-20260826-WA0006.jpeg](https://cdn.hackclub.com/01a09498-9d2c-7ca1-bbde-b70288de99e0/IMG-20260826-WA0006.jpeg)

# 2026-09-12: catastrophe - polarized capacitor was soldered in wrong

**Total time spent: 30 minutes**

# what happened
- turns out when i was testing the transmitter, i found it wasn't working
- while debugging, i found that the capcitor (100uF) was soldered in wrong
![IMG-20260819-WA0019.jpeg](https://cdn.hackclub.com/01a0947f-85a1-717d-9bf2-0b6c0a75bc53/IMG-20260819-WA0019.jpeg)

# what did i do??
- picked up some desolder wik
![IMG-20260819-WA0021.jpeg](https://cdn.hackclub.com/01a0947f-6422-74ea-85ae-e2391341091a/IMG-20260819-WA0021.jpeg)
- inhaled some flux fumes
- and tried to desolder the shit out that capacitor
- it didn't work so i put on some more flux and it still didn't work
- then i used the help of some tweezers, heated the solder pads, and plucked out the capacitors

![IMG_20260819_155745800.jpg](https://cdn.hackclub.com/01a0947e-e3f8-79b8-b10b-d7ef3afeb713/IMG_20260819_155745800.jpg)
![IMG-20260819-WA0006.jpeg](https://cdn.hackclub.com/01a0947f-1cc4-78a9-bebf-9d1a98636870/IMG-20260819-WA0006.jpeg)

after a whole lot of time wasting, it finally worked
![IMG-20260819-WA0014.jpeg](https://cdn.hackclub.com/01a0947f-d17d-7f77-9ed6-01aaafe789ae/IMG-20260819-WA0014.jpeg)

# 2026-09-12: got my case printed and shipped

**Total time spent: 1 minute**

# what did i do?
- got my case 3d printed by @Anay
- really loved the black colour matching with the pcb's colour

![IMG-20260816-WA0020.jpg](https://cdn.hackclub.com/01a09476-be2d-7803-8a8f-81c530a01a00/IMG-20260816-WA0020.jpg)
![IMG-20260817-WA0002.jpg](https://cdn.hackclub.com/01a09476-bf22-72b0-ad32-02dfa885c99a/IMG-20260817-WA0002.jpg)

# 2026-09-12: soldered the nano header pins on the transmitter

**Total time spent: 15 minutes**

# what did i do?
- soldered in the arduino nano header pins in the transmitter's pcb
- i am now pretty confident while using a soldering iron, i can make not clean joints, but ones which actually work

![IMG_20260819_133330033.jpg](https://cdn.hackclub.com/01a09475-1b2c-7f8f-be2f-28bb18cbc010/IMG_20260819_133330033.jpg)

# 2026-09-12: soldered the keys and nrf24l01 on the transmitter

**Total time spent: 45 minutes**

# what did i do?
- soldered the 4 switches
- soldered the nrf24l01 module
- put on some keycaps on the switches
- soldered the capacitors (foreshadowing, i might have soldered the polarized capacitor wrongly)

![IMG-20260818-WA0013.jpeg](https://cdn.hackclub.com/01a09451-7c43-7a56-8ae9-7427fadaa488/IMG-20260818-WA0013.jpeg)
(look at those joints 😍)
![IMG_20260818_193840748.jpg](https://cdn.hackclub.com/01a09451-8fe6-7158-a9fd-42365f21cb10/IMG_20260818_193840748.jpg)


# 2026-09-12: pcb arrived

**Total time spent: 1 minute**

# what happened?
- pcb arrived
- had to pay ₹1500 (US$15) for customs out of my pocket
- really liked the silkscreen i had made yaya

![IMG_20260818_170055.jpg](https://cdn.hackclub.com/01a0944a-cf68-7086-a902-08d23a2868e3/IMG_20260818_170055.jpg)![IMG_20260818_170938465.jpg](https://cdn.hackclub.com/01a0944a-db5e-7496-945e-bbdfd88cc22a/IMG_20260818_170938465.jpg)![IMG-20260818-WA0001.jpeg](https://cdn.hackclub.com/01a0944a-ff5d-7c96-a3fc-23aa455da933/IMG-20260818-WA0001.jpeg)

# 2026-09-12: Got the parts but a major issue

**Total time spent: 10 minutes**

# what did i do?
- by 12 august i had received all my components
- a major issue, the l298n motor driver came damaged (omg scaryy)
- luckily i returned it and in a day it came, then i checked and it was perfect

![IMG_20260811_150338891.jpg](https://cdn.hackclub.com/01a09446-46b5-74f4-9d7f-03623376574b/IMG_20260811_150338891.jpg)
![IMG_20260811_150357509.jpg](https://cdn.hackclub.com/01a09446-4718-71aa-abca-6966ceef5a20/IMG_20260811_150357509.jpg)
![IMG_20260811_150404410.jpg](https://cdn.hackclub.com/01a09446-47d5-783b-b80e-9261c302f722/IMG_20260811_150404410.jpg)

# 2026-09-11: Ordered the Parts

**Total time spent: 10 minutes**

# what did i do?
- got the grant
- ordered the parts
- waited

![Screenshot_2026-09-12_at_2.34.55_AM.png](https://cdn.hackclub.com/01a09249-b548-7c96-9517-e7da76551649/Screenshot_2026-09-12_at_2.34.55_AM.png)

