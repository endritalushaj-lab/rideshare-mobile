# Product Requirement Document (PRD) - Rideshare Mobile

## 1. Përmbledhja e Projektit (Overview)
**Rideshare Mobile** është një platformë digjitale për ndarjen e udhëtimeve (carpooling/ridesharing). Aplikacioni u mundëson shoferëve të publikojnë vendet e lira në makinë gjatë udhëtimeve të tyre dhe pasagjerëve të kërkojnë e të rezervojnë udhëtime me kosto më të ulët.

---

## 2. Problemi dhe Zgjidhja
* **Problemi:** Kostot e larta të karburantit për udhëtime ditore, trafiku i rënduar dhe mungesa e një platforme të sigurt e të thjeshtë për bashkëudhëtim.
* **Zgjidhja:** Një aplikacion mobil/web që mundëson lidhjen direkte mes shoferëve dhe pasagjerëve, me kërkim sipas destinacionit, datës dhe orarit.

---

## 3. Përdoruesit Synuar (Target Audience)
* **Pasagjerët:** Studentë, punonjës që udhëtojnë çdo ditë (commuters) dhe udhëtarë që kërkojnë transport më ekonomik.
* **Shoferët:** Personat që udhëtojnë rregullisht me makinë personale dhe dëshirojnë të ndajnë kostot e rrugës.

---

## 4. Veçoritë Kryesore (Key Features)

### A. Moduli i Pasagjerit:
1. **Kërkimi i Udhëtimit:** Filtrues sipas vendit të nisjes, destinacionit, datës dhe orës.
2. **Rezervimi:** Kërkesë për rezervim të një ose më shumë vendeve.
3. **Detajet e Udhëtimit:** Shikimi i profilit të shoferit, çmimit për vend dhe të dhënave të veturës.

### B. Moduli i Shoferit:
1. **Publikimi i Udhëtimit:** Vendosja e pikës së nisjes, mbërritjes, datës, orës, çmimit dhe vendeve të lira.
2. **Menaxhimi i Kërkesave:** Pranim ose refuzim i kërkesave për rezervim nga pasagjerët.

### C. Veçoritë e Përgjithshme:
1. **Autentikimi:** Regjistrimi dhe kyçja e përdoruesve (Login / Register).
2. **Profili i Përdoruesit:** Menaxhimi i të dhënave personale dhe historikut të udhëtimeve.

---

## 5. Staku Teknologjik (Technical Stack)
* **Frontend:** Next.js / React (Tailwind CSS për stilim).
* **Backend & Database:** PostgreSQL / Supabase ose Firebase.
* **Kontrolli i Versionit:** GitHub Repository (publik).

---

## 6. Plani i Zhvillimit (Roadmap)
* **Java 1:** PRD, Exit Ticket dhe struktura fillestare e projektit.
* **Java 2:** Dokumenti `java-02.md` dhe skica e ndërfaqes (`skica.png`/`jpg`).
* **Javët 3–15:** Zhvillimi i kodit në Next.js, integrimi i bazës së të dhënave dhe raportet javore `java-NN.md`.
