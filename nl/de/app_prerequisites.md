---

copyright:
 years: 2017

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen:.screen}
{:codeblock:.codeblock}

# Voraussetzungen
{: #prerequisites}
Letzte Aktualisierung: 13. Oktober 2017
{: .last-updated}


## App Launch-Serviceinstanz erstellen
{: #prerequisites_1}

1. Klicken Sie im [IBM Bluemix-Katalog](https://console.ng.bluemix.net/catalog/) auf **Mobile** > **App Launch**.
2. Geben Sie einen Servicenamen und einen Berechtigungsnachweisnamen an.
3. Stellen Sie optional eine Verbindung zu anderen vorhandenen Apps her oder erstellen Sie keine Servicebindung.
4. Klicken Sie auf **Erstellen**.


Sie können auswählen, ob Sie einen Service mit oder ohne Bindung erstellen möchten. Services mit Bindung sind mit anderen Bluemix-Apps verbunden, Services ohne Bindung sind eigenständig und nicht mit anderen Apps verbunden. Apps des App Launch-Service weisen standardmäßig keine Bindung auf.

## App initialisieren
{: #prerequisites_app}

1. Klicken Sie auf **Einstellungen**.
1. Laden Sie abhängig vom verwendeten Plattformtyp eines der beiden SDKs herunter.
	- [iOS](https://github.ibm.com/Engage/bms-clientsdk-ios-swift-engage)
	- [Android](https://github.ibm.com/Engage/bms-clientsdk-android-engage)

2. Kopieren Sie die Konfigurationsschlüssel zum Initialisieren der App. Verwenden Sie den geheimen App-Schlüssel, die App-GUID un den geheimen Clientschlüssel, um die App zu konfigurieren und Projekte zu erstellen.

![SDK und Schlüssel](images/engagement_settings.gif)

## Feature erstellen
{: #prerequisites_2}

Der {{site.data.keyword.engage_short}}-Service ermöglicht es Ihnen, Features zu erstellen und die Reaktionen auf Features zu testen. 

Führen Sie die folgenden Schritte aus, um ein Feature zu erstellen:

1. Klicken Sie auf **Features & Metriken** > **Feature erstellen**.

2. Aktualisieren Sie das Formular für das Erstellen neuer Features und Metriken mit einem entsprechenden Featurenamen und einer Beschreibung. Sie können auch die Eigenschaften des Features definieren und Metriken zum Messen der Wirkung Ihres Projekts hinzufügen.

3. Klicken Sie auf **Erstellen**. Das neue Feature wird nun in der Anzeige für Features und Metriken aufgeführt.
![Neue Features](images/feature_creating.gif)

4. Klicken Sie auf das erstellte Feature, um es für die Verwendung als Projekt zu aktivieren.

5. Aktualisieren Sie im Fenster mit den Featuredetails den Status Ihres Features so, dass er **Bereit** lautet.
![Featuredetails](images/feature_details.gif)

6. Klicken Sie auf **Status aktualisieren**.

7. Aktualisieren Sie die App so, dass die neu erstellten Attribute und Feature-Codes in die iOS- oder Android-App aufgenommen werden. 

8. Das Feature ist nun zur Verwendung bereit.
![Feature zur Verwendung bereit](images/feature_multiple_1.gif)


## Zielgruppe erstellen
{: #prerequisites_2}

Führen Sie die folgenden Schritte aus, um eine Zielgruppe zu erstellen:

1. Erstellen Sie ein Zielgruppenattribut. 

	a. Klicken Sie auf **Zielgruppe** > **Zielgruppenattribut erstellen**.

	b. Geben Sie die folgenden Werte an:

	- **Name**: Geben Sie einen entsprechenden Namen für das Attribut an.
	- **Beschreibung**: Eine kurze Beschreibung des Attributs.
	- **Typ**:	Attributtyp auswählen.
	- **Zulässige Werte**: Geben Sie die gewünschten Attributwerte ein.

	![Zielgruppenattribute](images/audience_attribute_creation.gif)

	Abhängig von den jeweiligen Anforderungen können Sie mehrere Zielgruppenattribute erstellen, wie in der folgenden Abbildung dargestellt.
	
	![Zielgruppenattribute](images/audience_attributes.gif)


2. Erstellen Sie eine Zielgruppe.

	a. Klicken Sie auf **Zielgruppe erstellen**.

	b. Geben Sie einen entsprechenden Namen und eine Beschreibung im Fenster für die neue Zielgruppe an.

	c. Wählen Sie ein Attribut aus und klicken Sie auf **Hinzufügen**.

	![Zielgruppenattribute](images/audience_platforms.gif)

	d. Wählen Sie die erforderlichen Optionen aus den aufgeführten Attributen aus.

	e. Klicken Sie auf **Speichern**.

Sie können nun mithilfe der Option [Feature Control](app_feature_toggle.html) ein Projekt erstellen.
