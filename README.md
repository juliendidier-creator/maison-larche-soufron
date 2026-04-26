# Analyse — 50 av. Dr Paul Soufron, 19600 Larche

Page interactive d'aide à la décision pour l'achat de cette maison.

🔗 **Page en ligne :** https://juliendidier-creator.github.io/maison-larche-soufron/

## Contenu
- Simulateur de négociation (sliders prix / apport / durée / taux)
- Carte Leaflet des transactions DVF Larche 2021-2025
- Tableau triable des maisons vendues sur l'avenue
- Graphique de dispersion €/m² avec position du bien
- Comparables ciblés
- Risques naturels (PPRI Vézère, radon, argile)
- Checklist d'achat interactive (sauvegarde localStorage)
- Stratégie de négociation chiffrée
- Sources & liens utiles (pré-remplis pour Géorisques, etc.)

## Données sources
- **DVF géolocalisé** — data.gouv.fr (115 transactions Larche INSEE 19107, 2021-2025)
- **Annonce** — Leboncoin n°3176920773 (CONTACT IMMO Larche)
- **Marché** — Meilleurs Agents, PAP, Efficity, RealAdvisor (déc. 2025)

## Stack technique
Single-file HTML — Chart.js + Leaflet via CDN — pas de build, pas de backend.

## Usage local
```bash
npx serve . -l 8765
# ou
python3 -m http.server 8765
```
Puis ouvrir http://localhost:8765
