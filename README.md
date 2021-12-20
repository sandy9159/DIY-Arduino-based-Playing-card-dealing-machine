# DIY-Arduino-based-Playing-card-dealing-machine
![we](https://user-images.githubusercontent.com/19898602/146784592-f232ae34-824a-4fbd-a28d-8bd448bcbc5c.png)


Hello friends in this project I have made an arduino based Playing card dealing machine.
Playing cards with friends is very fun time to enjoy, because I am tech nerd

I thought why not to add some tech flavour to the game and made some machine which dispense the card for the player.

So in this way I got idea to build this amazing machine, 

To build this card dealing machine I have used arduino nano as a micro controller and stepper motor and DC motor 
Stepper rotate the platform and other DC gear motor will dispense the card.

I also used my custom PCB for the complete project the custom PCB is very helpful to build arduino project 
If you are interested to build your custom PCB please read complete post I will share the Gerber file of PCB and more details.



# COMPONENT USED

> Arduino Nano
> A4988 Stepper driver
> Nema 17 stepper motor
> N20 DC gear motor
> Custom PCB
> 12mm wooden sheet



# BUILD
![image](https://user-images.githubusercontent.com/19898602/146786432-44a809a3-c633-4ae5-ab1f-002fba27f490.png)
![image](https://user-images.githubusercontent.com/19898602/146786477-84062ce6-453c-4931-9bc8-fea205c11f3a.png)

First of all I take the measurements on 12mm wooden sheet with the help of scale and pencil. 
I approx. cut the wooden piece in size of 130mm x 130mm


![image](https://user-images.githubusercontent.com/19898602/146786830-fb4bf24e-7611-400c-b4db-a8ae2415991d.png)
![image](https://user-images.githubusercontent.com/19898602/146786874-e2cbd352-131e-4d73-ad38-bb31208f2683.png)


Then I take a 4mm wooden sheet and draw a 100mm circle with the help of compass
Now I cut the round wooden sheet with the help of band saw machine 
Then I attached the disk to my mini lathe and give it last finishing touch with the help of sand paper
In this way I get perfect round wooden disc.


![image](https://user-images.githubusercontent.com/19898602/146787476-5f4d55fa-d2b0-4b29-a7d4-1ab865a03658.png)
![image](https://user-images.githubusercontent.com/19898602/146788041-4aaae177-5d83-4add-987f-87a1f74ef3f0.png)


After that I 3D printed this gear type ring this will be rigidly connected with the base of machine.
the gear connected the shaft will get lock with the base ring so when stepper motor rotate the hole platform will rotate.


## MULTIPURPOSE PCB ##
![FTQFHXZKLBNXU2X](https://user-images.githubusercontent.com/19898602/122632825-db9b8e80-d0f2-11eb-8281-3239f1275adc.jpg)
![147494540_1146948692400891_5797782675789162173_o](https://user-images.githubusercontent.com/19898602/122632834-ee15c800-d0f2-11eb-9385-0bcb4b05119a.jpg)

Making such projects without PCB is night mare yes trust me
you cannot get wanted result and professional touch in your project if you ignore PCB
So some days back I have developed my Multipurpose PCB.
This PCB is used to build wide range of arduino projects 

followings are the some features of PCB

1. Wide range of power input 9V to 24V DC
2. Cross polarity protection
3. DC motor voltage selection 9V or 12 V DC
4. Servo motor voltage selection 5V or 9V DC
5. Manual microstepping setting for stepper motor
6. Power indication LED
7. L298N IC for heavier DC motor
8. ON board 5V and 9V regulator no need to arrange different power sources
9. Header pins and screw terminals for easy connections

List of the Components you can connect to the PCB

1. 2 DC motor ( 9V to 24V DC)
2. 2 Potentiometer
3. 2 Servo motors ( 5V to 9V DC)
4. 1 Serial device (BT module, HMI, Communication module, RX, TX)
5. 1 Encoder (2 interrupt pin & 1 PB pin)
6. 1 I2C device (SCL/SDA Device, display, MPU6050 etc)
7. 2 Stepper motors

![147560983_1146948889067538_4990854912671411429_o](https://user-images.githubusercontent.com/19898602/122632848-fff76b00-d0f2-11eb-955e-207472be636d.jpg)
![component](https://user-images.githubusercontent.com/19898602/122632849-01289800-d0f3-11eb-970a-53fc1b6e0b58.jpg)


I have design circuit and PCB in [easyEDA](https://easyeda.com/) and ordered PCB from [JLCPCB](https://jlcpcb.com/IAT )

This is the link of [PCB editabl file](https://oshwlab.com/sharmaz747/multipurpose-pcb)

If you seriously need quality PCB quickly in your hand then you must have to try [JLCPCB](https://jlcpcb.com/IAT ) PCB manufacturing service.
They have Special offer of $2 for 1-4 Layer PCBs, free SMT assembly monthly.
If you get yourself registered today at [JLCPCB](https://jlcpcb.com/IAT ) you get 18$ welcome coupon from [JLCPCB](https://jlcpcb.com/IAT ).








