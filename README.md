# New Media Design 3 2018-2019

Studenten:

 - «Voornaam» «Familienaam»
 - «Voornaam» «Familienaam»

## Productiedossier

### Installatie

#### Project klonen

Open **PowerShell Core 6** en kloon het repository dat je door **GitHub Classroom** gekregen hebt.

```
PS> c
PS> git clone «repository-url» «mapnaam»
PS> c «mapnaam»
```

#### Update Ruby Gems

Update de Ruby Gems met **Bundler**

```
PS> c «mapnaam»
PS> cd docs
PS> bundle update
PS> bundle exec jekyll serve
```

### Jekyll-configuratie

In `docs/_config.yml` pas je de `baseurl` aan, van:

```
# Site settings
# ─────────────
baseurl: /1819-nmd3-project # the subpath of your site, e.g. /blog
```

naar `/«repositorynaam»` (bv. `/1819-nmd3-project-Docenten`):

```
# Site settings
# ─────────────
baseurl: /«repositorynaam» # the subpath of your site, e.g. /blog
```

### GitHub Pages Configuratie

Op GitHub ga je naar je repository en klik op **Settings**. Scroll naar beneden tot aan **GitHub Pages**, zet de **Source** op `master branch /docs folder` en klik op **Save** om te bewaren.

### Voorbeeldsite

 - Basissjabloon <https://gdmgent-1819-nmd3.github.io/1819-nmd3-project-master>
 - Persoonlijke repo van Olivier Parent <https://gdmgent-1819-nmd3.github.io/1819-nmd3-project-Docenten>
