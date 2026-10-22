# Raporti Javës 3 - Rideshare Mobile

## 1. Përmbledhja e Punës
Në këtë javë kemi ndërtuar strukturën bazë të aplikacionit RideShare duke përdorur App Router të Next.js. Kemi krijuar një komponent të ripërdorshëm kartash dhe tri faqe kryesore.

---

## 2. Provat e Ekzekutimit

### Prova 1
Në faqen kryesore `/` shfaqen saktësisht 3 karta udhëtimesh. Faqja u testua në ekran telefoni (375px) dhe teksti është i lexueshëm pa lëvizje horizontale.

### Prova 2
Klikimi te karta e dytë dërgon te `/udhetimi/2` me detajet e Fushë Kosovës. Karta e tretë (Lipjan) ka 0 vende dhe butoni shfaqet i çaktivizuar ("Nuk ka vende të lira"). Qasja te `/udhetimi/99` shfaq faqe 404 me mesazhin "Udhëtimi nuk u gjet" dhe mundësi kthimi te lista.

### Prova 3
Klikimi te "Kërko vend" te udhëtimi 2 dërgon te `/udhetimi/2/kerkesa` ku shfaqet titulli "Simulim: Në pritje" me buronin për t'u kthyer mbrapsht te detajet.

---

## 3. Konkluzion
Rrjedha prej tre ekranesh funksionon me sukses me të dhëna fiktive.
