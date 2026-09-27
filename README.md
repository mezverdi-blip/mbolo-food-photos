# Mbôlo Food — photos

Ce dépôt héberge les **photos optimisées (WebP)** utilisées par l'application mobile
**Mbôlo Food** (annuaire des restaurants de Libreville et du Gabon).

- **Origine** : les photos proviennent des **fiches publiques Google Maps** des restaurants
  (photos publiées par les établissements et par les contributeurs Google Maps).
  Crédits : © Google Maps et les contributeurs respectifs de chaque fiche.
- **Traitement** : redimensionnement et conversion WebP uniquement (aucune retouche),
  pour un affichage rapide et léger dans l'application.
- **Organisation** : `<id-restaurant>/<nn>-<empreinte>-<taille>.webp`
  - `s` : vignette 240×240 (listes)
  - `m` : carte 640×400
  - `l` : galerie 1080×810 (fiche restaurant)
- **Diffusion** : GitHub Pages — `https://mezverdi-blip.github.io/mbolo-food-photos/<chemin>`
  (miroir : `https://cdn.jsdelivr.net/gh/mezverdi-blip/mbolo-food-photos@main/<chemin>`).

## Retrait sur demande

Vous êtes l'auteur d'une photo ou le responsable d'un établissement et souhaitez
qu'une image soit retirée ? Ouvrez une *issue* sur ce dépôt en indiquant le chemin du
fichier (ou le nom du restaurant) : elle sera supprimée rapidement.

Mise à jour : script `scripts/sync-photos.py` de l'application (téléchargement,
optimisation, envoi par lots).
