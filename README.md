# Split Mechanical Keyboard

The keyboard uses a split layout with around 76 keys, The design is meant to be customizable and DIY-friendly. It uses Kailh hot-swap sockets, which means switches can be replaced anytime without needing to desolder them. This makes it easy to experiment with different switches later. For the controller, I used the nRF52840 development board, which works well with ZMK firmware. ZMK alows the keyboard to support Bluetooth, so it can be used wirelessly. It also support customizable keymaps, layers, and other advanced keyboard features. 

Designing the PCB took a lot more time than I expected. there were many small issues during routing and schematic checks. I spent quite a lot of time fixing different problems and improving the layout. After several iterations and debugging, the **PCB now finally passes both DRC (Design Rule Check) and ERC (Electrical Rule Check) with 0 errors**. Fixing all those issues took a lot of effort, but it was really satisfying to finally see everything clean in KiCad. The keyboard uses 76 mechanical switches, and each switch has a 1N4148 diode for the key matrix. Stabilizers are used for larger keys, and the switches are mounted using Kailh hot-swap sockets. Keycaps and switchs can be changed depending on personal preference. Also one of my fried recently built his own keyboard through stasis and he have some left over part which I can take use in when I'll built this keyboard, he even told me he'll be helping me to built this!!

One goal of this project was also to keep the build relatively affordable. Based on the current Bill of Materials, the estimated total cost is around ₹10,455 (~$110.72 USD) including PCB manufacturing and other components. I tried my best to keep it in budget, I tried to get maximum thing from one place (amazon) in budget to make things simple and save in shipping charges. Also I'll buy the PCBs locally and it would cost me around $20.

Overall, this project was mainly built for learning, experimenting, and having fun with hardware design. It was a really good experience going through the full PCB design process and understanding how keyboards work internally. If someone finds this project interesting or wants to build their own version of it, that would be really awesome.

<img width="684" height="653" alt="Screenshot 2026-04-24 233628" src="https://github.com/user-attachments/assets/8f9ec1d5-118c-4074-90d8-1475d44e785f" />
<img width="777" height="656" alt="Screenshot 2026-04-24 233605" src="https://github.com/user-attachments/assets/f1436d72-cd7e-481f-8213-9795b5cf3d2a" />
<img width="697" height="659" alt="Screenshot 2026-04-24 234435" src="https://github.com/user-attachments/assets/55d02a4c-e218-436f-89db-941f5ee10852" />
<img width="664" height="629" alt="Screenshot 2026-05-07 192928" src="https://github.com/user-attachments/assets/725f8d70-ba4a-456b-8bc0-bf6a1ebc8387" />
<img width="1174" height="894" alt="Screenshot 2026-05-09 214136" src="https://github.com/user-attachments/assets/6d7494b2-8d3d-4a1c-8ed3-a23762b212ac" />
<img width="1111" height="810" alt="Screenshot 2026-05-09 214242" src="https://github.com/user-attachments/assets/de010748-bae8-4fa5-9d44-82b5ca4ad1ad" />
<img width="1037" height="807" alt="Screenshot 2026-05-09 214315" src="https://github.com/user-attachments/assets/ee60e112-10e5-4dc3-b998-d553b4b1f6d7" />
<img width="1241" height="856" alt="Screenshot 2026-05-09 214406" src="https://github.com/user-attachments/assets/559aefbb-d593-4bd6-941e-816d8cd2e9bd" />
<img width="876" height="663" alt="Screenshot 2026-05-09 215040" src="https://github.com/user-attachments/assets/66895f81-c8bb-483e-bd99-70fb3973f028" />


## Cart:

<img width="1165" height="968" alt="Screenshot 2026-05-10 230352" src="https://github.com/user-attachments/assets/b10a133c-48cd-4fa0-816b-b7af50b12524" />
<img width="1919" height="1039" alt="Screenshot 2026-05-10 230543" src="https://github.com/user-attachments/assets/268ae494-2e20-4e4d-861b-5b8944e5ac50" />



## Bill of Materials (BOM) – Split Keyboard

| # | Component | Quantity | Unit Price | Total | Link |
|---|-----------|---------|-----------|------|------|
| 1 | Kailh Hot-Swap Sockets | 1 pack (~100 pcs) | ₹2476 | ₹2476 | https://www.amazon.in/gp/product/B0GHR248QJ) |
| 2 | Mechanical Switches | 76 (1 pack) | ₹1965 | ₹1965 | https://www.amazon.in/gp/product/B0F53HLG5M |
| 3 | Stabilizers | 1 pack | ₹1,929 | ₹1,929 | https://www.amazon.in/gp/product/B0CL195BK7 |
| 4 | Keycaps | 1 sets | ₹928 | ₹928 | https://www.amazon.in/gp/product/B0F3883M9C |
| 5 | 1N4148 Diodes | 1 pack (~100 pcs) | ₹285 | ₹285 | https://www.amazon.in/gp/product/B0FJLP12GX |
| 6 | nRF52840 Microcontroller | 1 | ₹758 | ₹758 | https://robu.in/product/promicro-nrf52840-development-board/ |
| 7 | PCB (Will buy it locally) | 1 order (2PCB) | $20 | ≈ ₹1838 | — |

---
### Total Estimated Cost

| Item | Cost |
|-----|------|
| Components Total | ₹8,567 |
| PCB | ≈ ₹1,888 |
| **Total Build Cost** | **≈ ₹10,455** (**$110.72 USD**) |
