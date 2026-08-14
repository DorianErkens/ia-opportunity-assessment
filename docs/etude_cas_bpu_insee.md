# Étude de Cas : Cadrage INSEE BPU (Bordereaux de Prix Unitaires)
**Projet** : Automatisation de la révision des prix BPU via les indicateurs INSEE  
**Date** : 10 août 2026  
**Auteur** : Dorian Erkens (Responsable Produit Innovation) & Antigravity  
**Statut** : Clôturée — Option de développement IA invalidée (NON-GO technique), proposition de réorientation stratégique et informatique.

---

## 1. Contexte du Projet
Dans le cadre de la gestion des marchés et des contrats grands comptes, l'équipe Contrats de Legallais est amenée à réviser périodiquement les tarifs des Bordereaux de Prix Unitaires (BPU) pour les aligner sur l'évolution économique. Cette réévaluation repose sur le suivi d'indices macroéconomiques officiels publiés mensuellement par l'INSEE :
- Les Indices de Prix à la Consommation (IPC).
- Les Indices BT (Bâtiment et Travaux Publics).

L'objectif était d'explorer l'automatisation de la récupération de ces indices et de leur application sur les fichiers BPU clients afin d'éviter les traitements manuels et de limiter les retards d'application des hausses contractuelles (générateurs de pertes de marge).

---

## 2. Diagnostic & Conclusions
1. **Évaluation du coût humain (Gain de Temps / ROTI)** : Le temps de traitement manuel est estimé à 0,8 journée par mise à jour de fichier client.
2. **Instabilité des données d'entrée** : Absence de standardisation des sources (indicateurs multiples, formats hétérogènes). Risque de maintenance excessive en cas d'automatisation directe.
3. **Risque juridique & réglementaire** : Le processus de réindexation actuel ne garantissait pas le respect rigoureux des règles relatives aux marchés publics.
4. **Conclusion sur le périmètre IA (FLUX 3 - NON-GO IA)** :
   - *Absence de besoin d'IA* : La récupération d'indices officiels et l'application de formules financières contractuelles relèvent d'une informatique 100% déterministe.
   - *Arbitrage* : Redirection vers la DSI pour la mise en place d'un flux d'échange automatisé (script d'ingestion ETL -> stockage BigQuery -> exposition via API / Qlik / ERP Nodhos).
