# T07: Acadèmia feta amb Moodle

Pràctica **individual i tancada**.  
L’objectiu és demostrar que ets capaç d’**instal·lar, personalitzar, configurar i gestionar Moodle** com ho faries en un encàrrec real d’una organització.

Treballaràs per a un client concret: una escola d’ensenyament secundari anomenada **Escola Júlia**, que necessita un **portal d’aprenentatge online** per facilitar la comunicació i l’aprenentatge entre professorat i alumnat.  
Per fer-ho, s’ha decidit utilitzar **Moodle**.

> **Molt important:** aquesta pràctica està dividida en **5 parts**.  
> Quan acabis cada part, **avisa el professor/a** perquè validi que ho tens tot correcte.  
> L’avaluació es farà **en directe**: hauràs d’ensenyar cada part, explicar **on ho has configurat**, **per què** i **demostrar que funciona**.

---

## Part 1: Instal·lació i configuració inicial de Moodle

Una escola d’ensenyament secundari, anomenada **Escola Júlia**, ens ha demanat el desenvolupament d’un portal web d’aprenentatge amb l’objectiu d’oferir, tant als professors com als alumnes, una plataforma online que faciliti la comunicació i l’aprenentatge.

Segueix les indicacions següents per adaptar el Moodle a les necessitats del client.

### 1. Instal·lació de Moodle
- Descomprimeix Moodle al servidor web.
- Accedeix-hi des del navegador per iniciar la instal·lació.
- Crea una base de dades **MySQL Improved** amb el nom `moodle`.
- Usuari de la BD: `root`  
- Contrasenya: `root`
- Crea el compte d’administrador:
  - Usuari: `admin`
  - Contrasenya: `Administrador_1`
  - Indica també email, població i país.

### 2. Idioma
- Configura el **català** com a idioma predefinit del Moodle.

### 3. Primera pàgina del lloc
- Nom complet: **Escola d’Ensenyament Secundari Júlia**
- Nom curt: **Escola Júlia**
- Afegeix una **descripció detallada** dels valors i compromís de l’escola (copiada d’una altra escola).
- La pàgina inicial:
  - No mostrarà res abans d’iniciar sessió.
  - Un cop dins, mostrarà:
    - Categories de cursos
    - Caixa de cerca de cursos

### 4. Aparença
- Aplica un **tema nou** (diferent dels predeterminats).
- Modifica el **favicon** per un de personalitzat.
- Si el tema ho permet, mostra el **logo de l’escola**.

---

## Part 2: Gestió d’usuaris, rols i cursos

### 1. Categories de cursos
- Crea les següents categories:
  - 1er ESO
  - 2on ESO
  - 3er ESO
  - 4rt ESO

### 2. Professors
Crea els comptes d’usuari:
- Pedro Ruiz Gomez
- Benito Wolff Ruiz
- Angel Lobo Mateo
- Claudia Blazquez Tomas
- Vicente Puñal Pineda  

Configuració segons l’**arxiu adjunt núm. 1**.

### 3. Rol de creador de cursos
- Assigna a **Pedro Ruiz Gomez** el rol de **creador de cursos**.

### 4. Modificació del rol
- Dona permís al creador de cursos per **gestionar categories**:
  - Administració del lloc → Usuaris → Definició de rols → Creador de cursos → Editar

> **IMPORTANT:** inicia sessió com **Pedro Ruiz Gomez**.

### 5. Curs Matemàtiques 1
- Categoria: 1er ESO
- Nom curt: `MAT_1ESO`
- Inici: 12/09/2025
- Visible
- 5 temes (1 per pàgina)
- Idioma: català
- Màx. 5 notícies
- Qualificacions i informes visibles
- Fitxers: màx. 2 MB
- Sense grups
- Rol professor: **Senyor Ruiz**
- Resum: arxiu adjunt núm. 2 (amb format)

### 6. Curs Taulell d’anuncis 1
- Nom curt: `TAU_1ESO`
- Format social
- Idioma: català
- Sense notícies, qualificacions ni informes
- Fitxers: màx. 2 MB
- Sense grups
- Resum: *Taulell d’anuncis de 1er de la ESO*

### 7. Curs Informàtica 1
- Nom curt: `INF_1ESO`
- 12 setmanes en una sola pàgina
- Temes ocults visibles
- Idioma: català
- Amb grups (grups separats)
- Professor: **Senyor Ruiz**
- Professor no-editor: **Senyoreta Blazquez**
- Resum: arxiu adjunt núm. 3

### 8. Ordre dels cursos
- Fes que **Taulell d’anuncis 1** aparegui el primer.

### 9. Assignació de professors
- Pedro Ruiz Gomez: Matemàtiques 1 i Informàtica 1 (professor)
- Claudia Blazquez Tomas: Informàtica 1 (professor no-editor)
- Comprova limitacions com a professor no-editor.

### 10. Automatriculació
- Matemàtiques 1 → `mates1`
- Informàtica 1 → `info1`
- Taulell d’anuncis 1: accés de **visitants** amb contrasenya `guest`

### 11. Autenticació per correu
- Activa **autoregistre per correu electrònic**:
  - Administració del lloc → Connectors → Autenticació → Gestió

### 12. Alumne de prova
- Registra un alumne i confirma’l manualment com a administrador.

---

## Part 3: Afegir continguts al curs Matemàtiques 1

Professor: **Pedro Ruiz Gomez**

- Títols i resums dels 5 temes
- Etiqueta superior amb imatge
- Fòrum (subscripció automàtica)
- Glossari amb 3 entrades
- Xat setmanal
- Enquesta COLLES
- Enllaç XTEC
- Pàgina amb criteris d’avaluació (taula)
- Reordenació d’elements

---

## Part 4: Activitats avançades

Tema **Nombres**:
- Etiquetes (Apunts, Exercicis pràctics, Exercicis d’avaluació)
- Consulta
- Lliçó (nombres racionals)
- Qüestionari
- Tasca text en línia
- Tasca de fitxer

---

## Part 5: Blocs, plugins i còpies de seguretat

> **IMPORTANT:** cal fer-ho com a **administrador**

### 1. Blocs
- Calendari
- Esdeveniments propers
- Usuaris en línia
- Els meus cursos
- Comentaris
- Entrada aleatòria del glossari
- Canal RSS remot
- Text (amb enllaços externs)

### 2. Gadgets
- Rellotge JavaScript
- Gadget web extern

### 3. Insígnies
- Activitat 1
- Activitat 2
- Activitat 3
- Activar seguiment de compleció

### 4. Còpia de seguretat
- Backup del curs **Matemàtiques 1**
- Restauració com:
  - Nom: *Matemàtiques 1 backup*
  - Nom curt: `MAT_BCKP`

