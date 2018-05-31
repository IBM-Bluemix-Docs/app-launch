---

copyright:
 years: 2017

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen:.screen}
{:codeblock:.codeblock}

# Prerequisiti
{: #prerequisites}
Ultimo aggiornamento: 18 gennaio 2018
{: .last-updated}


## Creazione di un'istanza del servizio App Launch
{: #prerequisites_1}

1. Nel [Catalogo IBM Cloud](https://console.ng.bluemix.net/catalog/), fai clic su **Mobile** > **App Launch**.
2. Fornisci un nome del servizio. 
3. Fai clic su **Create**.
4. Scegli di collegarti ad altre applicazioni esistenti o lascialo senza associazioni.


Puoi scegliere di creare un servizio associato o non associato. I servizi associati sono collegati ad altre applicazioni IBM Cloud, mentre i servizi non associati sono autonomi e non collegati ad altre applicazioni. Le applicazioni del servizio App Launch non sono collegate per impostazioni predefinita.

## Inizializzazione della tua applicazione
{: #prerequisites_app}

1. Fai clic su **Settings**.
1. Scarica uno degli SDK, in base al tuo tipo di piattaforma:
	- [iOS](https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-swift-applaunch)
	- [Android](https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-android-applaunch)

2. Copia le chiavi di configurazione per inizializzare la tua applicazione. Utilizza segreto applicazione, GUID applicazione e segreto client per configurare la tua applicazione e creare gli impegni.

![SDK e chiavi](images/engagement_settings.gif)

## Creazione di una funzione
{: #prerequisites_2}

Il servizio {{site.data.keyword.engage_short}} ti consente di creare e verificare le risposte alle funzioni. 

Per creare una funzione, completa la seguente procedura: 

![Dettagli funzione](images/feature_creation_animated.gif)

1. Nel pannello di navigazione, fai clic su **Features** > **Create New Feature** 

2. Aggiorna il modulo Create New Feature and Metrics con un nome e una descrizione della funzione appropriati. Puoi anche definire le proprietà della funzione e aggiungere metriche per misurare l'impatto del tuo impegno. Fai clic su **Bulk edit** per aggiungere più proprietà modificando il JSON.

3. Fai clic su **Create**. La nuova funzione viene ora visualizzata nel pannello Features. 

4. Abilitare la funzione una volta sviluppato. 

5. Per abilitare una funzione da utilizzare come un impegno, fai clic sulla funzione che hai creato.

6. Nella finestra dei dettagli della funzione, scegli di aggiornare lo stato della tua funzione in **Ready**.

7. Fai clic su **Update** stato.

8. Aggiorna la tua applicazione in modo che includa i codici della funzione e gli attributi appena creati nella tua applicazione iOS o Android. 

9. La funzione è ora pronta per essere utilizzata. 

La finestra Feature Details ha un'opzione per esportare la funzione come un file JSON che può essere utilizzato nell'applicazione client per caricare i valori predefiniti.


## Creazione dei destinatari
{: #prerequisites_2}

Per creare i destinatari, completa la seguente procedura:

![Crea destinatari](images/create_audience_animated.gif)

1. Crea un attributo dei destinatari. 

	Fai clic su **Audience** > **Create Attribute**.

	Fornisci i seguenti valori:

	- **Nome**: fornisci un nome appropriato per l'attributo.
	- **Descrizione**: una breve descrizione dell'attributo.
	- **Tipo**:	scegli il tipo di attributo.
	- **Valori consentiti**: immetti i valori dell'attributo che desideri utilizzare.

    Puoi scegliere di creare più attributi dei destinatari, come elencato nella seguente immagine, in base ai tuoi requisiti.
	
	
2. Crea i destinatari.

	a. Fai clic su **Create Audience**.

	b. Fornisci un nome e una descrizione appropriati nella finestra dei nuovi destinatari.

	c. Seleziona un attributo e fai clic su **Add**.

    d. Scegli le opzioni richieste dagli attributi elencati.

	e. Fai clic su **Save**.
	
	Puoi ora creare un impegno. 

<!-- You can now create an engagement using the [Feature Control](app_feature_toggle.html) option. -->
