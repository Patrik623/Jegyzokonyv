# Monostabilmultivibrator
---  
- Mérést végezte: Kiss Patrik
- Mérés helye: Villamos 3 labor
- Mérés ideje: 2025.03.11.
- Csoport: 12.D/1


---   

## A mérés folyamata:
>Mérés célja: Az 555-ös időzítő IC felhasználásával egy monostabil multivibrátor áramkör építése, amely egy gomb megnyomásával egy led-et világit meg adott ideig.



---


## Méréshez használt eszközök / berendezések:
- NI Mydaq: 234246436835685SN
- - **NI myDAQ**
- **Breadboard**
- **555 időzítő IC**
- **LED**
- **Nyomógomb**
- **Ellenállások:**
  - 10 kΩ (2-es láb és gomb között)
  - 1 MΩ (7-es és 4-es láb között)
  - 220 Ω (LED védelmére)
- **Kondenzátor:**
  - 10 µF (6-os lábra kötve)
- **Tápfeszültség:**
  - 5V a 8-as lábra kötve


---


## Kapcsolas:
- Kapcsolási rajz az alábbi linken megtalálható: ![circuit-20250311-1209](https://github.com/user-attachments/assets/b0562f80-33d9-4bc7-b73f-6a13d0cd2130)
  
## Kapcsolási rajz megvalósitása: 
![image](https://github.com/user-attachments/assets/de53c4b7-034d-40dc-9698-e7786c08982f)

---

## Működés leírása:
- A nyomógomb lenyomásakor az 555-ös IC 3-as kimenete magas szintre vált, és a LED világítani kezd. A LED körülbelül **30 másodpercig** világít, majd automatikusan kikapcsol.
  



   

