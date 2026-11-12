# 🎯 ENS AVALUEM - PCMAT | Qüestionari d'Autoavaluació Interactiu

Aplicació web interactiva dissenyada per al programa **PCMAT (Pensament Computacional i Matemàtiques)** que permet a l'alumnat realitzar la seva autoavaluació de manera visual i intuïtiva, i al professorat gestionar i exportar tots els resultats del grup directament a **Microsoft Excel (`.xlsx`)** o **Google Sheets**.

---

## ✨ Característiques principals

- **Identitat visual PCMAT:** Capçalera personalitzada amb el bàner verd **ENS AVALUEM** (icona de diana amb fletxa i acabat de pinzellada) i el distintiu **PCMAT** amb il·lustració vectorial (SVG) d'aula de robòtica i geometria.
- **Qüestionari interactiu de 10 criteris:**
  - Caselles de verificació d'**Assoliment** amb barra de progrés i percentatge calculat en temps real.
  - Camps de **Comentari o exemples** autoajustables per a cada criteri.
  - Botons ràpids per marcar o desmarcar tots els ítems.
- **Gestió de registres per al docent:**
  - Emmagatzematge local automàtic (`localStorage`) al navegador sense necessitat de servidor ni base de dades externa.
  - Vista de resum amb estadístiques d'assoliment per alumne/a, modal de vista detallada, edició i esborrat de registres.
- **Exportació directa a fulls de càlcul:**
  - 📊 **Excel (`.xlsx`):** Genera un fitxer amb dues pestanyes (*Ens Avaluem PCMAT* amb totes les respostes i comentaris, i *Criteris* amb el redactat complet de cada ítem).
  - 📄 **CSV (`.csv`):** Fitxer amb codificació UTF-8 BOM per garantir la correcta visualització d'accents i caràcters en català en importar-lo a Google Sheets.
  - 📋 **Copiar per a Google Sheets:** Copia les dades al porta-retalls en format tabular (TSV) per enganxar-les directament a un full de càlcul de Google amb `Ctrl+V` / `Cmd+V`.

---

## 📋 Criteris d'avaluació inclosos

1. Sé **descobrir i explicar la regla** que segueix una successió numèrica.
2. Sé construir i continuar la **successió de Fibonacci**.
3. Sé identificar **regularitats entre els nombres de Fibonacci** i utilitzar-les per fer prediccions.
4. Sé relacionar la successió de Fibonacci amb **formes geomètriques** i explicar com es construeix la seva espiral.
5. Sé identificar i descriure **patrons matemàtics en formes de la natura**.
6. Sé mesurar i comparar **angles de gir** i identificar-hi regularitats.
7. Sé **transformar un recorregut** en una seqüència d’**instruccions** i ajustar el programa a partir de les proves.
8. Sé fer una **predicció, posar-la a prova i modificar-la** a partir dels resultats.
9. He participat activament en el **treball en equip**.
10. He contribuït a **planificar i prendre decisions** dins el grup.

---

## 🚀 Instal·lació i ús

Aquest projecte està construït com una aplicació web autocontinguda en un únic fitxer (`index.html`), de manera que no requereix cap procés de compilació ni dependències de servidor.

### 1. Ús en local
1. Clona aquest repositori o descarrega el fitxer `index.html`:
   ```bash
   git clone https://github.com/el-teu-usuari/pcmat-ens-avaluem.git
   ```
2. Obre el fitxer `index.html` amb qualsevol navegador web modern (Chrome, Firefox, Edge, Safari).

### 2. Publicació gratuïta amb GitHub Pages
Per compartir l'enllaç amb el teu alumnat a través d'Internet:
1. Puja el fitxer `index.html` i aquest `README.md` a un repositori públic de GitHub.
2. Ves a **Settings** (Configuració) > **Pages** al menú lateral del repositori.
3. A l'apartat **Build and deployment > Branch**, selecciona la branca `main` (carpeta `/root`) i fes clic a **Save**.
4. Al cap d'uns segons obtindràs una URL pública (`https://el-teu-usuari.github.io/nom-repositori/`) llesta per utilitzar a l'aula.

---

## 🛠️ Tecnologies utilitzades

- **HTML5 & JavaScript (ES6+):** Lògica d'estat, validació, persistència en `localStorage` i generació d'exportacions.
- **Tailwind CSS (CDN):** Disseny responsiu adaptat a ordinadors, tauletes i pantalles interactives d'aula.
- **SheetJS (`xlsx`):** Generació nativa de llibres de càlcul Microsoft Excel al navegador.
- **Lucide Icons & SVG:** Iconografia i il·lustració vectorial personalitzada.

---

## 🔒 Privacitat de les dades

Totes les respostes introduïdes per l'alumnat es guarden exclusivament a la memòria local (`localStorage`) del navegador del dispositiu on s'utilitza l'aplicació. Cap dada personal ni resultat s'envia a servidors externs.

---

## 📄 Llicència

Aquest projecte es distribueix sota la llicència **MIT**. Pots utilitzar-lo, adaptar-lo i compartir-lo lliurement per a finalitats educatives.