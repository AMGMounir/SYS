# 🌟 Projet Parallélisation maximale automatique

## 💫 Objectif

Développer une bibliothèque en Python pour automatiser la parallélisation maximale des systèmes de tâches. L'utilisateur peut définir librement les tâches et leurs interactions via des variables et obtenir un système de tâches de parallélisme maximal, ainsi de les exécuter de manière séquentielle ou parallèle tout en respectant les contraintes de précédence. 

# Classes

### `Task`

- `name`: Le nom de la tâche.
- `reads`: Les lectures effectuées par la tâche.
- `writes`: Les écritures effectuées par la tâche.
- `run`: La fonction d'exécution de la tâche.

### `TaskSystem`

- `task_system`: Le système de tâches.
- `dependencies`: Les dépendances entre les tâches.
- `start`: Le début de l'exécution.
- `end`: La fin de l'exécution.

# Fonctionnalités

- `get_Dependencies()`: Renvoie une liste des noms des dépendances de chaque tâche.
- `runSeq()`: Exécute les tâches de manière séquentielle.
- `run()`: Exécute les tâches de manière parallèle.
- `parCost(nombrederun)`: Mesure les temps d'exécution séquentielle et parallèle.
- `detTestRnd(num_executions)`: Effectue des tests de déterminisme aléatoires.
- `draw(task_system)`: Dessine le graphe des tâches.
- `error_message(task_system)`: Gère les erreurs du système de tâches.

# Implémentation

 Le package utilise les importations suivantes :

- Standard : `time`, `threading`, `networkx`, `matplotlib.pyplot`, `random`

| Type | Importation | 
|-----------|-----------|
| Standard | time,threading,random|
| Pypi| NetworkX|
| Pypi| customtkinter|

# Installer

- Les modules standard sont déjà inclus dans la bibliothèque Python.
- Voici les étapes nécessaires pour installer NetworkX et customtkinter :
              -0- Pour exécuter les commandes suivantes, ouvrez votre terminal ou votre invite de commande :
              
              ```bash
                 $ pip install networkx matplotlib
                 $ pip install customtkinter

# Exécution 

   - Afin de lancer le programme :

     $ Télécharger le fichier éxecutable: https://drive.google.com/file/d/1lD-nWxCLmxDkWi19kWQF9dAUnfLMtPqd/view?usp=sharing

     $ clone https://github.com/AMGMounir/SYS.git


# 💻 Auteurs 

     - Mounir Amghar
     
     - Imane Hai

     - Kaoutar Oualad

                  
