# Éditeur de Photo de Profil Facebook

Application web simple et élégante pour créer des photos de profil Facebook personnalisées avec un décor.

## Fonctionnalités

- ✅ Interface moderne et intuitive
- ✅ Upload de photo de profil
- ✅ Application automatique d'un décor PNG
- ✅ Aperçu en temps réel
- ✅ Téléchargement de l'image finale
- ✅ Tout fonctionne dans le navigateur (aucun serveur requis)

## Installation

1. Placez votre fichier de décor PNG dans le même répertoire que `index.html`
2. Renommez votre fichier décor en `frame.png` (ou modifiez la constante `FRAME_FILE` dans le code)
3. Ouvrez `index.html` dans un navigateur moderne

## Utilisation

1. Ouvrez `index.html` dans votre navigateur
2. Cliquez sur "📷 Choisir votre photo de profil"
3. Sélectionnez une photo depuis votre ordinateur
4. L'aperçu s'affiche automatiquement
5. Cliquez sur "⬇️ Télécharger l'image finale"
6. Utilisez l'image téléchargée comme photo de profil Facebook

## Spécifications techniques

- **Format d'image finale** : PNG, 1836x1836 pixels (format Facebook)
- **Photo de profil** : Dessinée en cercle au centre
- **Décor** : Superposé par-dessus la photo
- **Technologies** : HTML5 Canvas, JavaScript vanilla
- **Compatibilité** : Tous les navigateurs modernes

## Personnalisation

Pour changer le fichier de décor, modifiez cette ligne dans le code :

```javascript
const FRAME_FILE = 'frame.png'; // Changez le nom ici
```

## Notes

- Le décor doit être un PNG avec transparence
- La photo de profil est automatiquement recadrée en cercle
- Tout le traitement se fait dans le navigateur (aucune donnée envoyée à un serveur)
