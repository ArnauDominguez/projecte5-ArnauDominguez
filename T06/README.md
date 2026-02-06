# T06: Configuració del domini

## Introducció

Un cop tenim ja el nostre **domini creat**, el següent pas és **desplegar-lo**, és a dir, crear els diferents objectes que el formen: **grups, usuaris i màquines**.  
En aquesta tasca veurem la utilitat d’organitzar els objectes mitjançant **Unitats Organitzatives (OU)** per mantenir una estructura clara, escalable i fàcil de gestionar.

## Procediment pràctic

### 1. Estructura d’unitats organitzatives (OU)

- Crear una **estructura d’OU coherent**.
- Justificar la decisió presa segons criteris d’organització, seguretat i administració.

### 2. Definició de grups

Definir la següent estructura de grups:

- **gestio**
- **magatzem**
- **gerencia**
- **personal**  
  > Tots els grups anteriors han de ser **membres d’aquest grup**.

### 3. Plantilles d’usuari

Crear una **plantilla d’usuari** per a cadascun dels grups següents:

- **Gestio**
- **Magatzem**
- **Gerencia**

Cada plantilla ha de tenir:
- Definida la **pertinença al grup corresponent**
- Configurada la **creació automàtica de la carpeta personal**

### 4. Usuaris de prova

- Definir **un usuari de prova** per a cadascuna de les plantilles creades.

### 5. Aprovisionament d’equips

- Crear una **OU d’equips**.
- Aprovisionar un equip amb el nom **PC1** dins d’aquesta OU.

### 6. Màquina virtual client

- Crear una **VM amb Windows 11** amb les característiques següents:
  - **4 GB de RAM**
  - **Disc suficient**
  - Xarxa en **mode NAT**
- Un cop creada la màquina, **afegir-la al domini**.

### 7. Verificació del funcionament

- Comprovar el correcte funcionament del domini:
  - Iniciar sessió a l’equip client (**PC1**) amb els **tres usuaris de prova**.
  - Verificar l’accés correcte i la creació de la **carpeta personal**.

## Materials i enllaços de suport

- **UD6.AA3 Desplegament**  
  Moodle 0224 SOX

