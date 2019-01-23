# esx_gitrdone
## Description
ESX_GITRDONE is an RP construciton job built based on the latest (as of this build) esx_policejob.
* FEATURES:
	* Vehicle Shop
	* Invoicing
	* Large prop list

### Requirements
* Auto mode
  * [esx_billing](https://github.com/FXServer-ESX/fxserver-esx_billing)

* Player management (boss actions and armory with buyable weapons)
  * [esx_society](https://github.com/FXServer-ESX/fxserver-esx_society)
  * [esx_datastore](https://github.com/FXServer-ESX/fxserver-esx_datastore)


## Download & Installation



## Installation
- Import `esx_gitrdone.sql` in your database
- Add this in your server.cfg :

```
start esx_gitrdone
```
-  * If you want player management you have to set `Config.EnablePlayerManagement` to `true` in `config.lua`

# Legal
### License
Oringial code - [esx_policejob - police script for ESX](https://github.com/ESX-Org/esx_policejob)

Copyright (C) 2019 Chip Wickings

This program Is free software: you can redistribute it And/Or modify it under the terms Of the GNU General Public License As published by the Free Software Foundation, either version 3 Of the License, Or (at your option) any later version.

This program Is distributed In the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty Of MERCHANTABILITY Or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License For more details.

You should have received a copy Of the GNU General Public License along with this program. If Not, see http://www.gnu.org/licenses/.
