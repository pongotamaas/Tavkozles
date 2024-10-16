
## &#928; Csillapító Áramkör Jegyzőkönyv.

**Mérés helye**: Miskolci SZC Kandó Kálmán Informatikai Technikum  
**Mérés időpontja**: 2024.10.09.  
**Mérő műszerek**: HMO1002 Oscilloscope - 1764K02-102609-WG  
**Felelős személy**: Sándor Péter  
**Cél**: A pi csillapító áramkör elemzése.

---

### 1. **Bevezetés**

A projekt célja egy PI csillapító áramkör megépítése, amelynek fókuszában a csillapítás mérése áll.
Az áramkört breadboardon építettem meg, a könnyedség kedvéért.

![R1 képlete](https://raw.githubusercontent.com/pongotamaas/Tavkozles/refs/heads/main/img/szamolas.png)


6 dB-es csillapításra kiszámolt ellenállás értékek:

A kapcsolási rajz ábrázolja a jelgenerátort a belső ellenállásával, valamint a Pi csillapítót a kiszámolt ellenállás értékekkel:

![kapcsolási rakz](https://raw.githubusercontent.com/pongotamaas/Tavkozles/refs/heads/main/img/fingocska.PNG)

### 3. **Mérési paraméterek**

| Paraméter           | Érték |
|---------------------|-------|
| Generátor jel       |5,148 Vp2p |
| Kimeneti Jel        |2,501 Vp2p  |
| Generátor Frekvencia|1kHz  |
| Csillapítás         |-627dB  |
| Átviteli Arány      |6,27dB  |
| Bemeneti impedancia |-  |
| Kimeneti impedancia |- |   

<br>

Látható az oszcilloszkópon a sárga 1-es csatornán a csillapított kimeneti jel, és a kék 2-es csatornán a generátor jel.




### 4. **Mérési eredmények**

- **Kimeneti Jel**: A kimeneti jel mindössze 48,6%-a a generátor jelének.
  
- **Csillapítás/Átviteli arány**:   6,27dB csillapítást tapasztalunk az áramkör jóvoltából.

- **Kimeneti/Bemeneti impedancia**: ??????.  

### 5. **Elemzés**
A pi csillapító (pi pad) ellenállás áramkörének elemzése során megfigyelhető, hogy a tervezett áramkör hatékonyan csökkenti a jel amplitúdóját, miközben megőrzi a jel formáját. Az áramkör négy fő komponensből áll: három ellenállásból és egy terhelő ellenállásból. Kisebb eltérés tapasztalható a kiszámolt értékek és a valós értékek között.

### 6. **Következtetések**
A pi csillapító áramkör sikeresen megvalósult, és a tesztelési eredmények azt mutatják, hogy a csillapítási teljesítmény megfelel a tervezett specifikációknak. A mérések alapján a csillapító hatás a kívánt frekvenciatartományban optimális, és a jelminőség megőrzése is megfelelő. A projekt során szerzett tapasztalatok alapján a tervezési folyamat során figyelembe kell venni a komponensek toleranciáját és a környezeti hatásokat, mivel ezek befolyásolhatják az áramkör teljesítményét.

### 7. **Javaslatok**


---

**Aláírás**:  
Felelős mérő személy: ..............................  
Dátum: .............................................
