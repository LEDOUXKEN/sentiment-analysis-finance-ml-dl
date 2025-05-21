# Analyse et Prédiction du Sentiment dans les Actualités Financières 

##  Introduction
Ce projet propose une approche de Machine Learning et Deep Learning pour automatiser l'analyse du sentiment dans les textes financiers.

##  Structure du Projet
- `data/` : Jeu de données prétraité
- `notebooks/` : Analyses exploratoires et entraînement des modèles
- `models/` : Sauvegarde du meilleur modèle optimisé
- `scripts/` : Code de prétraitement et prédiction en production

##  Technologies Utilisées
- **Traitement du texte** : `NLTK`, `Scikit-learn`, `TfidfVectorizer`
- **Machine Learning** : `Logistic Regression`, `SVM`, `Naive Bayes`
- **Deep Learning** : `TensorFlow`, `Keras (LSTM)`
- **Visualisation** : `Matplotlib`, `Seaborn`, `WordCloud`
<img width="418" alt="image" src="https://github.com/user-attachments/assets/1ebee85c-64ff-4a1e-bc15-5d955276e6e6" />
<img width="536" alt="image" src="https://github.com/user-attachments/assets/c95357bc-01ab-4c01-8d53-c9564e97c129" />
<img width="605" alt="image" src="https://github.com/user-attachments/assets/c56447b2-f8c1-49ef-9ef1-544fb5e5289e" />
<img width="431" alt="image" src="https://github.com/user-attachments/assets/c8ce2592-ef6a-481e-8f22-18eca34664b6" />
<img width="545" alt="image" src="https://github.com/user-attachments/assets/d9300f16-6ca9-4f27-9fef-24a9facb5f33" />
<img width="442" alt="image" src="https://github.com/user-attachments/assets/88eff9d6-2934-4ce5-8d6f-897ddfb664ec" />


##  Résultats
Les modèles testés incluent la Régression Logistique, SVM, Naïve Bayes et LSTM, avec un **F1-score global de 79%** pour le LSTM. 

##  Comment Exécuter
1. Installez les dépendances : `pip install -r requirements.txt`
2. Lancez l'entraînement des modèles : `python train_models.py`
3. Faites des prédictions sur de nouveaux textes : `python predict.py --text "Operating profit increased significantly"`

##  Auteur
 **Fidèle-Ledoux** - Passionné de Data Science et NLP appliqué à la finance.

🔗 [LinkedIn](https://www.linkedin.com/in/fidele-ledoux) | [Portfolio](#)
