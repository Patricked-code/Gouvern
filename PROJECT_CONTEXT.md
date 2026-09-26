# PROJECT_CONTEXT

- Repository: Patricked-code/Gouvern
- Project: Gouvern
- Owner: @Patricked-code
- Canonical branch: main
- Baseline subject HEAD: 3806a2c4f3a40aca28d34a00a77b2ad1be3e80f0
- First governed agent: ChatGPT via CHATGPT

## Mission

Créer une application web permettant d’obtenir, centraliser, organiser et consulter les données statiques ainsi que les documents des OPCVM africains, à partir de sources officielles ou vérifiables, en conservant l’identité des fonds, leurs caractéristiques de référence et les documents associés.

## Scope

### In scope
- Référencer les OPCVM africains par pays, régulateur, société de gestion et fonds
- Centraliser les données statiques de référence des fonds : identité, dénomination, codes/ISIN lorsqu’ils existent, catégorie, devise, société de gestion, dépositaire, pays, statut, dates et autres caractéristiques stables disponibles
- Collecter, cataloguer et rendre consultables les documents officiels ou vérifiables liés aux OPCVM : prospectus, notes d’information, fiches signalétiques, documents réglementaires, rapports, fiches produits et autres documents disponibles
- Conserver les URLs sources, métadonnées documentaires, dates, provenance et éléments permettant de vérifier l’origine de chaque donnée ou document
- Permettre la recherche, le filtrage et la consultation web des fonds, données statiques et documents
- Construire progressivement un catalogue de sources officielles ou vérifiables pour les pays africains

### Out of scope
- Valeurs liquidatives quotidiennes et autres séries temporelles dynamiques dans la première baseline
- Calcul de performance, risque, classement ou notation des fonds dans la première version
- Souscription, rachat, paiement ou exécution d’ordres sur OPCVM
- Gestion de portefeuille ou conseil en investissement
- Invention ou complétion automatique de données absentes des sources
- Suppression de la provenance ou des documents originaux après normalisation

## Architecture / stack

Profile selection: application. See docs/ARCHITECTURE.md.

## Infrastructure / deployment

Declared baseline status: NO_INFRASTRUCTURE_YET.

## External systems

- None declared

## Initial constraints

- Couvrir progressivement les OPCVM des pays africains
- Prioriser les données statiques et les documents dans la première version
- Utiliser des sources officielles ou suffisamment vérifiables
- Conserver la provenance, les URLs sources et les documents originaux lorsque cela est possible
- Ne jamais inventer ni compléter silencieusement une donnée absente
- Préserver la traçabilité entre fonds, données statiques, documents et sources
- Faire évoluer le projet sans contourner la gouvernance ni casser les garanties existantes

## Governed repository setup

Workflow model: STANDARD_GOVERNED_FLOW
MCP linked: True
Domain binding: {"mode": "UNRESOLVED"}
