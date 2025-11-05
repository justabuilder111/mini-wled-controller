# Mini WLED Controller
- This is an esp32-based controller designed to be small, portable and run with WLED.
- It has an IR receiver and a microphone for audio reactive :D
- It runs off USB-C power so you can power it from a powerbank if you want to take it somewhere!
- I made it to put some cool looking LEDs in my room and to learn PCB design

3d render of the PCB:
![3D PCB](/img/3d_pcb.png)

PCB wiring:
![PCB](/img/pcb.png)

BOM:
|No.|Quantity|Designator             |Value|Manufacturer Part    |Manufacturer |Supplier Part|Supplier|Unit Price|
|---|--------|-----------------------|-----|---------------------|-------------|-------------|--------|----------|
|1  |7       |C1,C2,C5,C8,C12,C13,C14|     |CC0603KRX7R9BB104    |YAGEO(国巨)    |C14663       |LCSC    |0.0024    |
|2  |1       |C3                     |4.7uF|CL10A475KO8NNNC      |SAMSUNG(三星)  |C19666       |LCSC    |0.0092    |
|3  |1       |C4                     |     |CL10A106KP8NNNC      |SAMSUNG(三星)  |C19702       |LCSC    |0.0056    |
|4  |3       |C6,C15,C16             |     |CL10A226MQ8NRNC      |SAMSUNG(三星)  |C59461       |LCSC    |0.0087    |
|5  |2       |C7,C10                 |     |CL10A105KB8NNNC      |SAMSUNG(三星)  |C15849       |LCSC    |0.0047    |
|6  |1       |C9                     |470uF|RST470UF10V029       |KNSCHA(科尼盛)  |C4747954     |LCSC    |0.0338    |
|7  |1       |LED1                   |     |KT-0805G             |KENTO        |C2297        |LCSC    |0.0108    |
|8  |1       |LED2                   |     |TSOP38238            |VISHAY(威世)   |C141632      |LCSC    |0.6630    |
|9  |2       |Q1,Q2                  |     |BC817-25             |R+O(宏嘉诚)     |C20069154    |LCSC    |0.0179    |
|10 |1       |Q3                     |     |XC6220B331MR-G       |TOREX(特瑞仕)   |C86534       |LCSC    |0.4455    |
|11 |2       |R1,R2                  |     |0402WGF5101TCE       |UNI-ROYAL(厚声)|C25905       |LCSC    |0.0005    |
|12 |3       |R3,R4,R5               |     |0603WAF1002T5E       |UNI-ROYAL(厚声)|C25804       |LCSC    |0.0009    |
|13 |1       |R6                     |     |0402WGF1001TCE       |UNI-ROYAL(厚声)|C11702       |LCSC    |0.0006    |
|14 |3       |R7,R8,R9               |     |0603WAF510JT5E       |UNI-ROYAL(厚声)|C23197       |LCSC    |0.0011    |
|15 |2       |SW1,SW2                |     |TS-1088-AR02016      |XUNPU(讯普)    |C720477      |LCSC    |0.0423    |
|16 |1       |U1                     |     |ESP32-WROOM-32E-N8   |ESPRESSIF(乐鑫)|C701342      |LCSC    |4.137     |
|17 |1       |U2                     |     |CH340C               |WCH(南京沁恒)    |C84681       |LCSC    |0.5835    |
|18 |1       |U4                     |     |SN74LVC2T45DCUR      |TI(德州仪器)     |C15741       |LCSC    |0.1688    |
|19 |1       |U5                     |     |SPH0645LM4H-1-8      |Knowles(楼氏)  |C19272537    |LCSC    |1.7910    |
|20 |1       |U6                     |     |DB128L-5.08-3P-GN-S  |DORABO(地博电气) |C395869      |LCSC    |0.2745    |
|21 |1       |USBC1                  |     |TYPE-C 16PIN 2MD(073)|SHOU HAN(首韩) |C2765186     |LCSC    |0.0563    |
