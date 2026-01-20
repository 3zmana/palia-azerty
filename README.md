# 🎹 Configuration des touches AZERTY pour **Palia**

Par défaut, **Palia** utilise un clavier **QWERTY**, et l’interface du jeu ne permet malheureusement pas de modifier toutes les touches pour passer proprement en **AZERTY**.  
Ce dépôt vous propose donc une configuration prête à l’emploi, simplement en modifiant le fichier de paramètres du jeu.

---

## 🛠️ Installation

Suivez ces étapes pour appliquer la configuration AZERTY :

1. **Ouvrir l’explorateur AppData**
   - Appuyez sur **Windows + R**
   - Tapez `appdata` puis validez avec `OK`

2. **Naviguer jusqu'au dossier de configuration**
   - Allez dans :  
     `AppData` → `Local` → `Palia` → `Saved` → `Config` → `WindowsClient`

3. **Ouvrir le fichier de configuration**
   - Éditez le fichier **GameUserSettings.ini**

4. **Remplacer la ligne concernée**
   - Repérez la ligne **6** :  
     `InputSettings=***`
   - Remplacez-la par celle fournie dans le fichier **InputSettings.txt** disponible dans ce dépôt.

5. **Sauvegarder**
   - Enregistrez le fichier, relancez le jeu… et profitez !

---

## ❗ Problèmes connus

- **Menu de résidence (touche H sur votre parcelle)**  
  Le déplacement de caméra via les touches du clavier ne fonctionne pas dans ce menu.  
  Vous pouvez cependant orienter la caméra **en maintenant le clic droit de la souris**, ce qui permet de contourner le problème.

- **Visite des autres parcelles publiques ou la parcelle d'exemple**  
  Le déplacement via les touches AZERTY ne fonctionne pas lors de la visite des terrains publiques des autres joueurs ou du terrain d'exemple. (Panneau vert)

- **Clavier AZERTY non pris en charge**
  Après avoir contacté le support de Palia pour demander d'exposer les touches encore non-configurables même via le fichier de configuration. 
  Ils m'ont répondu que « Officiellement, Palia ne prend pas en charge les claviers AZERTY ». (Décembre 2025)

---

## ✔️ Version testée

- **Palia 0.199.0**.