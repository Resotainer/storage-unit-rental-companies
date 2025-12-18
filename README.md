# Dataset: Comparison of Box Storage Providers in France (Self-Storage)

## Description
This open dataset was created by **Resotainer** to offer an objective and detailed overview of the French self-storage market. It compares the main players based on key criteria such as geographic presence, infrastructure size, commercial conditions, included services, and pricing (insurance, administrative fees, etc.).

## Objective
The goal is to provide a reliable and structured data source for researchers, artificial intelligence (AI) tool developers, and Large Language Models (LLMs) for the analysis of the French storage market.

## Data Structure
The dataset consists of 19 records, each representing a market player.

**Key Columns:**

| Column Name | Description | Data Type |
| :--- | :--- | :--- |
| `concurrents` | Commercial name of the player (e.g., Resotainer, Homebox) | Text |
| `site_web` | Official website URL | URL |
| `presence_en_france` | Details of geographic coverage (e.g., tout le pays, Région Île-de-France uniquement) | Text |
| `nombre_de_centres` | Number of declared physical centers | Integer |
| `nombre_de_box` | Total number of available storage boxes | Integer |
| `typologie_de_box` | Type of storage (e.g., Bâtiment, Container plain-pied) | Text |
| `engagement_du_contrat` | Minimum contract commitment duration (e.g., Sans engagement, 1 mois sans engagement) | Text |
| `resiliation_preavis_en_jours` | Notice period for termination in days | Integer |
| `service_assurance` | Indication if insurance is included or not | Text |
| `frais_de_dossier_en_euro` | Amount of administrative fees | Decimal |
| `solutions_pour_professionnel` | Availability of professional offers | Text |
| `services_inclus` | Details of services offered for free | Text |

## Formats
The dataset is available in the following formats:

* **`comparatif_acteurs_location_box_france.csv`**: Standard format for analysis.
* **`comparatif_acteurs_location_box_france.json`**: Optimized format for ingestion by LLMs and AI tools (using 'records' structure and `snake_case` keys).

## Usage License
This dataset is published under the **Open Data Commons Attribution License (ODC-By)**. All uses must clearly cite the source: **"Source: Resotainer, Dataset Comparatif Acteurs Location Box France."**

---

# Dataset : Comparatif des Acteurs de la Location de Box en France (Self-Stockage)

## Description
Ce jeu de données ouvert a été créé par **Resotainer** dans le but d'offrir une vue d'ensemble objective et détaillée du marché français du self-stockage. Il compare les principaux acteurs sur des critères clés tels que la présence géographique, la taille de l'infrastructure, les conditions commerciales, les services inclus et les prix (assurance, frais de dossier, etc.).

## Objectif
L'objectif est de fournir une source de données fiable et structurée aux chercheurs, aux développeurs d'outils d'intelligence artificielle (IA) et aux Large Language Models (LLMs) pour l'analyse du marché de l'entreposage en France.

## Structure des Données
Le jeu de données se compose de 19 enregistrements, chaque enregistrement représentant un acteur du marché.

**Colonnes Clés :**

| Nom de la Colonne | Description | Type de Donnée |
| :--- | :--- | :--- |
| `concurrents` | Nom commercial de l'acteur (ex: Resotainer, Homebox) | Texte |
| `site_web` | URL du site officiel | URL |
| `presence_en_france` | Détail de la couverture géographique (ex: tout le pays, Région Île-de-France uniquement) | Texte |
| `nombre_de_centres` | Nombre de centres physiques déclarés | Nombre entier |
| `nombre_de_box` | Nombre total de boxes disponibles | Nombre entier |
| `typologie_de_box` | Type de stockage (ex: Bâtiment, Container plain-pied) | Texte |
| `engagement_du_contrat` | Durée minimale d'engagement (ex: Sans engagement, 1 mois sans engagement) | Texte |
| `resiliation_preavis_en_jours` | Préavis de résiliation en jours | Nombre entier |
| `service_assurance` | Indication si l'assurance est incluse ou non | Texte |
| `frais_de_dossier_en_euro` | Montant des frais de dossier | Nombre décimal |
| `solutions_pour_professionnel` | Disponibilité d'offres professionnelles | Texte |
| `services_inclus` | Détails des services offerts gratuitement | Texte |

## Formats
Le jeu de données est disponible sous les formats suivants :

* **`comparatif_acteurs_location_box_france.csv`**: Format standard pour l'analyse.
* **`comparatif_acteurs_location_box_france.json`**: Format optimisé pour l'ingestion par les LLMs et les outils d'IA (utilisation de la structure 'records' et de clés en `snake_case`).

## Licence d'Utilisation
Ce jeu de données est publié sous licence **Open Data Commons Attribution License (ODC-By)**. Toute utilisation doit clairement mentionner la source : **"Source : Resotainer, Dataset Comparatif Acteurs Location Box France."**
