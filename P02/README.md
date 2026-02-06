# P02: Llicenciament Windows Server 2025

Mentre inicieu la vostra aventura emprenedora, cal seguir pagant factures. Gràcies a la gran feina que vau desenvolupar a **EverPia**, els responsables de la consultora han decidit donar-vos suport, passant-vos encàrrecs de clients que ara mateix no estan en condicions d’acceptar.

## Introducció al client

L’empresa **TransLògic S.A.**, dedicada a la logística regional, vol renovar la seva infraestructura de servidors a la versió **Windows Server 2025**. Actualment disposen d’un servidor físic antic que ha quedat obsolet i volen **virtualitzar tota la seva càrrega de treball** per millorar la disponibilitat.

## Detalls de la infraestructura

### Servidor físic (Host)
- 1 unitat amb **2 processadors (CPUs)**  
- Cada processador té **12 nuclis (cores) físics**  
- **Total: 24 nuclis**

### Càrrega de treball (Màquines Virtuals – VMs)
- 1 VM per a **Controlador de Domini (Active Directory)**
- 1 VM per a **Servidor de Fitxers**
- 1 VM per a **Servidor d’Impressores i Gestió Documental**
- 1 VM per a **SQL Server (Base de dades de l’ERP)**
- 8 VMs de suport per a **aplicacions de logística i terminals de magatzem**
- **Total: 12 màquines virtuals amb Windows Server**

### Usuaris i dispositius
- **45 empleats** en total
- **30 treballadors d’oficina** (tenen el seu propi PC i portàtil)
- **15 mossos de magatzem** (comparteixen **5 tauletes robustes** per fer inventari en **3 torns**)

## Encàrrec del client

Com a consultors informàtics, haureu de:

1. Analitzar el **model de llicenciament per nucli (core)** de Windows Server 2025.
2. Calcular el **cost total** segons les dues opcions principals:
   - **Standard**
   - **Datacenter**
3. Determinar quin tipus de **CAL** (*User vs Device*) és més econòmic per a l’empresa.
4. Justificar la **decisió final** basant-se en:
   - Costos
   - Escalabilitat futura
   - Funcionalitats (Storage Spaces Direct, SDN, etc.)
5. **Presentació al client**: crear una presentació de **5–10 minuts** on s’expliqui la solució de forma clara per a un perfil **no tècnic** (el gerent de TransLògic).

## Materials i enllaços de suport

- **UD6.AA1. Introducció a Windows Server**  
  Moodle 0224 SOX
- **Microsoft – Preus i llicències de Windows Server**  
  [link] [link] [link] [preus]

