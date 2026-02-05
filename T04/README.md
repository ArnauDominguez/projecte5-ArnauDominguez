# T04: Instal·lació Windows Server 2025

## Introducció al cas

Després del nostre assessorament, **TransLògic S.A.** ens encarrega el desplegament dels seus servidors **Windows Server 2025**.

Per aquest motiu, haurem de desplegar diverses màquines virtuals i, amb l’objectiu de ser eficients i seguir bones pràctiques, realitzarem una instal·lació de prova que servirà tant per aprendre els procediments com per elaborar una **guia d’instal·lació**. Aquesta guia ha de proporcionar una documentació base per a la posterior implantació als sistemes del client.

## Procediment

- Crea una màquina virtual amb **8 GB de RAM** i **dos processadors**.  
  La VM disposarà de:
  - Un disc principal de **32 GB** (on s’instal·larà el sistema operatiu)
  - Un disc secundari de **10 GB**
  - **Dues interfícies de xarxa**:
    - Una en xarxa **NAT (no NAT)**
    - Una segona en mode **host-only**

- Instal·la **Windows Server 2025** en mode **GUI**, amb:
  - Idioma: **US**
  - Configuració regional i teclat: **espanyol**

- Canvia el nom de l’equip a **DCxx** (on `xx` correspon al vostre número de llista).

- Actualitza la màquina virtual i, un cop finalitzades les actualitzacions, **pausa-les el màxim temps possible**.

## Contingut de la guia

- Compara la configuració de la màquina virtual definida a l’apartat anterior amb els **requisits indicats per Microsoft**.  
  Són coherents?

- Documenta els diversos procediments de la instal·lació amb:
  - **Captures de pantalla**
  - **Observacions personals**

> Recorda que el format a utilitzar és **MarkDown**.

## Materials i links de suport

- **UD.6. AA2. Instal·lació Windows Server 2025**  
  *[Moodle 0224 Sist. Operatius en Xarxa]*

- **Requisitos de hardware para Windows Server**  
  *Microsoft Learn* (enllaç)

[Solucio](Solucio.md)

[Tornar pàgina projecte](../README.md)
