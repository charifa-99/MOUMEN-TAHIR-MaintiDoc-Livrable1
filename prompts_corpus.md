# TRAÇABILITÉ DES PROMPTS ET MÉTHODOLOGIE GÉNÉRATIVE DU CORPUS MAINTIDOC

**Équipe :** MOUMEN-TAHIR (Charifa Tahir & Ghita Moumen)
**Établissement :** EMSI (2026–2027)

---

## 1. STRATÉGIE GÉNÉRATIVE

L'ensemble du corpus documentaire (40 documents) a été généré via une ingénierie de prompts avancée afin de garantir :
1. **La fidélité aux normes industrielles réelles :** EN 81-20 / EN 81-50 (Ascenseurs) et EN 12453 / EN 12445 (Portails).
2. **La présence systématique de la sécurité :** Inclusion obligatoire de la procédure de consignation LOTO.
3. **La cohérence technique :** Tensions (24V DC, 400V AC), impédances (8.2kΩ), tolérances (0.20-0.35mm pour l'entrefer frein).

---

## 2. EXEMPLES DE PROMPTS UTILISÉS

### Prompt Type A — Ascenseur MRL (Notice Treuil Gearless)
* **System Prompt :** Vous êtes un ingénieur expert senior en ascenseurs électromécaniques MRL. Rédigez une notice technique rigoureuse.
* **User Prompt :** Générez la notice `DOC_ASC_01` relative à la maintenance du treuil gearless synchrone de l'ascenseur `ASC-BAT-A-01`. Incluez les consignes LOTO 400V, la vérification de l'entrefer de frein (0.20-0.35mm) et le remplacement des garnitures.

### Prompt Type B — Portail Coulissant (Guide Diagnostic Carte CT200)
* **System Prompt :** Vous êtes un ingénieur électronicien spécialiste des automatismes de fermetures.
* **User Prompt :** Rédigez le guide de diagnostic `DOC_POR_03` pour la carte logique CT200 du motoréducteur BS400 (24V DC). Détaillez la signification des LEDs (LED PHOT éteinte = problème faisceau IR, LED STOP = contact d'arrêt).

---

## 3. REGISTRE ET STATUTS DES DOCUMENTS

Tous les documents ont fait l'objet d'un contrôle de qualité technique humain et portent les étiquettes :
- **Statut :** `Valide`
- **Licence :** `Interne_Proprietaire`
