# High-Speed-Digital-IO-RX
Analog Integrated Circuit (Implemented in Virtuoso Cadence)

This project can be divided into 2 blocks
-   LVDS Receiver
-   Deserializer

<br>

<p align="center">
   <img src="./schematic.jpg" width="600" height="300"/>
</p>

<br> <br>

## **LVDS Receiver**
This is basically a comparator. The comparator stage is a two-stage operational amplifier. The two stages can be categorized as: 
-   Differential amplifier stage
-   Common source amplifier stage

<br>

<p align="center">
   <img src="./comparator.jpg" width="600" height="400"/>
</p>

<br> <br>


## **Deserializer**
-   A serial to parallel converter.
-   Consists of 14 negative edge triggered D flip flops.

<br>


## **D Flip-Flop**
<br>

<p align="center">
   <img src="./D_FF_symbol.jpg" width="300" height="200"/>
   <img src="./D_FF.jpg" width="300" height="200"/>
</p>

<br> 

Inside D flip-flop there are NAND and NOT gates. Static CMOS implementation of these gates are following

<br>

<p align="center">
   <img src="./NAND.jpg" width="300" height="200"/>
   <img src="./NOT.jpg" width="300" height="200"/>
</p>

<br> 


## **Output**
<br>

<p align="center">
   <img src="./output.jpg" width="600" height="300"/>
</p>

<br> <br>

## **Goals Achieved**
<br>

<p align="center">
   <img src="./result.jpg" width="600" height="300"/>
</p>

<br>

## **Contributors**
1. Md. Tasnim Azad
2. Khaled Mahmud
3. Md. Siratul Mostakim Ifty 
4. Abhishek Das
