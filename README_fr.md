<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Friendica pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/friendica.svg)](https://dash.yunohost.org/appci/app/friendica) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/friendica.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/friendica.maintain.svg)  
[![Installer Friendica avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=friendica)

*[Read this readme in english.](./README.md)*

> *Ce package vous permet d’installer Friendica rapidement et simplement sur un serveur YunoHost.
Si vous n’avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Friendica is a decentralised communications platform that integrates social communication. The platform links to independent social projects and corporate services.

Friendica connects you effortlessly to a federated communications network of several thousand servers, with more than half a million user registrations. You can directly connect to anyone on Friendica, Mastodon, Diaspora, GnuSocial, Pleroma, or Hubzilla, regardless where each user profile is hosted.

**Version incluse :** 2023.01~ynh1

**Démo :** https://dir.friendica.social/servers

## Captures d’écran

![Capture d’écran de Friendica](./doc/screenshots/friendica-vier-profile.png)

## Avertissements / informations importantes

## Installation

### Enregistrez un nouveau domaine et ajoutez-le à YunoHost

Avant l'installation, lisez les [instructions d'installation de Friendica](https://github.com/friendica/friendica/blob/develop/doc/Install.md) pour obtenir des informations importantes sur l'installation.

- Domaine dédié (doit être installé sous la racine Web comme **https://friendica.example.com/** et non **https://example.com/friendica/** )

- Friendica nécessite des certificats SSL approuvés par le navigateur.

### Installer Friendica
Utilisez le panneau d'administration YunoHost pour installer Friendica en saisissant l'adresse du dépôt GitHub dans l'URL de l'application personnalisée :

https://github.com/YunoHost-Apps/friendica_ynh

## Utilisateur avec des droits d'administrateur LDAP
**Pour les droits d'administrateur** : une fois l'installation terminée, vous devrez visiter la page de votre domaine et vous connecter avec le **nom d'utilisateur et le mot de passe du compte administrateur** qui ont été saisis au moment du processus d'installation. Vous pouvez ensuite créer votre profil et accéder au panneau d'administration.

 **Pour les utilisateurs normaux de YunoHost :** Les utilisateurs LDAP normaux peuvent se connecter via l'authentification LDAP et y créer des profils. 

## Documentations et ressources

* Site officiel de l’app : <http://friendi.ca>
* Documentation officielle utilisateur : <https://wiki.friendi.ca/>
* Documentation officielle de l’admin : <https://github.com/friendica/friendica/wiki>
* Dépôt de code officiel de l’app : <https://github.com/friendica/friendica>
* Documentation YunoHost pour cette app : <https://yunohost.org/app_friendica>
* Signaler un bug : <https://github.com/YunoHost-Apps/friendica_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/friendica_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/friendica_ynh/tree/testing --debug
ou
sudo yunohost app upgrade friendica -u https://github.com/YunoHost-Apps/friendica_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>