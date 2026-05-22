# Atlas de la pensée occidentale

Carte interactive de la philosophie occidentale — penseurs, courants, influences et connexions.

**https://alphaGoGoYet.github.io/philosophie-map/**

---

## Navigation

- **Vue d'ensemble** : la carte entière est visible au démarrage. Un encadré suit la souris pour montrer la zone qui sera affichée au zoom.
- **Cliquer** n'importe où → zoom sur cette zone
- **Glisser** pour naviguer en mode zoomé
- **Ctrl + molette** pour ajuster le zoom
- **Double-clic** ou **Echap** → retour à la vue d'ensemble
- **Cliquer un penseur** → panneau détaillé (pensée, citations, bibliographie, liens)
- **Rechercher** un nom ou concept dans la barre en haut

---

## Enrichir le contenu

Chaque penseur dispose d'un dossier dans `data/` avec trois fichiers éditables :

```
data/
  kant/
    description.md     ← texte libre sur la pensée (markdown)
    quotes.json        ← citations avec source
    bibliography.json  ← œuvres avec date
```

### Modifier une fiche existante

1. Ouvrir le fichier sur github.com (ex. `data/kant/description.md`)
2. Cliquer l'icône **crayon** en haut à droite
3. Modifier le contenu
4. Cliquer **Commit changes**

La carte en ligne se met à jour automatiquement en ~30 secondes.

### Ajouter un penseur non encore documenté

1. Copier le dossier `data/_template/` et le renommer avec l'identifiant du penseur (en minuscules, sans accents, ex. `data/montaigne/`)
2. Remplir les trois fichiers en suivant le format du template
3. Commiter

### Format des fichiers

**description.md** — texte libre en markdown :
```markdown
Texte de présentation de la pensée.

Deuxième paragraphe. On peut utiliser **gras** et *italique*.
```

**quotes.json** — tableau de citations :
```json
[
  {
    "text": "Texte de la citation.",
    "source": "Titre de l'œuvre, chapitre"
  }
]
```

**bibliography.json** — tableau d'œuvres :
```json
[
  {
    "title": "Titre de l'œuvre",
    "year": "1781"
  }
]
```

---

## Penseurs documentés

Antiquité · Moyen Âge · Renaissance · Rationalisme · Empirisme · Lumières · Idéalisme allemand · XIXe siècle · Phénoménologie · Existentialisme · Structuralisme · Théorie critique · Philosophie analytique · Épistémologie · Pragmatisme · Sciences sociales · Économie · Pensée postcoloniale
