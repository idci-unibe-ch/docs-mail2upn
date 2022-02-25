# Anmeldetypen

Für die Migration sind folgende Begriffe für Sie und bei der Kommunikation mit den Nutzenden wichtig.

`sAMAccountName`
:   ***ab12c345*** oder bei legacy Accounts ***emuster***  
    Der sAMAccountName wird häufig auch in Kombination mit der Domäne genutzt: CAMPUS\sAMAccountName

`User Principal Name (UPN)`
:   Der UPN sollte der primären E-Mail Adresse entsprechen und hat auch das Format einer E-Mail Adresse:  
    **vorname.nachname@unibe.ch**

`Legacy User Principal Name (Legacy UPN)`
:    Bisher wurde der UPN an der UniBE mit dem sAMAccountName gebildet:  
    **sAMAccountName@campus.unibe.ch** bspw. ***ab12c345@campus.unibe.ch*** oder ***emuster@campus.unibe.ch***

`SWITCH edu-ID`
:   Die SWITCH edu-ID ist ein von der UniBE unabhängiger Account mit eigenem Passwort.  
    Der Benutzername ist dabei eine beliebige, private oder geschäftliche E-Mail Adresse.  
    Für die Migration ist die SWITCH edu-ID nicht von Interesse.
  

## Übersicht

| Dienstleistung                                     	| Anmeldung mit Mail2UPN        | Anmeldung bisher            |
|----------------------------------------------------	|-------------------------------|-----------------------------|
| Adobe Cloud                                          	| UPN                           | Legacy UPN                  |
| Boris                                              	| SWITCH edu-ID                 | SWITCH edu-ID               |
| CampusCloud (Filr)                                 	| sAMAccountName                | sAMAccountName              |
| DesktopWeb (Inova)                                   	| UPN                           | Legacy UPN                  |
| eduroam WLAN[^1]                                    	| sAMAccountName@unibe.ch[^1]   | sAMAccountName@unibe.ch     |
| eForms                                             	| UPN                           | Legacy UPN                  |
| ILIAS                                              	| SWITCH edu-ID                 | SWITCH edu-ID               |
| KSL                                                	| SWITCH edu-ID                 | SWITCH edu-ID               |
| KTools                                             	| sAMAccountName                | sAMAccountName              |
| KVS                                                	| sAMAccountName                | sAMAccountName              |
| Mailclient                                         	| UPN                           | Legacy UPN                  |
| Netadmin                                           	| sAMAccountName                | sAMAccountName              |
| Office 365, Teams, OneDrive                        	| UPN                           | Legacy UPN                  |
| Plagscan                                           	| UPN                           | Legacy UPN                  |
| Selfservice Studierende                            	| SWITCH edu-ID                 | SWITCH edu-ID               |
| SLSP, Swiss Library Service Platform (swisscovery) 	| SWITCH edu-ID                 | SWITCH edu-ID               |
| Serviceportal                                      	| UPN                           | Legacy UPN                  |
| Softwareshop                                       	| SWITCH edu-ID                 | SWITCH edu-ID               |
| SUB Anmeldung                                      	| SWITCH edu-ID                 | SWITCH edu-ID               |
| SwitchTube                                         	| SWITCH edu-ID                 | SWITCH edu-ID               |
| Uniprint                                           	| sAMAccountName                | sAMAccountName              |
| Unisport                                           	| SWITCH edu-ID                 | SWITCH edu-ID               |
| VPN (Fortinet)                                      	| UPN                           | Legacy UPN                  |
| Webmail                                            	| UPN                           | Legacy UPN                  |
| Zeiterfassung (Bridge4ERP) via "Login"               	| campus\sAMAccountName         | campus\sAMAccountName       |
| Zeiterfassung (Bridge4ERP) via "Windows Login"       	| UPN                           | Legacy UPN                  |
| ZMS (CMS)                                            	| UPN                           | sAMAccountName              |
| zoom                                               	| UPN                           | Legacy UPN                  |


[^1]:
    eduroam ist ein Sonderfall bei welchem man sich schon früher mit @unibe.ch angemeldet hat.  
    Für die Nutzenden ist das leider verwirrend. Wir versuchen hier noch eine Lösung zu finden, damit zumindest die Anmeldung mit dem UPN möglich ist.