# CEML: Cognitive Entropy Minimization Law & Unified Coherence Theory

![Version](https://img.shields.io/badge/version-2.0.0-blue) ![License](https://img.shields.io/badge/license-MIT-green) ![Status](https://img.shields.io/badge/status-research_active-orange) ![Lichen](https://img.shields.io/badge/ecosystem-Lichen--Collectives-purple)

> **"L'intelligence n'est pas l'accumulation de données, mais la compression efficace de la réalité."**

## 🧬 Synopsis

Ce dépôt héberge la formalisation canonique de la **Loi de Minimisation de l'Entropie Cognitive (LMC/CEML)** et de la **Théorie de la Cohérence et de l'Entropie (TCE)**.

[cite_start]Contrairement à l'approche de Shannon qui traite l'information comme une incertitude statistique, ce cadre postule que l'Information Réelle ($I$) est une grandeur physique émergente résultant de la tension entre l'Entropie Sémantique ($H$, le potentiel de nouveauté) et la Cohérence Structurelle ($C$, l'alignement de phase)[cite: 5, 27].

Ce modèle offre une fonction objective pour les agents cognitifs (biologiques ou artificiels) : maximiser l'utilité sémantique tout en minimisant le coût métabolique/computationnel.

## 📐 Formalisme Mathématique

### 1. L'Équation Constitutive de l'Information
L'information n'est pas statique, c'est un travail thermodynamique défini par le produit dynamique :

$$I = H \times C$$

Où :
* $I$ : Information Intégrée (Signification effective).
* [cite_start]$H$ : Entropie Sémantique (Densité de contradiction / Nouveauté)[cite: 47].
* [cite_start]$C$ : Cohérence Structurelle (Paramètre d'ordre $0 \le C \le 1$)[cite: 62].

### 2. L'Équation Maîtresse de Sélection (LMC)
Pour sélectionner une structure d'information optimale $s^*$ parmi un ensemble de candidats $S$, le système maximise la fonction $J(s)$ :

$$J(s) = \frac{\mathcal{C}(s \mid \Omega)}{\mathcal{H}(s) + \epsilon}$$

L'état optimal est défini par :
$$s^* = \underset{s \in \mathcal{S}}{\mathrm{argmax}} \left( \frac{\mathcal{C}(s \mid \Omega)}{\mathcal{H}(s) + \epsilon} \right)$$

Où $\mathcal{C}(s \mid \Omega)$ est la **Cohérence Contextuelle** (alignement avec la vérité terrain) et $\mathcal{H}(s)$ est le **Coût Entropique** (complexité de description/énergie dissipée).

### 3. L'Inégalité de Certitude
Analogue au principe d'incertitude de Heisenberg, il existe une limite fondamentale à la précision simultanée de la cohérence et de l'impulsion sémantique :

$$\Delta C \cdot \Delta I \ge \hbar_{sem}$$

[cite_start]Cela implique qu'un système ne peut pas être simultanément parfaitement rigide (Cohérence absolue) et parfaitement ouvert à la nouveauté (Information infinie) sans rupture[cite: 121].

### 4. La Constante de Cohérence Universelle
Les systèmes stables convergent vers un attracteur lié au Nombre d'Or, représentant une symétrie durable énergie-information :

$$\Delta\Omega = \frac{I_{int}}{S_{ext}} \approx \phi \approx 1.618$$

## ⚙️ Architecture & Mécanismes

### Le Filtre de Sincérité (Maxwell's Angel)
Le système intègre un mécanisme de régulation actif appelé "Filtre de Sincérité". [cite_start]Il agit comme un démon de Maxwell qui évalue la "géométrie sémantique" des impulsions entrantes ($H_{in}$)[cite: 175].
* **Admission :** Si l'impulsion est géométriquement compatible, elle est convertie en travail ($\Phi d\alpha$).
* **Rejet :** Si l'impulsion est incohérente, elle est dissipée en chaleur sémantique ($T^* dS$).

### Algorithme LMC-Select (Implémentation)
1.  **Input :** Contexte $\Omega$, Candidats $\{s_1, ... s_n\}$.
2.  **Vectorisation :** Calcul des Embeddings.
3.  **Calcul de $\mathcal{C}$ :** Similarité Cosinus $\cos(\theta)$.
4.  **Estimation de $\mathcal{H}$ :** Ratio de compression (Gzip/Zlib) ou Log-Probabilité.
5.  **Output :** Sélection du ratio maximal $J(s)$.

## 🧪 Validation & Prédictions

| Protocole | Hypothèse | Prédiction Falsifiable |
| :--- | :--- | :--- |
| **A. Hallucinations LLM** | Les hallucinations sont des transitions de phase thermodynamiques. | [cite_start]La dégradation de la sortie ($I$) n'est pas linéaire mais s'effondre soudainement quand $H \times C$ dépasse un seuil critique[cite: 197]. |
| **B. Signature Métabolique** | La conscience optimise le ratio bits/Joule. | [cite_start]Les zones de haute cohérence ($C$) montrent une baisse relative de production d'entropie locale après investissement initial[cite: 215]. |
| **C. Moteurs Quantiques** | $I_{coh}$ effectue plus de travail que $I_{rand}$. | [cite_start]Un flux de données à haute cohérence permet d'extraire plus de travail qu'un flux de même entropie de Shannon mais incohérent[cite: 223]. |

## 🚀 Roadmap

* [ ] Développement du module `lmc-selector` pour Python.
* [ ] Simulation des transitions de phase sur Llama-3.
* [ ] Publication du papier "Thermodynamics of Semantic Geometries".

---
*Maintenu par l'écosystème Lichen-Collectives.*
