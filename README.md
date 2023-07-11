# AnetA8_with_KMS_Tinybee_v1
This repository contains the binary files and some instructions for improving the old Anet A8 with new electronic components, in this case with the board KMS Tinybee. This board uses the esp32 controller.

# List of hardware used
I use the following hardware to improve the old anet A8 problems.

*Original Anet A8 hardware 
*Drivers (A4988 or TMC2209) - I used TMC2209 (comes with the board when you buy it)
*Board KMS Tinybee V1 and drivers (https://es.aliexpress.com/item/1005003822446877.html?spm=a2g0o.order_list.order_list_main.29.1875194dE3BpYl&gatewayAdapt=glo2esp)
*3D printed case (I will probably design it in the future)
*3D touch sensor 
*Low noise extruder fan (12V) (https://es.aliexpress.com/item/4001177586848.html?spm=a2g0o.order_detail.order_detail_item.13.748d39d3o8vp3N&gatewayAdapt=glo2esp)
*Two fans (12V) for electronics (https://es.aliexpress.com/item/1005004526691880.html?spm=a2g0o.order_detail.order_detail_item.10.748d39d3o8vp3N&gatewayAdapt=glo2esp)

# Instructions

* Put the drivers in the board.
  
You can use the A4988 or the TMC2209, but I recommend to use the TMC if want to use the printer at night, because they are very silent.

(photo)

* Ajust the drivers current

Depending on which drivers you used, you need to see the current for the motors. But, here I am going to tell what worked for me.
In my case I used the TMC2209, so 

<img scr="https://wiki.fysetc.com/images/2209%E6%B5%8Bvref.png">

In the first time, I adjusted the voltage to 0.9 volts, however, motor got very hot. Then, I used a voltage of 0.6 volts.

* 


