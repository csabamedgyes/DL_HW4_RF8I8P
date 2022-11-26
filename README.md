# DL_HW4_RF8I8P

Hello! My name is Csaba Medgyes (RF8I8P) and this is the repo of the 4th Homework for our Deep Learning class. The excercises are the following:

A cél egy előtanított CNN háló tovább tanítása:

    Válassz ki három tetszőleges kategóriát a Google Open Image Dataset-ből (GOID: https://storage.googleapis.com/openimages/web/index.html) és tölts le 400 képet kategóriánként. 
    Tölts be tetszőleges előtanított hálót (pl. Inception v3, VGG, ResNet) és tanítsd tovább (transfer learning) a kiválasztott három kategóriával:
        Előbb csak a végső fully-connected rétegek tanuljanak.
        Majd az így tovább tanított hálót tanítsátok még tovább úgy, hogy a konvolúciós rétegek felsőbb rétegei is tanulnak (az alsóbbak nem).
    Egy elkülönített teszt adatbázison, a kiválasztott három kategóriával értékeld ki a megoldás hatékonyságát.
    Figyelj arra, hogy
        a kép letöltés módszerét, scriptjét (ha saját kód) is mellékeld,
        a tanító adatbázisban 200-200, a validációsban 100-100, a tesztben 100-100 kép legyen,
        egy képet csak egy adatbázis részben használj fel,
        azonos előfeldolgozó eljárást használj, mint amit az előtanított hálónál alkalmaztak.

Segítségként javasoljuk az alábbi forrás felhasználását: https://blog.keras.io/building-powerful-image-classification-models-using-very-little-data.html
A kis házi feladatot angol nyelven add be! Törekedj a minél rövidebb kódra!

Csak Github-ra secret gist-ként feltöltött Jupyter notebook formátumot fogadunk el, amelyben a kódok mellett magyarázat és az eredmények is láthatóak. A Notebook-ban szerepeljen az „Open in Colab” nyomógomb, amire kattintva megnyitja a notebook-ot Google Colab alatt. A megoldás URL-jét küldd be. 
