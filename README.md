# SecFrame

Site statique de référence sur les méthodologies de gouvernance, sécurité et gestion de projet :
COBIT 2019, ISO/IEC 27001, CAPM (PMI), PRINCE2, EBIOS Risk Manager et MITRE ATT&CK.

Chaque fiche présente une vue d'ensemble, un schéma SVG du référentiel et une méthode pas-à-pas
pour l'appliquer.

### 🔗 [Voir le site en ligne](https://cabaaji.github.io/secframe/)

## Ouvrir le site en local

Aucune dépendance n'est nécessaire : c'est du HTML/CSS/JS pur.

**Option 1 — directement dans le navigateur**
Double-cliquer sur `index.html` (ou l'ouvrir via `Fichier > Ouvrir` dans le navigateur).

**Option 2 — via un petit serveur local (PowerShell)**
```powershell
powershell -ExecutionPolicy Bypass -File serve.ps1
```
Puis ouvrir http://localhost:5500/ dans le navigateur.

## Structure

```
index.html              page d'accueil
assets/css/style.css    thème (charte graphique cybersécurité sobre)
assets/js/main.js       navigation (lien actif, menu mobile)
pages/                  une page par méthodologie
serve.ps1               serveur statique local de secours (si Node/Python indisponibles)
```
