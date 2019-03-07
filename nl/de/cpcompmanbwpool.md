---

copyright:

  years: 1994, 2019

lastupdated: "2019-02-25"

keywords: bandwidth pool, bandwidth usage, Add Servers list, optimizing badwidth 

subcollection: customer-portal 

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:tip: .tip}
{:screen: .screen}
{:new_window: target="_blank"}


# Bandbreitennutzung optimieren
{: #cp_manbdwpool}

Für Netzverkehr im öffentlichen Datennetz, der von IBM Cloud-Rechenzentren auf der ganzen Welt abgeht, werden Gebühren für die abgehende Bandbreite berechnet. Die Kosten hängen davon ab, wo sich die Ressource befindet, von der die Daten übertragen werden, welche Datenmenge ausgegeben wird und zu welcher Bandbreitenzuteilung Ihre erworbenen IBM Cloud-Produkte berechtigt sind. 
{:shortdesc} 

Kunden können die Bandbreitennutzung optimieren, indem sie die gesamte Bandbreite für Server in einem Bandbreitenpool zusammenfassen. Bandbreitenüberschreitungen für Server in einem Bandbreitenpool werden als Summe aufaddiert und Überschreitungen nur dann berechnet, wenn die gesamte Bandbreite aller Server die insgesamt für alle Server zugeordnete Bandbreite überschreitet. Dies steht im Gegensatz zur Messung auf der Ebene einzelner Server. 

Die Pooldefinitionen sind in der folgenden Tabelle aufgeführt: 

| Pool      | Standort(e)          |
| ------------- |:-------------:|
| USA    | DAL01<br/><br/>DAL02<br/><br/>DAL04<br/><br/>DAL07<br/><br/>DAL09<br/><br/>DAL10<br/><br/>DAL12<br/><br/>DAL13<br/><br/>HOU02<br/><br/>MON01<br/><br/>SEA01<br/><br/>SJC01<br/><br/>SJC03<br/><br/>SJC04<br/><br/>TOR01<br/><br/>WDC01<br/><br/>WDC04<br/><br/>WDC06<br/><br/>WDC07|
| Amsterdam & London | AMS01<br/><br/>AMS03<br/><br/>LON01<br/><br/>LON02<br/><br/>LON04<br/><br/>LON05<br/><br/>LON06<br/><br/>PAR01 |
| Australien | MEL01<br/><br/>SYD01<br/><br/>SYD04<br/><br/>SYD05 |
| Brasilien | SAO01 |
| Frankfurt | FRA02<br/><br/>FRA04<br/><br/>FRA05 |
| Indien | CHE01 |
| Italien | MIL01 |
| Südkorea | SEO01 | 
| Mexiko | MEX01 | 
| Norwegen | OSL01 | 
| Singapur, Hongkong & Tokio | HKG02<br/><br/>SNG01<br/><br/>TOK02<br/><br/>TOK04<br/><br/>TOK05 |
{:caption="Tabelle 1. Definitionen von Poolzusammenschlüssen" caption-side="top"}


## Bandbreitenpool ändern
{: #cp_modbdwpool}

Nachdem ein Bandbreitenpool erstellt wurde, können Sie als berechtigter Benutzer jederzeit auf den Pool zugreifen. Sie greifen auf den Bandbreitenpool zu, um die dem Pool zugeordneten Einheiten anzuzeigen, Einheiten zum Pool hinzuzufügen oder Einheiten aus dem Pool zu entfernen. Führen Sie zum Zugriff auf einen Pool die folgenden Schritte aus:

1. Melden Sie sich beim Kundenportal mit Ihren eindeutigen Berechtigungsnachweisen an.
2. Wählen Sie im Menü die Optionen **Netz** > **Bandbreite** > **Pools** aus, um auf das Fenster 'Bandbreitenpool' zuzugreifen.
3. Klicken Sie auf den **Poolnamen**, um auf den Pool zuzugreifen. Jede Einheit, die dem Pool zugeordnet ist, wird angezeigt.
4. Auf der Registerkarte **Ändern** können Sie den Pool umbenennen, eine Einheit hinzufügen oder eine Einheit aus dem Pool entfernen:
  * Zum Umbenennen des Pools geben Sie den neuen Poolnamen in das Feld ein, das den aktuellen Poolnamen enthält.
  * Zum Hinzufügen einer Einheit zum Pool wählen Sie in der Liste **Server hinzufügen** den Namen der Einheit aus und klicken Sie auf **Auswählen**.
  * Zum Entfernen einer Einheit aus dem Pool wählen Sie in der Liste **Server entfernen** die Einheit aus und klicken Sie anschließend auf **Auswählen**.
5. Klicken Sie auf **Rack ändern**.
6. Klicken Sie auf den Link **Alle Bandbreitenpools anzeigen**, um zum Fenster 'Bandbreitenpools' zurückzukehren.
