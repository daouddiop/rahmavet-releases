# RahmaVét Manager — Fenêtre native

Logiciel de gestion cabinet vétérinaire.
S'ouvre dans **sa propre fenêtre** (plus besoin du navigateur).

## Lancer

```bat
pip install -r requirements.txt
python desktop_app.py
```

Ou double-clic sur **Lancer_RahmaVet.bat**.

Mode navigateur (secours) :
```bat
python run.py browser
```

Login initial : `admin` / `admin123`

## Windows — exécutable + installateur

1. `build_windows.bat` → `dist\RahmaVetManager.exe`
2. Inno Setup → ouvrir `installer.iss` → Compile  
   → `Output\RahmaVetManager_Setup.exe`

## Vos informations cabinet (déjà configurées)

- Nom : RahmaVét
- Adresse : Darou Rahmane 2éme Bayale
- Tél : 78 541 87 66
- Email : contact@rahmavet.sn

Modifiables dans `config.py`.

## Fonctionnalités

- Fenêtre native (pywebview)
- Animaux, stock, dépenses, factures PDF, RDV
- Sauvegardes + récupération mot de passe
- Mode sombre, export CSV
- 100 % local / hors ligne
