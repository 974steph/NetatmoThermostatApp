# NetatmoThermostatApp
Gestion d'un [thermostat Netatmo](https://www.netatmo.com/fr-FR/product/energy/) via la box eedomus

Script cr�� par [@Thibautg16](https://twitter.com/Thibautg16/)

Cette application est l'adaptation du script existant avec quelques am�liorations (![changelog](https://github.com/Thibautg16/NetatmoThermostatApp/blob/master/CHANGELOG.md))

## Pr�requis 
Vous devez au pr�alable disposer d'un thermostat Netatmo install� et configur�.

## Commen�ons
### Ajout du p�riph�rique 
Cliquez sur "Configuration" / "Ajouter ou supprimer un pr�riph�rique" / "Store eedomus" / "Netatmo Thermostat App" / "Cr�er"

![2017-12-09_13h14_08](https://user-images.githubusercontent.com/4451322/33806330-ffa4c576-ddc6-11e7-9d21-7893a0de7ecf.png)

Cliquez sur **Cliquez ici pour obtenir votre code code d'autorisation**. Vous �tes alors redirig�s vers le portail Netatmo. 

![2017-12-04_22h43_29](https://user-images.githubusercontent.com/4451322/33577887-e5852324-d944-11e7-8796-f00ad385255f.png)

Vous �tes ensuite redirig�s vers le site **Eedomus** 

![2017-12-04_22h52_09](https://user-images.githubusercontent.com/4451322/33578194-fe856324-d945-11e7-8aa0-8c775ced2ae3.png)

Copiez le *code d'autorisation Oauth Netatmo* obtenu sur la page eedomus qui est rest�e ouverte dans votre browser Internet ainsi que les adresses *MAC du thermostat* et du *relais*. 

*Voici les diff�rents champs � renseigner:*

* [Optionnel] - Nom personnalis� : personnalisation du nom de votre p�riph�rique
* [Obligatoire] - Pi�ce : vous devez d�finir dans qu'elle pi�ce se trouve votre thermostat
* [Obligatoire] - Code d'autorisation Oauth Netatmo
* [Obligatoire] - Adresse MAC du thermostat Netatmo
* [Obligatoire] - Adresse MAC du relais Netatmo
* [Optionnel] - Mode manuel : personnaliser la dur�e de vos consignes manuelles
* [Optionnel] - Informations signal wifi du Relais : choisissez si vous souhaitez cr�er ce module
* [Optionnel] - Informations batterie thermostat : choisissez si vous souhaitez cr�er ce module
* [Optionnel] - Informations signal radio (RF) : choisissez si vous souhaitez cr�er ce module

Plusieurs modules sont cr��s sur votre box eedomus, ainsi que le script Netatmo. 

![2017-12-04_22h56_55](https://user-images.githubusercontent.com/4451322/33578322-7711a08c-d946-11e7-9258-35377eff4dc4.png)


![alt text](https://img.shields.io/github/release/Thibautg16/NetatmoThermostatApp.svg?style=for-the-badge)
![alt text](https://img.shields.io/github/license/Thibautg16/NetatmoThermostatApp.svg?style=for-the-badge)
![alt text](https://img.shields.io/badge/Status-Prod-green.svg?style=for-the-badge)
![alt text](https://img.shields.io/badge/twitter-@Thibautg16-blue.svg?style=for-the-badge)
