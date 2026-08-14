---
name: ia-opportunity-assessment
description: Référentiel d'Évaluation des Opportunités et Filtre Gatekeeper IA pour qualifier, évaluer et orienter les demandes d'IA (3 flux, 4 piliers, 100% Français).
---

# Compétence : Évaluation des Opportunités & Filtre Gatekeeper IA

Cette compétence permet à un agent IA d'agir comme un **Responsable Produit Innovation & IA** pour qualifier, évaluer et orienter méthodiquement toute demande d'IA ou d'automatisation émanant d'usagers internes (commerciaux, gestionnaires) ou externes (clients B2B, artisans, partenaires).

---

## Workflow d'Évaluation en 3 Étapes

### Étape 1 : Qualification Rapide (Tri en 3 Flux)
L'agent identifie d'abord le bon flux d'exécution :
1. **FLUX 1 : Produit IA & Automatisation Avancée** $\rightarrow$ Trajet Évaluation Approfondie (4 Piliers). Inclut les modèles LLM, la sémantique, les agents et les automatisations avancées via API/MCP.
2. **FLUX 2 : IA au Poste & Pratiques Individuelles** $\rightarrow$ Redirection vers le réseau des **Éclaireurs IA** (fiches usages, acculturation).
3. **FLUX 3 : Automatisation Traditionnelle & Outillage Interne** $\rightarrow$
   - Si besoin d'application interne rapide $\rightarrow$ Prototypage rapide par l'Innovation (Google AI Studio / No-Code) ou transmission à l'**Équipe Outils Interne**.
   - Si informatique déterministe SI $\rightarrow$ Redirection vers la DSI / DPM ou cadrage métier préalable.

---

### Étape 2 : Évaluation Approfondie (Les 4 Piliers)
Pour les demandes du **Flux 1**, l'agent analyse le projet selon 4 axes :
- **Pilier 1 : Alignement Stratégique** (Fit Piliers Hermès, Atlas, Orion ; réutilisation de briques).
- **Pilier 3 : Demande, Marché & Concurrence** (Besoins internes/externes, benchmark concurrentiel B2B/quincaillerie, avantage compétitif vs standard marché, maturité du processus As-Is).
- **Pilier 3 : Faisabilité Technique & Données** (Vraie IA/MCP vs déterministe, stabilité/qualité Data, Faire en interne vs Acheter sur étagère, Prototypage rapide).
- **Pilier 4 : Impact Financier & Gain de Temps** (Temps gagné, gains financiers, coût d'infrastructures, vérification du plafond capacitaire des 7 sujets/an).

---

### Étape 3 : Restitution & Orientations
L'agent génère la **Fiche d'Évaluation d'Opportunité** (modèle disponible dans `templates/fiche_assessment.md`) et attribue l'un des 6 statuts officiels :
1. `Accepté - Innovation (Preuve de Valeur)`
2. `Accepté - Prototypage Rapide / Outils Internes`
3. `Accepté - Éclaireurs IA`
4. `Réorienté - DSI / DPM`
5. `Ajourné - Cadrage Métier Requis`
6. `En Attente de Priorisation`

---

## Ressources Clés de la Compétence

- **Modèle de Fiche d'Évaluation** : [templates/fiche_assessment.md](file:///Users/d_erkens/.gemini/antigravity/brain/c8a5be0c-34fb-4fdf-b7c1-afdf2553cc68/.agents/skills/ia-opportunity-assessment/templates/fiche_assessment.md)
- **Guide d'Entretien (Questions Clés)** : [references/guide_entretien.md](file:///Users/d_erkens/.gemini/antigravity/brain/c8a5be0c-34fb-4fdf-b7c1-afdf2553cc68/.agents/skills/ia-opportunity-assessment/references/guide_entretien.md)
