# T05: Instal·lació del domini

## Introducció

Com a continuació de la tasca anterior, cal desplegar el **Directori Actiu** sobre la màquina virtual amb l’objectiu de practicar el posterior desplegament en el client.

A més, aquest procediment ha de servir com a **prova de concepte (PoC)** per mostrar als responsables de **TransLògic**, i així poder ajustar les configuracions a les necessitats reals del client.

## Procediment a documentar

- Instal·lar els **rols necessaris** al servidor.

- Crear un **domini nou en un bosc nou** amb el nom:
  - `translogicXX.test`  
    (on `XX` correspon al vostre número de llista)

- Establir el **nivell funcional** a **Windows Server 2025**.

- Promocionar el servidor com a **controlador de domini**:
  - És **important documentar la pantalla de resum** del procés.

- Gravar en un arxiu l’**script PowerShell** que permet automatitzar el procés.

- Un cop finalitzat tot el procediment, **copiar l’script PowerShell** a la carpeta del repositori que esteu utilitzant.  
  Podeu fer-ho mitjançant diferents mecanismes:
  - Còpia mitjançant **USB**
  - Enviament per **Internet** (correu, Drive o serveis com *FileTransfer*)
  - Còpia mitjançant **scp**  
    *(cal tenir el servei SSH instal·lat a Windows Server)*

## Materials i links de suport

- **Guia UD6.AA3 – Instal·lació DC**  
  *[Moodle SOX]*

