# Migrationsablauf

Bei Organisationseinheiten werden immer erst die IT-Technikverantwortlichen migriert (= IT-Staff). Bei Bedarf können einige Testpersonen (max. 5) mitmigriert werden.  

Diese Migrationen werden immer **von Dienstag bis Donnerstag** durchgeführt.  

Der ServiceDesk macht dabei um **15:30** die Anpassungen im HR wodurch diese **automatisch um 18:15 vom IAM in das Active Directory provisioniert** werden.  
Über Nacht gleichen sich dann die meisten Systeme der UniBE damit ab, so dass die Migration am nächsten Morgen um 08:00 als abgeschlossen angesehen werden kann.  

Die restlichen Nutzenden eines Instituts werden immer von **Dienstag bis Donnerstag um 13:30** umgestellt.

!!! warning
    Institute welche das HIN-Gateway nutzen können derzeit noch nicht migriert werden.

## Kontaktaufnahme

### Sie kontaktieren uns

Dies ist der Idealfall, denn hier nennen Sie uns Ihren Wunschtermin und wir versuchen diesen sofern möglich einzuhalten.  

Kontaktadresse: mail2upn.id@unibe.ch

### Wir kontaktieren Sie

Da wir das Projekt für künftige Dienstleistungen zum Abschluss bringen müssen, werden wir ab einem bestimmten Zeitpunkt Sie kontaktieren.  
In diesem Fall müssen wir einen Migrationstermin festlegen, werden aber sofern noch möglich auch dort etwaige Ausweichdaten mit Ihnen diskutieren.

## Migration der IT-Verantwortlichen

Der erste Schritt besteht in der Migration von Ihnen, also den Technikverantwortlichen einer Organisationseinheit.  
Bei Bedarf können Sie gleichzeitig auch noch bis zu 5 Nutzende migrieren um spezielle Gegebenheiten testen zu können.  

Diese Phase ist insbesondere für Sie wichtig, damit Sie Ihre internen aber auch unsere Systeme mit dem neuen Anmeldenamen testen können. Dies gibt Ihnen die Sicherheit, dass die Migration hoffentlich ohne grössere Probleme durchgeführt werden kann und Sie für die Anfragen der Nutzenden vor und nach der Migration gewappnet sind.  

Nehmen Sie sich daher genug Zeit für diese Tests und kontaktieren Sie uns bei Fragen oder Problemen.

Für solch kleine Migrationen sind wir flexibel und können diese innerhalb weniger Tage durchführen. Beachten Sie aber unbedingt [die Checkliste](./migration-checklist-itstaff.md) und melden Sie uns die genutzten Systeme.

## Festlegen eines Migrationstermins und Migrationslisten

Sind die Tests abgeschlossen und Sie bereit für die Migration melden Sie sich wieder bei uns.  
Wir legen dann einen passenden Migrationstermin zusammen mit Ihnen fest und stellen Ihnen eine Migrationsliste zur Verfügung, welcher Sie die Account-Anpassungen für Ihre Mitarbeitenden entnehmen können.  

Dies ist gleichzeitig die letzte Möglichkeit für Korrekturen oder Anpassungen der E-Mail Adresse / UPN.  
Wir empfehlen bspw. mit Personen Kontakt aufzunehmen, welche eine Nummerierung erhalten (vorname.nachname2@unibe.ch) und mit Ihnen die Möglichkeiten [gemäss den Namenskonventionen](../conventions/naming-conventions.md) zu besprechen.

Da wir die UPNs nicht reservieren können sollten ist es von Vorteil, wenn zwischen dem Ausstellen der Liste und der Migration nicht zuviel Zeit liegt.  
Wir müssen zudem eine Woche vor der Migration die Liste an die diversen Dienstleistungsverantwortlichen weiterleiten.  
Ab diesem Zeitpunkt sind keine Anpassungen mehr möglich.


## Durchführung der Migration

Zum definierten Datum werden wir ab 13:00 mit den Anpassungen im HR System beginnen.  
Ab 13:30 werden diese Anpassungen dann in das Active Directory, Exchange und Azure Active Directory übertragen.  

Die Nutzenden werden sich somit ab etwa 14:00 (uns fehlen noch die Erfahrungswerte) mit dem neuen UPN an Ihren Clients, dem Mail/Webmail und allen an Microsoft Identity angebundenen Systemen wie Office 365, Teams, eForms, Adobe, etc. anmelden können.  

Zu diesem Zeitpunkt beginnen dann auch die Dienstleistungsbetreibenden der zenralen Dienstleistungen mit den Synchronisierungen und Anpassungen.  

Spätestens am nächsten Morgen kann die Migration als abgeschlossen betrachtet werden.

## Migration von geteilten- oder Ressourcen-Mailboxen, Verteilerlisten und Forwards

Die Migration unpersönlicher Mailboxen, Verteilerlisten und Forwards ist unabhängig von der Migration der Mitarbeitenden.  

Bei Bedarf können wir diese Objekte bereits vor der Mitarbeitenden-Migration durchführen. Ansonsten sehen wir eine Migration eine Woche nach der Mitarbeitenden-Migration vor.