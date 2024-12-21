Pour créer et activer un environnement virtuel Python, suivez les étapes suivantes :

#  **Création de l'environnement virtuel** :
    
- Ouvrez votre terminal ou invite de commande.
- Exécutez la commande suivante, en remplaçant `<nom_env>` par le nom souhaité pour votre environnement 
```bash
    python -m venv <nom_env>   
```
        
   Cette commande crée un répertoire `<nom_env>` contenant une installation indépendante de Python et les outils nécessaires.

# **Activation de l'environnement virtuel** :
    
 **Sous Windows** :
        - Dans l'invite de commande, exécutez :
            
```bash
    <nom_env>\Scripts\activate.bat
```
Si vous utilisez PowerShell, exécutez :
            
```bash
    <nom_env>\Scripts\Activate.ps1
```
            
**Sous Unix ou MacOS** :
Dans le terminal, exécutez :

```bash
    source <nom_env>/bin/activate
````
            
   Après activation, le nom de votre environnement virtuel apparaît entre parenthèses au début de la ligne de commande, indiquant que l'environnement est actif.  

# **Désactivation de l'environnement virtuel** :

 Lorsque vous avez terminé votre travail, désactivez l'environnement virtuel en exécutant :

```bash
    deactivate
```
        
Cette commande rétablit l'environnement Python par défaut de votre système.

Ces étapes vous permettent de créer un environnement isolé pour vos projets Python, facilitant la gestion des dépendances et évitant les conflits entre différentes versions de paquets

Ressource : 
https://docs.python.org/fr/3/tutorial/venv.html
https://youtu.be/5MzhGQ8WL70?si=VK0nVVp_Q_NmYblw



