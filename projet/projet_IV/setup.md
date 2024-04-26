
# Setup


- **Indiquer dans un fichier `README.md` les noms des élèves du groupe**

- Créer un repository privé sur Github et ajouter en collaborateurs les comptes : 'selim.mellouk.halgand@proton.me' et 'etienne-mad'.

- Veiller à utiliser la même version de Python que dans le cours (3.11.4) via un environnement virtuel
    ```bash
    # windows
    # Installer la version de Python
    pyenv install 3.10.4
    # Créer l'environnement dans le dossier courant
    ~/.pyenv/pyenv-win/versions/3.10.4/python.exe -m venv env
    ```

- Ne pas commit l'environnement virtuel sur Git en ajoutant le nom de l'environnement virtuel (ie du dossier souvent appelé `env`) au `.gitignore`


- À la racine du repository, créer un fichier  `requirements.txt` : (pour afficher la version d'une librairie, on utilise `pip show <library>` avec l'environnement virtuel d'activé.)

    ```
    dnspython==2.4.2
    ipykernel==6.26.0
    #... toute autre librairie que vous utilisez

    ```

- Architecture du repository : 

    ```
    repo
    ├── .gitignore
    ├── env
    ├── README.md
    ├── requirements.txt
    └── ...
    ```
