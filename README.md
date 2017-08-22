# fxserver-esx_policejob
FXServer ESX Police Job

[REQUIREMENTS]

* Auto mode
  * esx_billing => https://github.com/FXServer-ESX/fxserver-esx_billing

* Player management (boss actions and armory with buyable weapons)
  * esx_society => https://github.com/FXServer-ESX/fxserver-esx_society
  * esx_datastore => https://github.com/FXServer-ESX/fxserver-esx_datastore

[INSTALLATION]

1) CD in your resources/[esx] folder
2) Clone the repository
```
git clone https://github.com/FXServer-ESX/fxserver-esx_policejob esx_policejob
```
3) * Auto mode : Import esx_policejob_minimal.sql in your database
   * Player / Armory management : Import esx_policejob_full.sql in your database

4) Add this in your server.cfg :

```
start esx_policejob
```
5) * If you want player management you have to set Config.EnablePlayerManagement to true in config.lua
   * If you want armory management you have to set Config.EnableArmoryManagement to true in config.lua
   
   
   --[[
#####################################################################################################
CREATOR OF THIS MODS POLICE GUIZz THANKS TO YOU !
Jobs Police V2 Modifier by Super.Cool.Ninja #FXServer
UPDATE 22/08/2017 
[FR] [EN]
#####################################################################################################
--]]



- Nouvelle Tenues par grades dispo ainsi que quelque options comme une casquette ou porter un gilet par balle ...
- Nouvelle action disponible comme faire sortir le joueur d'un voiture, retirer son permis en item puis retirer son permis en code

- Nouvelle langue ajoutée Portugais
- New language added Portuguese
- Novo idioma adicionado Português

- New Outfits by grades available as well as some options like a cap or wear a bullet waistcoat ...

- New action available such as getting the player out of a car, withdrawing his license in item and then withdrawing his license in code


- Installation:

- Juste glisser le fichier esx_policejob dans [ESX] 
- Ajoutée le dans votre server.cfg
- Ajoutée le fichier sql


- Just drag the esx_policejob file into [ESX]
- Added it to your server.cfg
- Added sql file

-- EH VOILA  --