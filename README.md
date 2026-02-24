# 📡 Portail Captif Premium — WiFi Zone Assinie

Interface de connexion haut de gamme pour routeur **MikroTik RB5009UPR+S+IN**  
Développée par **Richol N'guessan Victoir** — © 2026

---

## 🖼️ Aperçu

- Écran d'accueil animé avec logo personnalisé
- Panneau coulissant (swipe) avec onglets : **J'ai un compte** / **J'ai un code** / **Mobile Money**
- Affichage des tarifs WiFi
- Bouton contact direct
- Oiseau animé colibri dans le champ de saisie
- Overlay Info & Actualités (3 taps sur le logo WiFi)
- Message onboarding au premier lancement

---

## ⚙️ Compatibilité

| Routeur | Statut |
|---|---|
| MikroTik RB5009UPR+S+IN | ✅ Compatible |
| Tout routeur MikroTik Hotspot | ✅ Compatible |

---

## 📁 Structure des fichiers

```
hotspot-assinie-pro/
├── login.html             ← Fichier principal (à renommer sur le routeur)
├── assets/
│   └── logo-richol-victoire.png   ← Logo à fournir
└── README.md
```

---

## 🚀 Déploiement sur MikroTik

1. Connecte-toi au routeur via **Winbox** ou **SSH**
2. Copie `login.html` dans `/flash/hotspot/`
3. Copie le dossier `assets/` dans `/flash/hotspot/assets/`
4. Dans Winbox → **IP → Hotspot → Server Profiles** → définir le répertoire HTML
5. Ouvrir dans un navigateur mobile pour tester

---

## 🔒 Version DÉMO

> ⚠️ Ce dépôt contient la **version démonstration**.  
> La connexion Internet est **désactivée**.  
> Pour la version complète prête à déployer, contacter l'auteur.

---

## 📜 Licence

```
© 2026 Richol N'guessan Victoir
Utilisation commerciale interdite sans autorisation.
Ce code est fourni à titre de démonstration uniquement.
```

---

## 📞 Contact:+225 0759921897

Pour acquérir la version complète ou personnaliser ce portail :  
**Richol N'guessan Victoir**

