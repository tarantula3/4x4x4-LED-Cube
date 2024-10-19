# 4x4x4 LED Cube


[![f7xFfsGhaso](https://i.imgur.com/d9frfg5.jpeg)](https://www.youtube.com/watch?v=f7xFfsGhaso)

Bring life to your home with this enchanting 4x4x4 LED cube. From static to flashing, chasing, or fading this cube can be programmed to display many different types of 3D LED transitions. This customizable PCB LED cube is super easy to make and fun to have in your home. Go ahead and create a forest of these cubes using various color LEDs to enhance the beauty of your Christmas Tree this Christmas.

This cube has 64 Blue LEDs organized in 4 layers. These LEDs are wired up to an Arduino Nano. Each LED can be addressed individually using Arduino IDE, enabling it to display amazing 3D transitions!

There are hundreds of tutorials of these cubes made using exposed metal wires and by using crazy soldering techniques, which just gives me shivers. In this tutorial I'll show you guys how to make this super simple 4x4x4 PCB LED cube "without overcomplicating anything". With just basic soldering skills, you can create this PCB cube and light up your living room making everyone jealous.


Components Required
-------------------
For this project we need:
64 x Blue Color Round LEDs (plus some extra just in case you make a mistake)
4 x Blue Color Flat LEDs
4 x 100Ohm Resistors
8 x 4GX9 Pan Head Screws
1 x 220v to 5v Step Down Converter 
An AC Power Cord
1 x Arduino Nano
A 3D Printer
Acrylic Colors
Custom Built PCBs
20 x Exposed Thick Copper Wires and 
An x Optional switch

** All the project related resources can be downloaded from my GitHub repository : https://github.com/tarantula3/4x4x4-LED-Cube.


Testing The LEDs
----------------

![image](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEiAZCreMNjfc1GQmeM2mh3ZFX6nBZwKsve85bRWVvIrmVfWo_bVWVRuFWhHi8yFZu7dgIyl0CCTS_cQI1pVatNoiHNAmxeZjbiTSrdrv7rt1Gyr6806Mcxuvl5r98hgS6X1NDbT4wrCDMcaRs74WTN1jr-kF9iEHYg2sN2ka9751B6Ek-pWkywHd9O-VH0/w640-h360/2.png)

Before we start assembling our LED cube, it is a very good idea to test these LEDs.
Since few of the LEDs will remain absolutely inside the cube, so accessing them after the assembly will become an absolute nightmare. Hence a simple mistake can bring a lot of greif.
Using a coin cell, I tested all the 64 main LEDs and the 4 Square LEDs.


The Board
---------

![image](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEj2v9ABBJQQcEGZYWsuWNwPRhZ58gYL_pUW-MuKLXkSVkxtSA4NYIqWKafx661xXUQESYae0bL0cIa0EPu1IeKBjyPvfxbwFhfLEZkGGH2W2JXfu-6GbBByXO8CGRAmF4R1ZLzFz9vm_zY0aXd03Oy-mThU5DUzWIeo9Hd7-yylDkTnOP5pc4HIr-qrGoo/w640-h360/3.png)

So, I designed two types of PCBs for this project.
One for the base and the other one that will be installed 4 times to create the top 4 layers of the cube. Both PCBs have "TOP" and "BOTTOM" witten on them. The "Top" section faces up and the "Bottom" section faces down.

![image](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgyee1QacN18gneZafqCtHhOY6QwOi16ijVLVaj7N9pmAgHxC6Addl-IhIyNHD2J3DbqDi_pSYR7-wnQx01NFjqTCMbzkDezNZZTXMzE76xhxqna1yLPgOBGYyOjCSQ5Okhn05OOUhX1nsOwtNkWwrvdXDwLKWkPMh_0cp4o2ovb-OhPnmwOgvVSOE9ptI/w640-h360/5.png)

While assembling the cube, I will first solder the 16 copper wires to the "Top Section" of the base plate. Then I will solder the remaining 4 wires to the board. Each of these wires will connect to only one layer. Hence, all these wires are of different sizes. The 1st one from right connects to layer 1, next one to layer 2 and so on. Once all the wires are soldered to the "Top Section" of the base plate, I will one by one slide the LED meshes over these wires and solder them accordingly to form the top 4 layers.


Soldering The LED Mesh
----------------------

![image](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEiMcAl0J7Uaxr9AYW6F_9MYTEDVgwvzHTLgfZaWs7m0MFXSrQUTeNwCqIPjpsDac_buIBNwrbgxxlZUZYNA1DL6_UFACqiJsJtbF9C0lyZjNp7ddHyr-xEDOObXjDsiqjjtU-44PK1W1wPKa0aZYtyu33SP3_cYzsm3iSOKyqN61p_FAd5InkIK4dQf4Bo/w640-h360/6.png)

So, this is what came in the mailbag. Thanks to PCBWay, the boards are vell well fabricated and look absolutely amazing. The black color solder mask is adding to the beauty of the boards.
As discussed earlier we need 4 of the "LED Mesh Boards" and 1 board for the "Base".

![image](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEg3zXvwZ5GjlUGtKFy5IeUsd42HbpMbrycQRSoL-vbmNk5BLsYCy9abZiRisDsyiPZCMlLQ8x7h9iNT-cW8l5S_UoeTYqX64jvg3eL9kl4KK18jqHcB38v1pBO0FBCub4DxeP8q5uJZ0NlAGPyIcPyUTsYAJGnFhZTeVMsIIPGHCGWkBz8qfB-FmC11Lj8/w640-h360/8.png)

One by one I added all the LEDs to the board. While soldering the LEDs, please make sure that they are all added to the "Top" side of the board. Once all the LEDs were in, I went ahead and soldered them to the board.


Soldering The Base
------------------

![image](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhw7yPCcCKyyJRHSiQdzl_9LRgQJqrGsrVR93Geirow914tsDIrfpk7UrjWGy9vRgZrTCh_7NgBQF8yBHtBVK-grVnCb72IFJb7LTLIWhz_5QvTUubCksKg0jJWR7ij27toQRFAgmZDI4LFrcHFodF-ZUwPfiDXKZlHXn_-alyP2SY3oIimAp058GV1QVM/w640-h360/11.png)

After sorting out the top layers, it was time for me to set up the bottom bit. 
I started the setup by soldering the 4 x 100ohm resistors to the board. Then, I soldered the Arduino Nano to the board. Instead of soldering the Arduino Nano directly to the board, I used female pin headers to house the Arduino Nano Microcontroller. Please make sure all these components are soldered to the "Bottom" side of the base plate.

![image](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgmDoyB4KsNpzNWTQzLjYaHSNd83FAZUFCm9qff1B048qZdDgLH5FN3N3EMZ3ylbmz25F-f-89RxaSdgvbswFO1mdTPBU0yfTnWHmAphVx3Br-LaxAD6nYkqzm-iJdtxH8K-7n1AOSgHy7tythe1c7BxTROCLLI5YCJ9Zu6_Ygb8iM5a9a37MXnPW96emQ/w640-h360/12.png)

After that, I one by one soldered all the copper wires to the base plate. While soldering the wires, please make sure you solder them to the "Top" side of the board.
After soldering the wires to the base plate, slide the 1st LED Mesh and solder all the wires to it. Then slide the 2nd one and so on. I left a 1.7cm gap between each layer and 1.2cm gap between the 1st layer and the base plate.

![image](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgkl9NFdHuTnJVVzIg0xsEOPlhWipuSwqpbbSkwFUfEDYYPrKwwb4g0wsgek2QREq4YYqolSShEY7btxEeyok2r0IcqqRIT1L1Jgio6ITu5xcbDmACsirdpHGkzLVTM7_owVK4jidDuCd31aQhcHbgl41vy-lLWp6qnte4T7ni9LuQQUO8BTraTtjSOSug/w640-h360/13.png)

In this setup, the 4 wires that we saw earlier that connect to individual layers are soldered to the middle rail. However, in the final version I moved them to the outer rail to make the soldering process easy.


Coding
------

![image](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhw-Vy_uRg_Orfy2vwXNf7rELUMmVTKficumlRg3d4OasVvqJX5b6iCIoG3MrOxo12BAoZR0RRGt2_d2hdrlS469H1FEVyImyswiGtOEGxKaiJ_FSvnMQ5bptHKw1m0_79VqQc8e8Mg6uGKK1Thld_xxHCBMH6fkWHUlILJDqZ5vH9tHPlUuqRpqqFzy6c/w640-h360/14.png)

I found this sketch online, and then I edited it to work with my LED cube.
You can download the code from my GitHub repository (https://github.com/tarantula3/4x4x4-LED-Cube). The code is exactly the same as any other 4x4x4 LED cube code with some additional transitions that I added. I also found that the Arduino Nano freezes after a while. So, to keep the process going without any interruptions, I added a function to reboot the board after it completes one set of transitions. 


3D Model
--------

![image](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjvdRluGvoTku23iYndZzaCe3mcENZAgGINGTssHM7ALqj0Ju2Rc6cHCLpG0YDOPIFfQ_d8UznH6RJdirZm2uBjSA8xylFx1KlaZHDyHG13us5uoy1sduPXwjeyM36I75hcbMxoVh8t3EP4A2EpeNw8aVrw74MIdqCVAycnNcqdP8bgedUHH1t-_9KskLI/w640-h360/15.png)

Using Microsoft 3D Builder I designed the base of the cube.
The onscreen 3D model is actually upside down.
On one of the sides, I left a hole for inserting the powerchord. These groves are for the 4 x Flat Head LEDs.
The lid sits on top of the base and is screwed to the base using 4GX9 Pan Head Screws.


3D Printing
-----------

![image](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjz507msn6fbP1nN7rcJBwMaKmsNHX0F_XltqSeqakGeQ4-1X6bhlcTtrOEkFEzs9f2vkkRJqhMtg7SAtWa5NoGjKjILTWtirNtF8RBPf_AMxmhQv2-9J5dtizuTh7yPphkiXX79inHFrVXfK_6H1Gfw3ZOD2WcQ5znqNJzchaXUK_f9-cFcgMkRLZ9_wE/w640-h360/17.png)

Once the 3D models were sorted, it was time for me to fire up my 3D printing oven and start printing these 3D models.

As we all know, 3D printing is the process that uses computer-aided design or CAD, to create objects layer by layer.
3D printing is not a new technology, its been there since the 1980's, when Charles W. Hull invented the process and created the first 3D-printed part. Since then, the field of 3D printing has grown exponentially and holds countless possibilities. The 3D printing process fascinates me a lot and I sometimes love to sit near my printer and watch these layers getting printed.

![image](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgvgtCuP2GcxIOqaJaRgo8QP-K6Hu1sp9pN78zrNEB9KBO8f7mOdrbbxTT8bC_A18MRh5mbKAhn0MUtKz-1OU0ptb1gvRamt9mGrFpIECT5s0rYYStzqQsjJYcL1fG82XTpESUQN0qcWsxtMAL2MiX5RlsoYTYIb9BJggVq_6XpcVlVaONuXuLGvXmcPxA/w640-h360/19.png)

After extracting all the 3D printed bits, I sanded them to give them a nice and smooth texture.


Coloring
--------

![image](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgYYr_eechPAf-YE2LytSvnrVV4xEBZjsJa_17Obk5rYUwptWCRun722VIX9YQ05PkFPEepRgTRwx5o_xZG_KBKheu3TZ8QXdLC3bYnvJ-Ozv5hqABxC25M6FI2Ueuv09LXCcsbLktYub45mYKJ4tWIUkSdyKfL8NtbmhO235fuHLlDLvyOtPxMJLMkAms/w640-h360/20.png)

Using Acrylic Colors, I painted the body of the 3D printed base.


Assembling
----------

![image](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhw6fPkebhNB8z5ZtuupqMDzSGraBbzasS_NC9ClpjBFKrrS2BKXZ-UiCd8SaQKeRj95gzNDST8g0XgQHAmEO5J6O5j38tRIsmIhmhFgSlsRB94pk3oGL1u0iBfp0-4KI-Ipq6Pieb5vYLTZGOCTZrcvsNa3kVxPDOhZ-jFw-5yt7M4wu01WGGrhpems_k/w640-h360/22.png)

Now the final bits. 
I soldered the baseplate and the 4 x flat-head LEDs to the 220v-to-5v Step Down Converter. Then I pushed all the flat head LEDs through the groves that I created in the 3D printed base. Then using the 4GX9 Pan Head Screws I screwed the 3D printed base to the base plate.

![image](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhgvdOkSAfLGv1NF9jHRCRFSH711k5VxyrC-NrblaPDLqkDqxlP3upUYhIj1rlEkJA-y6AfcQmiI465cqx5oVYjgKcTyPDU7pEJ5QSgak4cAHX-SdWyB99G7r2inCR61DTfxTQ8LI1qq38Vr17PD9qdDiYs-Usk0gnS9-7PCJmpYr2Ahq2-e3vrryKkabY/w640-h360/23.png)

Next, I soldered the AC power-cord to the step-down converter and hot-glued it to one of the sides of the 3D printed base.
I created an acrylic box for the cube which will keep the LED Mesh dust free.
To conclude the assembly, I screwed the cover to the base. That's it, all done.


Final Demo
----------

![image](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhXqKccg9HyQdqwVIxrxfvBVcPceGpCJIJffekbIvFfIWJRO3GvKlof-Ia0ZJDrSYi1XSOKKGcH9KeBmH5Q7z-kSguxHh93ihmH5icFgxBpcFIDM5u-4Zsir3tNbbIIC8zwjYESzNR_ANSNmyOj37i1mGvuSBMVjK4Ffs9ZwhPQcs-Rj0pZW3xQPddjIss/w640-h360/24.png)

So, this is how my final setup looks like.
Do comment, and let me know if there are any scopes of improvement.


Thanks
------

[![f7xFfsGhaso](https://i.imgur.com/d9frfg5.jpeg)](https://www.youtube.com/watch?v=f7xFfsGhaso)

Thanks again for checking my post. I hope it helps you.
If you want to support me subscribe to my YouTube Channel: https://www.youtube.com/user/tarantula3

Video: View https://youtu.be/f7xFfsGhaso

Full Blog Post: View https://diyfactory007.blogspot.com/2024/10/4x4x4-LED-Cube.html


**References**
GitHub: https://github.com/tarantula3/4x4x4-LED-Cube

Code: https://github.com/tarantula3/4x4x4-LED-Cube/blob/main/Code.ino

Stl Files: https://github.com/tarantula3/4x4x4-LED-Cube

Gerber Files:  https://github.com/tarantula3/4x4x4-LED-Cube



**Support My Work:**

BTC:  15cNh9hup8jidCVPwa1DTcxeoh2FPijVrX

LTC:  LbquH9Ku78vHtcm3LZnWXpD1JQWdKzeV4v

DOGE: DEB2QBAihnBRhGsaB8P7kz559TDiucQhX6

ETH:  0x5d8c9ba0e54d8354d4af81871db26daa190d2194

BAT:  0x939aa4e13ecb4b46663c8017986abc0d204cde60

LBC:  bZ8ANEJFsd2MNFfpoxBhtFNPboh7PmD7M2

COS:  bnb136ns6lfw4zs5hg4n85vdthaad7hq5m4gtkgf23 Memo: 572187879

BNB:  0x5d8c9ba0e54d8354d4af81871db26daa190d2194


Thanks, ca again in my next tutorial.



Odysee: https://odysee.com/@Arduino:7/4x4x4-PCB-LED-CUBE:8
Cos: https://cos.tv/videos/play/56311646746350592 
Rumble: https://rumble.com/v5ja7lp-4x4x4-pcb-led-cube.html
