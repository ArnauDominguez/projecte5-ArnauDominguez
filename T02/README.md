# T02: Control de versions. Treballant amb git

De moment hem gestionat el control de versions usant directament el repositori des de la web de **GitHub**. Tot i que ens ha solucionat força problemes, és evident que aquesta metodologia té unes quantes limitacions:

- **Lentitud a l’hora d’editar**. L’editor web no és tan versàtil com un editor local, ja sigui de codi com **Visual Studio Code** o un editor de **Markdown** específic com **Ghostwriter**.
- **Dificultat a l’hora de gestionar el repositori**. Afegir arxius i carpetes pot ser força feixuc i requereix accions poc eficients.

Per aquest motiu, començarem a treballar de la forma que es fa en el món real: combinant el **control de versions local amb git** amb un gestor de **repositoris remots**, en aquest cas, **GitHub**. No són les úniques solucions, sobretot a nivell remot, on hi ha alternatives com **Bitbucket**, **GitLab**, etc.

De fet, **git** va aparèixer abans que **GitHub**, com un protocol de control de versions **descentralitzat** que va trencar amb el model de control de versions centralitzat que imperava fins aquell moment. Va ser creat per **Linus Torvalds**, el creador de **Linux**.

## Com hi treballarem?

En el nostre cas, partirem sempre d’un **repositori a GitHub**. El primer pas serà tenir una **còpia sincronitzada en local**, per exemple al disc del PC.

A partir d’aquí:
- Els canvis es faran sempre **en local**, seguint el flux **`git add` → `git commit`**.
- Cada cop que deixem la feina, **pugem els canvis a GitHub** amb un **`git push`**.
- Quan ens hi tornem a posar, amb un **`git pull`** ens assegurem de tenir en local els últims canvis.  
  Això és especialment important si ens movem d’ordinador o treballem tant des del PC de l’escola com des de casa.

## Materials i enllaços de suport

- [Introducció a GitHub](https://github.com/SMX2n/IntroGitHub)
- [Guia Control de Versions](https://github.com/SMX2n/ControlVersions)

