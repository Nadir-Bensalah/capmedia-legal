# Pages légales — Capmedia Digital

Les pages exigées par l'App Store et Google Play pour les applications publiées
par Capmedia Digital. Servies par GitHub Pages, donc joignables sans serveur à
maintenir et sans risque d'expiration silencieuse.

**Ces adresses doivent rester valides tant qu'une application est publiée.**
Apple refuse une fiche sans politique de confidentialité, et retire une
application dont l'URL de support tombe en panne.

## Applications

| Application | Dossier | Bundle |
|---|---|---|
| Amiens - Bus & Vélam | `amiens-bus-velam/` | `app.capmedia.busamiens` |

## Adresses à renseigner dans les magasins

```
Confidentialité   /amiens-bus-velam/confidentialite
Conditions        /amiens-bus-velam/conditions
Mentions légales  /amiens-bus-velam/mentions-legales
Support           /amiens-bus-velam/support
```

## Mise en ligne

GitHub Pages sur la branche `master`, dossier racine.

**Le domaine racine n'est volontairement pas revendiqué.** Poser un fichier
`CNAME` avec `capmedia.app` ferait servir CE dépôt à la racine du domaine, et
remplacerait un site existant. Deux options propres :

- **sous-domaine** : `legal.capmedia.app`, avec un enregistrement CNAME DNS vers
  `nadir-bensalah.github.io`, puis un fichier `CNAME` contenant ce sous-domaine ;
- **site existant** : recopier le dossier `amiens-bus-velam/` dans le site
  capmedia.app, et garder ce dépôt comme source.

Tant que rien n'est décidé, les pages sont servies à l'adresse par défaut, et
c'est celle qui est renseignée dans l'application.
