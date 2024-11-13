- nom :
- prénom :
- URL Netlify :

# Travail

N'oublier pas votre nom, prénom et l'URL de publication Netlify...

# Complétez le CSS

**Faire plusieurs commits** pour chaque étape du CSS

Compléter le fichier [accordeon.css](/src/css/components/accordeon.css) et visualiser l'effet sur [index.html](/index.html) .

Vous devez obtenir :\
https://moodle.univ-fcomte.fr/draftfile.php/60882/user/draft/813910702/accordeon.mp4

# Manuellement sans JS

Simplement, cliquez sur les `summary`...

# Refermer les autres par code JS

Testez dans la console :

```js
accordeon = document.querySelector(".accordeon");
accordeon.querySelectorAll("details").forEach((det) => (det.open = false));
```

À faire, adapter le code dans les fichiers [script.js](/src/js/script.js) pour le faire suite à un clic sur un des `summary`.

**Commit** : referme les détails suite à un clic sur un `summary`

# Version avec [triangle CSS](https://css-tricks.com/snippets/css/css-triangle/)

https://moodle.univ-fcomte.fr/draftfile.php/60882/user/draft/813910702/accordeon-vertical.mp4

**Faire plusieurs commits** pour chaque étape du CSS
