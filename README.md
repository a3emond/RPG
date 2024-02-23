## **ACCES RAPIDE AU DOSSIER ASSETS**
(files goes in it)------>
[Assets](RPG_Forms_FromBC/RPG_Forms_FromBC/Assets/)
<h1>RPG BitchClub</h1>
<br>

<h1>Name Convention</h1>


<table>
    <caption>FILES</caption>
  <thead>
    <tr>
      <th>Type</th>
      <th>Convention de Nommage</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Images</td>
      <td>&lt;Type&gt;_&lt;Description&gt;_img.&lt;Extension&gt;</td>
    </tr>
    <tr>
      <td>Audio</td>
      <td>&lt;Type&gt;_&lt;Description&gt;_audio.&lt;Extension&gt;</td>
    </tr>
    <tr>
      <td>Scripts</td>
      <td>&lt;Type&gt;_&lt;Description&gt;_script.&lt;Extension&gt;</td>
    </tr>
    <tr>
      <td>Data</td>
      <td>&lt;Type&gt;_&lt;Description&gt;_data.&lt;Extension&gt;</td>
    </tr>
    <tr>
      <td>Autres</td>
      <td>&lt;Type&gt;_&lt;Description&gt;_autre.&lt;Extension&gt;</td>
    </tr>
  </tbody>
</table>

<p><strong>&lt;Type&gt;(examples) :</strong><br>
- "monster"<br>
- "map"<br>
- "zone"<br>
- "player"<br>
- "weapon"<br>
- "item"</p>



<h1>Naming Conventions in C#</h1>

<table>
  <thead>
    <tr>
      <th>Type</th>
      <th>Convention de Nommage</th>
      <th>Exemples</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Local Variables</td>
      <td>CamelCase: <span style="color: #ffb86c;">localVariableName</span></td>
      <td>numberOfAnimals, playerName</td>
    </tr>
    <tr>
      <td>Class Member Variables</td>
      <td>CamelCase prefixed with '_': <span style="color: #ffb86c;">_memberVariableName</span></td>
      <td>_numberOfAnimals, _playerName</td>
    </tr>
    <tr>
      <td>Static Variables</td>
      <td>PascalCase prefixed with 's_': <span style="color: #ffb86c;">s_StaticVariableName</span></td>
      <td>s_NumberOfAnimals, s_PlayerName</td>
    </tr>
    <tr>
      <td>Constants</td>
      <td>UpperCase: <span style="color: #ffb86c;">CONSTANT_NAME</span></td>
      <td>MAX_ANIMALS, GAME_NAME</td>
    </tr>
    <tr>
      <td>Method Parameters</td>
      <td>CamelCase: <span style="color: #ffb86c;">parameterName</span></td>
      <td>playerName, healthPoints</td>
    </tr>
    <tr>
      <td>Properties</td>
      <td>PascalCase: <span style="color: #ffb86c;">PropertyName</span></td>
      <td>NumberOfAnimals, PlayerName</td>
    </tr>
  </tbody>
</table>
<br>
<h2>Class Structure:</h2>
<table>
    <thead>
        <tr>
            <th>Catégorie</th>
            <th>Nom de la Classe</th>
            <th>Description</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Characters</td>
            <td>Character.cs</td>
            <td>Classe représentant un personnage dans le jeu.</td>
        </tr>
        <tr>
            <td></td>
            <td>PlayerCharacter.cs</td>
            <td>Classe représentant le personnage joueur.</td>
        </tr>
        <tr>
            <td></td>
            <td>QuestNPC.cs</td>
            <td>Classe représentant un personnage non joueur offrant des quêtes.</td>
        </tr>
        <tr>
            <td>Game Engine</td>
            <td>CombatManager.cs</td>
            <td>Classe pour gérer les combats dans le jeu.</td>
        </tr>
        <tr>
            <td></td>
            <td>GameManager.cs</td>
            <td>Classe principale du moteur de jeu.</td>
        </tr>
        <tr>
            <td></td>
            <td>MapManager.cs</td>
            <td>Classe pour gérer les cartes et les niveaux du jeu.</td>
        </tr>
        <tr>
            <td></td>
            <td>SoundManager.cs</td>
            <td>Classe pour gérer les sons et les effets sonores du jeu.</td>
        </tr>
        <tr>
            <td>Input</td>
            <td>ControllerInputManager.cs</td>
            <td>Gère les entrées via un contrôleur.</td>
        </tr>
        <tr>
            <td></td>
            <td>InputManager.cs</td>
            <td>Gère les entrées générales.</td>
        </tr>
        <tr>
            <td></td>
            <td>KeyboardInputManager.cs</td>
            <td>Gère les entrées via le clavier.</td>
        </tr>
        <tr>
            <td>Items</td>
            <td>Consumable.cs</td>
            <td>Classe pour représenter les objets consommables.</td>
        </tr>
        <tr>
            <td></td>
            <td>Equipment.cs</td>
            <td>Classe pour représenter l'équipement porté par le joueur.</td>
        </tr>
        <tr>
            <td></td>
            <td>Item.cs</td>
            <td>Classe de base pour tous les objets dans le jeu.</td>
        </tr>
        <tr>
            <td></td>
            <td>Weapon.cs</td>
            <td>Classe pour représenter les armes dans le jeu.</td>
        </tr>
        <tr>
            <td>Maps</td>
            <td>Map.cs</td>
            <td>Classe pour représenter une carte ou un niveau dans le jeu.</td>
        </tr>
        <tr>
            <td></td>
            <td>Zone.cs</td>
            <td>Classe pour représenter une zone sur la carte.</td>
        </tr>
        <tr>
            <td>Quests and Story</td>
            <td>Dialogue.cs</td>
            <td>Classe pour représenter les dialogues dans le jeu.</td>
        </tr>
        <tr>
            <td></td>
            <td>DialogueManager.cs</td>
            <td>Classe pour gérer les dialogues et les interactions avec les personnages non joueurs.</td>
        </tr>
        <tr>
            <td></td>
            <td>ExperienceReward.cs</td>
            <td>Classe pour représenter la récompense d'expérience à la fin d'une quête.</td>
        </tr>
        <tr>
            <td></td>
            <td>ItemReward.cs</td>
            <td>Classe pour représenter la récompense d'objet à la fin d'une quête.</td>
        </tr>
        <tr>
            <td></td>
            <td>Quest.cs</td>
            <td>Classe pour représenter une quête dans le jeu.</td>
        </tr>
        <tr>
            <td></td>
            <td>QuestManager.cs</td>
            <td>Classe pour gérer les quêtes disponibles et en cours.</td>
        </tr>
        <tr>
            <td></td>
            <td>Reward.cs</td>
            <td>Classe pour représenter une récompense générique.</td>
        </tr>
        <tr>
            <td></td>
            <td>Story.cs</td>
            <td>Classe pour représenter l'histoire du jeu.</td>
        </tr>
        <tr>
            <td>Save System</td>
            <td>SaveFile.cs</td>
            <td>Classe pour gérer la sauvegarde des fichiers.</td>
        </tr>
        <tr>
            <td></td>
            <td>SaveGameManager.cs</td>
            <td>Classe pour gérer les données de sauvegarde du jeu.</td>
        </tr>
        <tr>
            <td>UI</td>
            <td>CombatWindow.cs</td>
            <td>Classe pour afficher les informations de combat.</td>
        </tr>
        <tr>
            <td></td>
            <td>InventoryWindow.cs</td>
            <td>Classe pour gérer l'inventaire du joueur.</td>
        </tr>
        <tr>
            <td></td>
            <td>MainMenu.cs</td>
            <td>Classe pour afficher le menu principal du jeu.</td>
        </tr>
        <tr>
            <td></td>
            <td>MainWindow.cs</td>
            <td>Classe pour gérer la fenêtre principale du jeu.</td>
        </tr>
        <tr>
            <td>Utility</td>
            <td>AnimationController.cs</td>
            <td>Classe pour contrôler les animations dans le jeu.</td>
        </tr>
        <tr>
            <td></td>
            <td>RandomManager.cs</td>
            <td>Classe pour gérer la génération de nombres aléatoires dans le jeu.</td>
        </tr>
    </tbody>
</table>
<b>RPG BitchClub</b><br>
│<br>
├── <b>Characters</b><br>
│   ├── <b>Character.cs</b> - <em>Classe représentant un personnage dans le jeu.</em><br>
│   ├── <b>PlayerCharacter.cs</b> - <em>Classe représentant le personnage jouable dans le jeu.</em><br>
│   └── <b>QuestNPC.cs</b> - <em>Classe représentant un personnage non joueur offrant des quêtes.</em><br>
│<br>
├── <b>Game Engine</b><br>
│   ├── <b>CombatManager.cs</b> - <em>Classe pour gérer les combats dans le jeu.</em><br>
│   ├── <b>GameManager.cs</b> - <em>Classe principale du moteur de jeu.</em><br>
│   ├── <b>MapManager.cs</b> - <em>Classe pour gérer les cartes et les niveaux du jeu.</em><br>
│   └── <b>SoundManager.cs</b> - <em>Classe pour gérer les sons dans le jeu.</em><br>
│<br>
├── <b>Input</b><br>
│   ├── <b>ControllerInputManager.cs</b> - <em>Classe pour gérer les entrées à partir d'un contrôleur.</em><br>
│   ├── <b>InputManager.cs</b> - <em>Classe pour gérer les entrées génériques.</em><br>
│   └── <b>KeyboardInputManager.cs</b> - <em>Classe pour gérer les entrées au clavier.</em><br>
│<br>
├── <b>Items</b><br>
│   ├── <b>Consumable.cs</b> - <em>Classe pour représenter les objets consommables.</em><br>
│   ├── <b>Equipment.cs</b> - <em>Classe pour représenter l'équipement porté par le joueur.</em><br>
│   ├── <b>Item.cs</b> - <em>Classe de base pour tous les objets dans le jeu.</em><br>
│   └── <b>Weapon.cs</b> - <em>Classe pour représenter les armes dans le jeu.</em><br>
│<br>
├── <b>Maps</b><br>
│   ├── <b>Map.cs</b> - <em>Classe pour représenter une carte ou un niveau dans le jeu.</em><br>
│   └── <b>Zone.cs</b> - <em>Classe pour représenter une zone dans une carte.</em><br>
│<br>
├── <b>Quests and Story</b><br>
│   ├── <b>Dialogue.cs</b> - <em>Classe pour représenter un dialogue dans le jeu.</em><br>
│   ├── <b>DialogueManager.cs</b> - <em>Classe pour gérer les dialogues dans le jeu.</em><br>
│   ├── <b>ExperienceReward.cs</b> - <em>Classe pour représenter une récompense en expérience dans le jeu.</em><br>
│   ├── <b>ItemReward.cs</b> - <em>Classe pour représenter une récompense en objet dans le jeu.</em><br>
│   ├── <b>Quest.cs</b> - <em>Classe pour représenter une quête dans le jeu.</em><br>
│   ├── <b>QuestManager.cs</b> - <em>Classe pour gérer les quêtes disponibles et en cours dans le jeu.</em><br>
│   ├── <b>Reward.cs</b> - <em>Classe pour représenter une récompense dans le jeu.</em><br>
│   └── <b>Story.cs</b> - <em>Classe pour représenter une histoire dans le jeu.</em><br>
│<br>
├── <b>Save System</b><br>
│   ├── <b>SaveFile.cs</b> - <em>Classe pour représenter un fichier de sauvegarde dans le jeu.</em><br>
│   └── <b>SaveGameManager.cs</b> - <em>Classe pour gérer la sauvegarde des données du jeu.</em><br>
│<br>
├── <b>UI</b><br>
│   ├── <b>CombatWindow.cs</b> - <em>Classe pour afficher les informations de combat dans le jeu.</em><br>
│   ├── <b>InventoryWindow.cs</b> - <em>Classe pour gérer l'inventaire du joueur dans le jeu.</em><br>
│   ├── <b>MainMenu.cs</b> - <em>Classe pour afficher le menu principal du jeu.</em><br>
│   └── <b>MainWindow.cs</b> - <em>Classe pour gérer la fenêtre principale du jeu.</em><br>
│<br>
└── <b>Utility</b><br>
    ├── <b>AnimationController.cs</b> - <em>Classe pour contrôler les animations dans le jeu.</em><br>
    └── <b>RandomManager.cs</b> - <em>Classe pour gérer la génération de nombres aléatoires dans le jeu.</em><br>



<h2>Assets Structure</h2>

<b>Assets</b><br>
│<br>
├── <b>Images</b><br>
│   ├── <b>Characters</b> - <em>Images des personnages du jeu.</em><br>
│   ├── <b>Items</b> - <em>Images des objets et équipements du jeu.</em><br>
│   └── <b>Maps</b> - <em>Images des cartes et niveaux du jeu.</em><br>
│<br>
├── <b>Audio</b><br>
│   ├── <b>Music</b> - <em>Fichiers audio pour la musique du jeu.</em><br>
│   └── <b>SoundEffects</b> - <em>Fichiers audio pour les effets sonores du jeu.</em><br>
│<br>
├── <b>Scripts</b><br>
│   ├── <b>Characters</b> - <em>Scripts pour le comportement des personnages.</em><br>
│   ├── <b>Items</b> - <em>Scripts pour les fonctionnalités des objets.</em><br>
│   ├── <b>Maps</b> - <em>Scripts pour la gestion des cartes et niveaux.</em><br>
│   ├── <b>UI</b> - <em>Scripts pour les interfaces utilisateur.</em><br>
│   └── <b>Utilities</b> - <em>Scripts utilitaires pour diverses fonctionnalités.</em><br>
│<br>
└── <b>Data</b><br>
    ├── <b>Configurations</b> - <em>Données de configuration du jeu.</em><br>
    ├── <b>Dialogues</b> - <em>Fichiers de dialogue pour les interactions dans le jeu.</em><br>
    └── <b>Quests</b> - <em>Données de quêtes et d'objectifs du jeu.</em><br>


