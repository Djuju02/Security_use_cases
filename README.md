# YOLO Mine Detection Project

## Contexte / Context

**Français** : Ce projet utilise un modèle pré-entrainé YOLO pour détecter des mines terrestres. Afin d'améliorer les performances de l'algorithme dans des conditions environnementales dégradées, des filtres simulant la neige, le brouillard et d'autres phénomènes météorologiques ont été ajoutés aux données d'entraînement.

**English** : This project utilizes a pre-trained YOLO model for landmine detection. To enhance the algorithm's performance in degraded environmental conditions, filters simulating snow, fog, and other weather phenomena have been added to the training data.

## Installation et Préparation / Installation and Setup

### Prérequis / Prerequisites

**Français** :
- Python 3.8+
- Pip
- OpenCV
- PyTorch
- Jupyter Notebook
- Git

**English**:
- Python 3.8+
- Pip
- OpenCV
- PyTorch
- Jupyter Notebook
- Git

---

### Étapes d'installation / Installation Steps

**Français** :

1. **Clonez le dépôt GitHub** :
   ```bash
   git clone https://github.com/votre-utilisateur/votre-repo.git
   cd votre-repo
   ```

2. **Installez les dépendances Python** :
   ```bash
   pip install -r requirements.txt
   ```

3. **Téléchargez le modèle pré-entraîné** :
   - Visitez le lien suivant pour télécharger le modèle : [Modèle YOLO Mine Detection](https://universe.roboflow.com/hassan-sdqop/mine-detection-tupvk)
   - Extrayez le fichier ZIP dans le répertoire du projet (par exemple : `./model/`).

4. **Lancez Jupyter Notebook** :
   ```bash
   jupyter notebook
   ```

5. **Chargez et exécutez le fichier notebook** :
   - Ouvrez le fichier `Notebook_Group34.ipynb`.
   - Configurez les chemins pour les données et le modèle dans le notebook.

6. **Ajoutez des filtres météorologiques** :
   - Utilisez OpenCV pour appliquer les filtres de neige et brouillard.
   - Ces fonctions sont incluses dans le notebook, dans les sections dédiées à la prétraitement des images.

**English** :

1. **Clone the GitHub repository**:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```

2. **Install Python dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Download the pre-trained model**:
   - Visit the following link to download the model: [YOLO Mine Detection Model](https://universe.roboflow.com/hassan-sdqop/mine-detection-tupvk)
   - Extract the ZIP file into the project directory (e.g., `./model/`).

4. **Launch Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```

5. **Load and run the notebook file**:
   - Open the file `Notebook_Group34.ipynb`.
   - Set up the paths for the data and the model in the notebook.

6. **Add weather filters**:
   - Use OpenCV to apply snow and fog filters.
   - These functions are included in the notebook, in sections dedicated to image preprocessing.

---

## Utilisation / Usage

**Français** :

1. **Chargement des données** : Assurez-vous que les images sont dans le dossier `./data/images/`.
2. **Ajout de filtres** : Modifiez les images avec des filtres pour simuler des conditions dégradées.
3. **Entraînement** : Exécutez les cellules d'entraînement dans le notebook.
4. **Évaluation** : Vérifiez les performances du modèle en utilisant des ensembles de données modifiés et non modifiés.

**English**:

1. **Load the data**: Ensure that images are in the `./data/images/` folder.
2. **Add filters**: Modify the images with filters to simulate degraded conditions.
3. **Training**: Run the training cells in the notebook.
4. **Evaluation**: Check the model's performance using both modified and unmodified datasets.

---

## Arborescence du projet / Project Structure

```plaintext
.
├── Notebook_Group34.ipynb  # Main Jupyter Notebook
├── model/                  # Folder for the YOLO model
├── data/
│   ├── images/            # Training images
│   └── labels/            # Corresponding labels
├── filters/               # Weather filters implemented
├── requirements.txt       # Python dependencies
└── README.md              # This file
```

---

## Contribution / Contribution

**Français** :
Les contributions sont les bienvenues. Veuillez ouvrir une pull request ou signaler un problème.

**English**:
Contributions are welcome. Please open a pull request or report an issue.

---

## Licence / License

**Français** : Ce projet est sous licence MIT.

**English**: This project is licensed under the MIT License.

