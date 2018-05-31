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
Letzte Aktualisierung: 18. Januar 2018
{: .last-updated}


## App Launch-Serviceinstanz erstellen
{: #prerequisites_1}

1. Klicken Sie im [IBM Cloud-Katalog](https://console.ng.bluemix.net/catalog/) auf **Mobile** > **App Launch**.
2. Geben Sie einen Servicenamen an.
3. Klicken Sie auf **Erstellen**.
4. Stellen Sie optional eine Verbindung zu anderen vorhandenen Apps her oder erstellen Sie keine Servicebindung.


Sie können auswählen, ob Sie einen Service mit oder ohne Bindung erstellen möchten. Services mit Bindung sind mit anderen IBM Cloud-Apps verbunden, Services ohne Bindung sind eigenständig und nicht mit anderen Apps verbunden. Apps des App Launch-Service weisen standardmäßig keine Bindung auf.

## App initialisieren
{: #prerequisites_app}

1. Klicken Sie auf **Einstellungen**.
1. Laden Sie abhängig vom verwendeten Plattformtyp eines der beiden SDKs herunter.
	- [iOS](https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-swift-applaunch)
	- [Android](https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-android-applaunch)

2. Kopieren Sie die Konfigurationsschlüssel zum Initialisieren der App. Verwenden Sie den geheimen App-Schlüssel, die App-GUID und den geheimen Clientschlüssel, um die App zu konfigurieren und Projekte zu erstellen.

![SDK und Schlüssel](images/engagement_settings.gif)

## Feature erstellen
{: #prerequisites_2}

Der {{site.data.keyword.engage_short}}-Service ermöglicht es Ihnen, Features zu erstellen und die Reaktionen auf Features zu testen. 

Führen Sie die folgenden Schritte aus, um ein Feature zu erstellen:

![Featuredetails](images/feature_creation_animated.gif)

1. Klicken Sie im Navigationsbereich auf **Features** > **Neues Feature erstellen**. 

2. Aktualisieren Sie das Formular für das Erstellen neuer Features und Metriken mit einem entsprechenden Featurenamen und einer Beschreibung. Sie können auch die Eigenschaften des Features definieren und Metriken zum Messen der Wirkung Ihres Projekts hinzufügen. Klicken Sie auf **Massenbearbeitung**, um mehrere Eigenschaften durch Bearbeiten der JSON-Datei hinzuzufügen.

3. Klicken Sie auf **Erstellen**. Das neue Feature ist nun in der Featureanzeige enthalten. 

4. Aktivieren Sie das Feature nach der Entwicklung.

5. Klicken Sie auf das erstellte Feature, um es für die Verwendung als Projekt zu aktivieren.

6. Aktualisieren Sie im Fenster mit den Featuredetails den Status Ihres Features so, dass er **Bereit** lautet.

7. Klicken Sie auf **Status aktualisieren**.

8. Aktualisieren Sie die App so, dass die neu erstellten Attribute und Feature-Codes in die iOS- oder Android-App aufgenommen werden. 

9. Das Feature ist nun zur Verwendung bereit.

Das Fenster mit den Featuredetails enthält eine Option für den Export des Features als JSON-Datei, die in der Clientanwendung verwendet werden kann, um die Standardwerte zu laden.


## Zielgruppe erstellen
{: #prerequisites_2}

Führen Sie die folgenden Schritte aus, um eine Zielgruppe zu erstellen:

![Zielgruppe erstellen](images/create_audience_animated.gif)

1. Erstellen Sie ein Zielgruppenattribut. 

	Klicken Sie auf **Zielgruppe** > **Attribut erstellen**.

	Geben Sie die folgenden Werte an:

	- **Name**: Geben Sie einen entsprechenden Namen für das Attribut an.
	- **Beschreibung**: Eine kurze Beschreibung des Attributs.
	- **Typ**:	Attributtyp auswählen.
	- **Zulässige Werte**: Geben Sie die gewünschten Attributwerte ein.

    Abhängig von den jeweiligen Anforderungen können Sie mehrere Zielgruppenattribute erstellen, wie in der folgenden Abbildung dargestellt.
	
	
2. Erstellen Sie eine Zielgruppe.

	a. Klicken Sie auf **Zielgruppe erstellen**.

	b. Geben Sie einen entsprechenden Namen und eine Beschreibung im Fenster für die neue Zielgruppe an.

	c. Wählen Sie ein Attribut aus und klicken Sie auf **Hinzufügen**.

    d. Wählen Sie die erforderlichen Optionen aus den aufgeführten Attributen aus.

	e. Klicken Sie auf **Speichern**.
	
	Sie können nun ein Projekt erstellen.

<!-- You can now create an engagement using the [Feature Control](app_feature_toggle.html) option. -->
