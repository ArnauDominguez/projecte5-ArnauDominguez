# T03: Serveis de transferència de fitxers

## Introducció a la tasca

En la vostra experiència a **EverPia** heu configurat serveis molt importants com **DHCP**, **DNS**, així com la connexió i administració remota dels equips.

Ara que comenceu el vostre camí en solitari, necessiteu ampliar coneixements i, tot i que serveis de *cloud* com **Dropbox**, **Google Drive**, etc. són en moltes ocasions la forma més habitual de descarregar arxius, voleu dominar els **protocols fonamentals de transferència**.  
Per aquest motiu, us inscriviu a una formació per convertir-vos en experts.

## Objectius de la formació

En acabar aquesta formació, haureu de ser capaços de respondre a aquestes preguntes amb **fets i configuracions reals**:

- Com funciona el **protocol FTP**?
- Quina diferència hi ha entre el **mode actiu** i el **mode passiu**?
- Implementació d’un **servidor FTP segur**.
- Protocol **sFTP** com a alternativa al FTP tradicional.
- **Engabiat d’usuaris** en connexions SFTP.
- Altres **mètodes alternatius** per a la transferència de fitxers.

## Pla de treball: què farem?

Aquesta formació es dividirà en **dues parts clarament diferenciades**: la fonamentació teòrica i la implementació real.

### 1. Fonaments teòrics i seguretat

Estudi dels protocols **FTP** i **sFTP**, parant especial atenció a:
- Modes **actiu** i **passiu** del FTP
- **Engabiat d’usuaris**
- Aspectes de **seguretat**

### 2. Laboratori pràctic (The *Real World*)

Posarem les mans al teclat. Configurarem **dos entorns diferenciats** utilitzant màquines virtuals:

#### Activitat A – Servidor FTP
- Configuració d’un servidor FTP estàndard  
- Creació d’usuaris  
- Engabiat (*chroot*)  
- Permisos de lectura i escriptura  
- Anàlisi de la transferència de dades **en clar** (sense xifrar)

#### Activitat B – Servidor sFTP (Secure FTP)
- Implementació de la transferència de fitxers sobre **SSH**
- Engabiat d’usuaris per evitar **fuites de seguretat**

> **Nota important:**  
> Com a administradors, la seguretat **no és una opció**, és una obligació.  
> Entendre la diferència entre aquests dos protocols és **vital** per al vostre futur professional.

## Sistema d’avaluació

Per superar aquesta formació, haureu de demostrar la vostra competència en **dos formats**:

- **Prova escrita**  
  Preguntes sobre protocols, ports, modes de connexió i conceptes de seguretat teòrica.  
  **(40%)**

- **Examen pràctic** (*repte de configuració cronometrat*)  
  Haureu d’aixecar des de zero:
  - Un servidor **FTP**
  - Un servidor **sFTP**
  - Configurar usuaris amb permisos específics
  - Verificar la connexió des d’un client extern  
  **(60%)**

Prepareu les vostres màquines virtuals.  
**Comencem a transferir dades!**

## Materials i enllaços de suport

- Materials de l’assignatura  
  **Moodle Serveis de Xarxa**

