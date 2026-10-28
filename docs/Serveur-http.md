# Lancer le site localement

Ouvrir les fichiers HTML directement dans le **navigateur Web** fonctionne mais montre rapidement ses limites.

Pour lancer **un site statique** localement on doit utiliser un **serveur Web**.

Les serveurs Web les plus connus sont [Nginx](https://nginx.org/) et [Apache](https://httpd.apache.org/), mais ils sont assez compliqués à installer et configurer quand on débute.

Je vous propose plusieurs options plus simples pour commencer.

Vous pouvez choisir celle que vous préférez. Vous trouverez les lignes de commmande à copier dans votre terminal dans les chapitres ci dessous.


Une fois l'une de ces commande lancée, vous pouvez accéder au site dans le navigateur : http://localhost:8000

## Via Python (recommandé)

> C'est le choix recommandé car python est installé par défaut sur Linux et macOS.
> Ca devrait fonctionner directement. 

Avec la commande [python](https://docs.python.org/3/library/http.server.html)

```sh
python -m http.server
# python3 -m http.server
```

## Serveur Vite avec NodeJs

Avec la commande [vite](https://vite.dev/guide/cli) en NodeJs

```sh
npw vite --port 8000
```

## Serveur jwebserver avec Java

Avec la commande [`jwebserver` inclue avec Java](https://dev.java/learn/jvm/tool/jwebserver/)

```sh
jwebserver
```

## Serveur PHP

Avec la commande [php pour ouvrir un serveur local interne](https://www.php.net/manual/fr/features.commandline.webserver.php)

```sh
php -S localhost:8000
```

