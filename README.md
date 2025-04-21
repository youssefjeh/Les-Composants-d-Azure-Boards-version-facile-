## 🧩 Les Composants d'Azure Boards (version facile)

### 1. **Work Items (Éléments de travail)**
👉 Ce sont les **blocs de base** dans Azure Boards. Chaque tâche, idée, bug, ou fonctionnalité est un "Work Item".

Il en existe plusieurs types :
- **Epic** : une grande fonctionnalité ou un gros thème (ex : "Refondre toute l’app mobile")
- **Feature** : une partie d’un Epic (ex : "Ajout de l’authentification")
- **User Story** : une fonctionnalité du point de vue de l’utilisateur (ex : "En tant qu’utilisateur, je peux me connecter")
- **Task** : une action à faire pour réaliser une User Story (ex : "Créer l’écran de connexion")
- **Bug** : un problème à corriger

---

### 2. **Boards (Tableaux)**
👉 Une vue en mode **Kanban**, comme Trello.

Tu vois chaque User Story sous forme de carte, classée dans des colonnes (par exemple : **To Do**, **Doing**, **Done**).

> Idéal pour suivre ce que chaque personne fait, ce qui est en cours, et ce qui est terminé.

---

### 3. **Backlogs**
👉 Une **liste hiérarchique** de tes éléments de travail (Epic > Feature > User Story > Task).

Tu peux les organiser par priorité, sprint, etc.  
C’est là qu’on planifie ce qui sera fait.

---

### 4. **Sprints**
👉 Un **Sprint** est une période de travail (souvent 2 semaines) pendant laquelle l’équipe se concentre sur un ensemble de tâches.

Dans Azure DevOps, tu peux créer un Sprint, y glisser les User Stories du backlog, et suivre l’avancement.

---

### 5. **Queries (Requêtes)**
👉 Un moyen de **filtrer et trouver** des Work Items (par personne, par type, par tag, par sprint, etc.)

Très pratique pour voir :
- Tous les bugs ouverts
- Les tâches de tel développeur
- Les User Stories d’un sprint donné

---

### 6. **Dashboards (Tableaux de bord)**
👉 Une page personnalisée avec **des widgets visuels** (graphiques, burndown charts, listes de bugs, etc.).

Parfait pour avoir une vue d’ensemble rapide du projet.

---

### 7. **Tags**
👉 Des **étiquettes** que tu peux ajouter aux Work Items pour mieux les classer.  
Exemples : `frontend`, `urgent`, `bug`, `sprint1`, etc.

---

### 🎯 Exemple simple :
Tu travailles sur une app mobile, voici comment ça se structure :

- **Epic** : Application mobile complète
  - **Feature** : Authentification
    - **User Story** : "Je peux me connecter avec mon email et mot de passe"
      - **Tasks** :
        - Créer l’interface de connexion
        - Gérer la logique backend
        - Tester les erreurs de login

Tu les vois tous dans le **Backlog**, tu les planifies dans un **Sprint**, tu les suis dans le **Board**, et tu analyses tout ça dans un **Dashboard** 🧠
