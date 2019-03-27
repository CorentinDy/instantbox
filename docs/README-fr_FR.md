<p align="right">En | <a href="./docs/README-zh_cn.md">简</a> | <a href="./docs/README-zh_tw.md">繁</a> | <a href="./docs/README-fr_FR.md">Fr</a></p>

<div align="center">

![logo](https://user-images.githubusercontent.com/5880908/53614582-6ebdfc80-3ba8-11e9-819e-d96a3f7c22f0.png)

# instantbox

Get a clean, ready-to-go Linux box in seconds.

[![Travis CI](https://badgen.net/travis/instantbox/instantbox)](https://travis-ci.com/instantbox/instantbox)
[![Docker](https://badgen.net/badge//instantbox%2Finstantbox?icon=docker)](https://hub.docker.com/r/instantbox/instantbox)
![Python 3.6](https://badgen.net/badge/python/3.6/3776ab)
![Code Style Pep8](https://badgen.net/badge/code%20style/pep8/ffd343)
[![Chat on Telegram](https://badgen.net/badge/chat/on%20telegram/0088cc)](https://t.me/joinchat/HtYtxRSerOwrMLg_2_wZTQ)
[![MIT](https://badgen.net/badge/license/MIT/3da639)](LICENSE)

</div>


## Introduction

### Qu'est ce qu'instantbox?

C'est un projet qui crée des systèmes Linux temporaires avec un accès instantané aux Webshell à partir de n'importe quel navigateur.


### Que peut faire une Instantbox?

1. fournir un environnement Linux propre pour une présentation
2. permettre aux étudiants d'expérimenter le charme de Linux dans votre école ou lors de votre prochaine réunion LUG
3. travailler avec inspiration dans un environnement propre
4. gérer des serveurs depuis n'importe quel appareil
5. expérimenter avec un projet open source
6. tester les performances logicielles avec des contraintes de ressources 

et plus encore! les posibilitées sont infinies...


### Quelles distributions Linux sont disponibles?


Nous supportons actuellement différentes version d'Ubuntu, CentOS, Arch Linux, Debian, Fedora et Alpine.



## Démarrage rapide

![Demo screenshot](https://user-images.githubusercontent.com/5880908/53613565-6237a500-3ba4-11e9-9e39-8ea48cee73ee.png)


## Déploiement

Prérequis: docker [[Plus d'informations]](https://docs.docker.com/install/)

```bash
mkdir instantbox && cd $_
bash <(curl -sSL https://raw.githubusercontent.com/instantbox/instantbox/master/init.sh)
```


## Questions

Merci de soumettre un problème ou rejoindre la conversation sur [telegram](https://t.me/joinchat/HtYtxRSerOwrMLg_2_wZTQ).


## Donations

Nous avons un besoin urgent de dons sous forme de ressources de serveurs. Veuillez nous contacter à team@instantbox.org si vous pouvez nous aider. On appréciera énormement!

## Credits

* [tsl0922/ttyd](https://github.com/tsl0922/ttyd) - webshell


## License

[MIT](LICENSE)
