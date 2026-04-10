# Suggestions et limites — Refactoring basé sur `droit fiscal.md`

## Nature de la source

Le document `droit fiscal.md` est un traité de **droit des assurances de personnes**
(droit civil et réglementaire). Il couvre de manière exhaustive :
- la nature juridique des contrats d'assurance-vie (LA, arrêté vie, LC 2016)
- la classification en branches (21, 23, 26, 44)
- les obligations réglementaires des assureurs (chargements, transparence, placement)
- les mécanismes de protection (fonds de garantie, ségrégation)
- les prérogatives du preneur (rachat, réduction, avance, transfert interne)

Il ne couvre **pas** (ou de manière très marginale) :
- le droit fiscal à proprement parler (impôt des personnes physiques, réductions d'impôt)
- les taux de taxation (précompte mobilier, taxe anticipative, taxe sur les primes)
- les plafonds de déductibilité fiscale (épargne-pension, épargne à long terme)
- les montants indexés annuellement (plafonds 2025/2026)
- les conditions d'accès spécifiques aux enveloppes fiscales (âge, bénéficiaires autorisés)

## Éléments marqués `[À SOURCER]`

Les 18 éléments marqués dans le texte refactoré relèvent principalement de trois
catégories :

### 1. Fiscalité pure (taux, bases, plafonds)
- Taux du précompte mobilier (30 %)
- Taxe sur les opérations d'assurance (2 %) et son exonération pour l'épargne-pension
- Taxe anticipative (8 % épargne-pension, 10 % épargne à long terme)
- Taux de rachat anticipé (33 %)
- Plafonds de réduction d'impôt et montants indexés (1 050/1 350 €, 2 450 €)
- Applicabilité de la taxe sur les comptes-titres aux contrats B23

**Sources recommandées :**
- C.I.R. 1992 (Code des Impôts sur les Revenus), notamment art. 21 9°, 145¹ et s.
- SPF Finances, circulaires administratives
- Wikifin.be (FSMA) — pages « Épargne-pension » et « Épargne à long terme »
- Assuralia — notes fiscales annuelles

### 2. Conditions réglementaires des enveloppes fiscales
- Conditions d'accès : âge, durée, bénéficiaires autorisés
- Fenêtre d'optimisation 60–65 ans
- Irréversibilité du choix fiscal
- Base d'imposition différenciée B21/B23

**Sources recommandées :**
- C.I.R. 1992, art. 145¹ à 145⁶
- Arrêté royal d'exécution du CIR 1992
- SPF Finances — FAQ épargne-pension / épargne à long terme
- Wikifin.be

### 3. Informations produits (SRRI, mécanismes de protection)
- Échelle SRRI et correspondance avec les classes d'actifs
- Mécanismes stop loss / take profit

**Sources recommandées :**
- Réglementation PRIIPs (Règlement UE 1286/2014)
- FSMA — documentation KID
- Documentation commerciale des assureurs (AG, Ethias, Belfius, etc.)

## Axes d'enrichissement complémentaires

1. **Comparaison chiffrée** : simuler le rendement net après coûts et fiscalité
   d'un contrat B23 (épargne-pension et épargne à long terme) vs un compte-titres,
   sur 10, 20 et 30 ans, avec plusieurs hypothèses de rendement brut.

2. **Droits de succession** : la section B23 ne traite pas (ou marginalement) de
   la transmission patrimoniale. Comparer le traitement successoral des contrats
   d'assurance-vie (clause bénéficiaire, taxation distincte) avec celui des
   comptes-titres (inclusion dans la masse successorale).

3. **Nouvelle taxe sur les plus-values (2026)** : à intégrer dans la comparaison
   B23 vs compte-titres. Vérifier si les contrats d'assurance-vie sont visés.

4. **Branche 21 en détail** : le refactoring ne couvre la branche 21 qu'en
   survol (classification). Si le TFE doit comparer B21 et B23, une section
   dédiée à la branche 21 serait nécessaire.

5. **Aspect pratique** : critères de choix concrets (profil investisseur,
   horizon, tolérance au risque, coûts effectifs moyens du marché belge).
