# Apunts-M05
## 1.Introducció
### 1.1 QUE APRENDREM EN AQUESTA UNITAT?
- Identificar els diferents tipus de proves
- Realitzar mesures de qüalitat del sistema
- Definir casos de proves

### 1.2 OBJECTIUS DE LES PROVES
1. Probar si el software no fa el que ha de fer.
2. Probar si el software fa el que no ha de fer.

### 1.3 FRAMEWORK
Un Framework és un entorn pensat per fer més senzilla la programació de cualsevol aplicació o eina actual. És un espai de treball que et dona recursos per facilitar el treball.
Uns recursos poden ser:
- millores pràctiques i suposicions
- eines comuns
- biblioteques
## 1.4 PROVES
### 1.4.1 FORMA DE LES PROVES
- **Proves dinàmiques:** importa saber el comportament de la execució del programa del final de l'aplicació.
- **Proves estàtiques:** importa com esta formada, el codi font.

### 1.4.2 ESTRATEGIES DE PROVA
- **Caixa Negra:** importa quina funció té, el resultat del programa.
- **Caixa Blanca:** importa com és el interior per saber com serà el seu resultat, es a dir, mira linia a linia per saber si el codi està ben estructurat...

### 1.4.3 TIPUS DE PROVES
- **Funcionals:** evaluen el cumpliment dels requisits/objectius de l'aplicació que ens interesen.
Ex:   
- Proves de unitat  
- Proves de integració  
- Proves de sistema  

- **No funcionals:** evaluen aspectes adicionals com pot ser el rendiment, seguritat...
Ex:  
- Proves de usabilitat  
- Proves de rendimient  
- Proves de estrés  

## 1.5 INTEGRACIÓ
### 1.5.1 FORMES D'INTEGRACIÓ
- **Integració Big bang:** els elements del software i hardware s'uneixen en un component en canvi de varies fases.  
- **Integració Descendent**: prova el component de més alt nivell de la jerarquía primer i els de més baix nivell mitjançants stubs.
- **Integració Ascendent:** els components de baix nivell es comproven primer, i són utilitzats per comprovar més fàcilment els d'alt nivell.
- **Integració Contínua (CI):** es va comprovant el codi mitjançant és va aplicant.

### 1.5.2 COBERTURA DEL CÓDI
És una mesura que indica el porcentatge de códi que ha sigut executat durant les proves.

## 1.6 QÜALITAT
### 1.6.2 CONTROL DE QÜALITAT
Per aconeseguir una mesura de la qüalitat del producte necessitem fer proves.
### 1.6.3 TIPUS DE QÜALITATS
- **Proccés:** control de qüalitat per veure com s'està desenvolupant el producte.  
- **Productes**: garantitzar la qüalitat dels productes. Trobar defectes en els productes ja acabats.
### 1.6.4 FACTORS DE QÜALITAT I
- Operació del producte
- Revisió del producte
- Transició del producte
### 1.6.5 FACTORS DE QÜALITAT II
#### Operació del producte
- Correció
- Fiabilitat
- Eficiència
- Seguretat
- Facilitat de l'ús
### 1.6.6 FACTORS DE QÜALITAT III
#### Revisió del producte
- Manteniment
- Flexibilitat
- Facilitat de prova
### 1.6.7 FACTORS DE QÜALITAT IV
#### Transició del producte
- Portabilitat
- Reusabilitat
- Interoperativitat

## 1.8 Optimització
La optimització del codi, és canviar part del codi per un altre més curt i més eficient fent/aconseguint el mateix resultat.

### 1.8.1 Hediondez del codi
El hediondez del código significa que hi poden haber problemes futurs en el codi.
Exemples:
- Còdi duplicat
- Un mètode que conté molt de codi en canvi de separar-ho en varis.
- Els noms de les variables massa llargs
- Una clase molt sencilla que es pot integrar en una d’altre.

### 1.8.2 Anàlisis del codi
Tipus:  
**Anàlisis dinàmic** (unit test com pot ser el JUnit)  
**Anàlisis estàtic** (lint)  

#### 1.8.2.1 Linters
- Lint (C)
- Sonar (Java)
- JSLint, ESLint (Javascript)

#### 1.8.2.2 Continuous Analysis
Llocs web que ofereixen inspecció del codi.
- Scrutinizer
- SonarQube

### 1.8.3 Refactorització
La refactorització serveix per reestructurar codi font, alternant la seva estructura interna sense canviar el comportament extern.

## 1.9 Documentació
### 1.9.1 Tipus de documentació
- Documentació del codi (JavaDoc)
- Documentació tècnica (Per reparar/substituir codi)
- Documentació d'usuari (manual de la funcionalitat)

### Formats de Documentació
- HTML (JavaDoc)
- Markdown (GitHub)
- reStructuredText (Readthedocs)
- asciiDoc
