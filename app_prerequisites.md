---

copyright:
 years: 2017

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen:.screen}
{:codeblock:.codeblock}

# Prerequisites
{: #prerequisites}
Last updated: 18 January 2018
{: .last-updated}


## Creating an App Launch service instance
{: #prerequisites_1}

1. In the [IBM Cloud Catalog](https://console.ng.bluemix.net/catalog/), click **Mobile** > **App Launch**.
2. Provide a Service name and a Credential name.
3. Choose to connect to other existing apps, or leave it unbound.
4. Click **Create**.

You can choose to create either a bound service or an unbound service. Bound services are connected to other IBM Cloud apps, while unbound services are standalone and not connected to other apps. App Launch service apps are unbound by default.

## Initializing your app
{: #prerequisites_app}

1. Click **Settings**.
1. Download either of the SDK's, based on your platform type:
	- [iOS](https://github.ibm.com/Engage/bms-clientsdk-ios-swift-engage)
	- [Android](https://github.ibm.com/Engage/bms-clientsdk-android-engage)

2. Copy the configuration keys to initialize your App. Use the App Secret, App GUID, and Client Secret to configure your app and create engagements.

![SDK and Keys](images/engagement_settings.gif)

## Creating a feature
{: #prerequisites_2}

The {{site.data.keyword.engage_short}} service allows you to create and test responses to features. 

To create a feature, complete the following steps: :

![Feature Details](images/feature_creation_animated.gif)

1. In the navigation pane, click **Features** > **Create New Feature** 

2. Update the Create New Feature and Metrics form with an appropriate feature name and description. You can also define the feature properties and add metrics to measure the impact of your engagement. Click **Bulk edit** to add multiple properties by editing the JSON.

3. Click **Create**. The new feature now appears on the Features panel. 

4. Enable the feature once it is developed.

5. To enable a feature to be used as an engagement, click the Feature that you have created.

6. In the Feature Details window, choose to Update Status of your feature to **Ready**.

7. Click **Update** Status.

8. Update your app to include the newly created attributes and feature codes in your iOS or Android App. 

9. The feature is now ready to be used.

The Feature Details window has an option to export the feature as a JSON file which can be used in the client application to load the default values.


## Creating an audience
{: #prerequisites_2}

To create an audience, complete the following steps:

![Create Audience](images/create_audience_animated.gif)

1. Create an audience attribute. 

	Click **Audience** > **Create Attribute**.

	Provide the following values:

	- **Name**: Provide an appropriate name for the attribute.
	- **Description**: A brief description on the attribute.
	- **Type**:	Choose the attribute type.
	- **Allowed values**: Enter the attribute values that you would want to use.

    You can choose to create multiple audience attributes, as listed in the following image, based on your requirement.
	
	
2. Create an audience.

	a. Click **Create Audience**.

	b. Provide an appropriate name and description on the New Audience window.

	c. Select an attribute, and click **Add**.

    d. Choose the required options from the listed attributes.

	e. Click **Save**.
	
	You can now create an engagement.

<!-- You can now create an engagement using the [Feature Control](app_feature_toggle.html) option. -->