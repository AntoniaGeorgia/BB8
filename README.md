<h1 align="center">
BB-8 Replica 
</h1>

## _Introducere_ :

Acest proiect are ca scop construirea unei replici funcționale a robotului BB-8 din universul cinematografic Star Wars. Pe lângă aspectul său iconic, replica va fi dotată cu funcționalități practice, cum ar fi controlul wireless prin intermediul modulului Bluetooth ZS-040. Robotul BB-8 este cunoscut pentru designul său unic, compus dintr-un corp sferic care se mișcă liber, pe care este fixat un "cap" rotativ.  
Proiectul își propune să integreze mecanisme electronice, comunicare wireless și software pentru a asigura funcționarea optimă și interacțiunea cu utilizatorul printr-o aplicație mobilă. Această realizare va combina elemente de robotică, programare și design industrial, fiind un exemplu captivant de tehnologie aplicată.  
Pentru implementare, se va folosi limbajul de programare C++, datorită eficienței sale și a compatibilității excelente cu platformele embedded. De asemenea, proiectul va integra un timer hardware/software, esențial pentru sincronizarea funcțiilor robotului, cum ar fi controlul motoarelor și gestionarea comenzilor Bluetooth.

Această combinație de programare de nivel jos, mecanisme fizice și control wireless va oferi un model funcțional și inteligent al robotului BB-8, capabil să fie controlat prin aplicație mobilă.

## _Laboratoare folosite_
- Lab 1 
- Lab 2 - folosesc timere
- Lab 4 - pentru comunicare Bluetooth

## _Lista de piese_ :

| Componentă       | Descriere                                    | Cantitate | Poze              |
|-------------------|----------------------------------------------|-----------|-------------------------|
| Arduino Uno       | Placă de dezvoltare pentru control           | 1         | <img src="https://github.com/AntoniaGeorgia/BB8/blob/main/img/ARD" width="100">  |
| L292N Shield       | Driver pentru motoare                       | 1         | <img src="https://github.com/AntoniaGeorgia/BB8/blob/main/img/l293.jpeg" width="100"> |
| Servo             | Motor servo pentru mișcare precisă          | 1         | <img src="https://github.com/AntoniaGeorgia/BB8/blob/main/img/servo.jpeg" width="100">                      |
| Bluetooth ZS-040  | Modul Bluetooth pentru control wireless     | 1         | <img src="https://github.com/AntoniaGeorgia/BB8/blob/main/img/HC-05-Bluetooth-ZS-040-Button.jpg" width="100">                    |
| Motor DC          | Motor de curent continuu pentru roți        | 2         | <img src="https://github.com/AntoniaGeorgia/BB8/blob/main/img/motor%20dc.jpeg" width="100">   |
| Roti              | Roti pentru motor DC                        | 2         | <img src="https://github.com/AntoniaGeorgia/BB8/blob/main/img/set-de-4-roi-negre-cu-aderena-puternica.jpg" width="100">  |
| Fire              | Cablu pentru conectare componente           | Mai multe | <img src="https://github.com/AntoniaGeorgia/BB8/blob/main/img/wire.jpeg" width="100">       |
| Magneti           | Magneti pentru fixare sau funcționalitate   | Mai multe | <img src="https://github.com/AntoniaGeorgia/BB8/blob/main/img/magneti.jpeg" width="100">     |
| Baterii           | Sursa de energie pentru Arduino și motoare  | 1 set     | <img src="https://github.com/AntoniaGeorgia/BB8/blob/main/img/standarde-baterii-1.jpg" width="100">  |

## _Poze_

![BB8](https://github.com/user-attachments/assets/0251fe0e-a6a9-4fb1-9160-7d2d179cf6eb)


<img src="https://github.com/AntoniaGeorgia/BB8/blob/main/BB8.jpeg" align="right"
     alt="Size Limit logo by Anton Lovchikov" width="120" height="178">

## _Schema electrică_

Schema electrică integrează modulul Bluetooth ZS-040 conectat la pinii A0 și A1 pentru comunicare serială, împreună cu driverul de motor L292N și motoarele DC. Acest setup permite controlul motoarelor prin comenzile trimise de utilizator prin intermediul aplicației mobile.

## _Etape realizare corp robot_

1. **Construcția corpului sferic și a cadrului intern**: Am folosit imprimanta 3D din laboratorul 314 pentru a realiza suportii pieselor , doi piloni de sustinere si un cilindru pentru a fi actionat de servomotor .Pentru realizarea schemei 3D am folosit aplicatiile AUTODESK FUSION si PRUSA .
   Imagini cu realizarea etapelor :
    
 <img src="https://github.com/user-attachments/assets/02ef5ad4-58c3-4308-bf49-d6c46aa57aa1" width="500">

   <img src="https://github.com/user-attachments/assets/7877d16f-17dc-4cd1-9ea8-11d57c953b41" width="500">

   <img src="https://github.com/user-attachments/assets/250471c0-aacb-460a-8f44-2eb10e42faf5" width="500">

   <img src=" https://github.com/AntoniaGeorgia/BB8/blob/main/img/WhatsApp%20Image%202024-12-19%20at%2016.31.36_4fe6543a.jpg" width="500">
 <img src="https://github.com/AntoniaGeorgia/BB8/blob/main/img/WhatsApp%20Image%202024-12-19%20at%2016.31.37_54c3725b.jpg" width="500">
 <img src="https://github.com/AntoniaGeorgia/BB8/blob/main/img/WhatsApp%20Image%202024-12-19%20at%2016.31.38_b355ada0.jpg" width="500">
 <img src="https://github.com/AntoniaGeorgia/BB8/blob/main/img/WhatsApp%20Image%202024-12-19%20at%2016.31.38_ce4c7c35.jpg" width="500">
 <img src="https://github.com/AntoniaGeorgia/BB8/blob/main/img/WhatsApp%20Image%202024-12-19%20at%2016.50.07_f9c2a346.jpg" width="500">
   


     https://github.com/user-attachments/assets/b1289d51-c061-4a3d-81a7-7f5a8ad521d3






   

3. **Montarea componentelor electronice**: Pe primul suport am montat cele doua motoare, rotile, acumulatorul care este o baterie de 9V si modulul bluetooth . Pe acestea le-am conectat la shield , care era totodata conectat la placuta arduino uno.  
4. **Scrierea codului pentru control wireless**:  
5. **Testare finală și optimizare**: 

## _Cod_







