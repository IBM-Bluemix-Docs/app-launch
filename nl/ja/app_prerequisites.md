---

copyright:
 years: 2017

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen:.screen}
{:codeblock:.codeblock}

# 前提条件
{: #prerequisites}
最終更新日: 2017 年 10 月 13 日
{: .last-updated}


## App Launch サービス・インスタンスの作成
{: #prerequisites_1}

1. [IBM Cloud カタログ](https://console.ng.bluemix.net/catalog/)で、**「モバイル」** > **「App Launch」**をクリックします。
2. サービス名および資格情報名を入力します。
3. 他の既存アプリに接続することを選択するか、アンバインドのままにします。
4. **「作成」**をクリックします。


バインドされたサービスまたはアンバインドされたサービスのいずれかを作成することを選択できます。バインドされたサービスは他の IBM Cloud アプリに接続されています。一方、アンバインドされたサービスはスタンドアロンであり、他のアプリには接続されていません。App Launch サービス・アプリは、デフォルトでアンバインドされています。

## アプリの初期化
{: #prerequisites_app}

1. **「設定」**をクリックします。
1. プラットフォームのタイプに基づいて、いずれかの SDK をダウンロードします。
	- [iOS](https://github.ibm.com/Engage/bms-clientsdk-ios-swift-engage)
	- [Android](https://github.ibm.com/Engage/bms-clientsdk-android-engage)

2. アプリを初期化するため、構成鍵をコピーします。アプリ秘密鍵、アプリ GUID、およびクライアント秘密鍵を使用して、アプリの構成およびエンゲージメントの作成を行います。

![SDK および鍵](images/engagement_settings.gif)

## フィーチャーの作成
{: #prerequisites_2}

{{site.data.keyword.engage_short}} サービスを使用して、フィーチャーへの応答を作成してテストできます。 

フィーチャーを作成するには、以下の手順を実行します。

1. **「フィーチャーおよびメトリック (Features & Metrics)」** > **「フィーチャーの作成 (Create Feature)」**をクリックします。

2. 「新規フィーチャーおよびメトリックの作成 (Create New Feature and Metrics)」フォームを適切なフィーチャー名と説明で更新します。フィーチャー・プロパティーを定義し、エンゲージメントの影響を測定するためのメトリックを追加することもできます。

3. **「作成」**をクリックします。新規フィーチャーが「フィーチャーおよびメトリック (Features and Metrics)」パネルに表示されるようになります。
![新規フィーチャー](images/feature_creating.gif)

4. フィーチャーがエンゲージメントとして使用されるようにするため、作成したフィーチャーをクリックします。

5. 「フィーチャー詳細 (Feature Details)」ウィンドウで、フィーチャーの「状況の更新 (Update Status)」で**「レディー (Ready)」**を選択します。
![フィーチャー詳細](images/feature_details.gif)

6. **「状況の更新 (Update Status)」**をクリックします。

7. iOS アプリまたは Android アプリに新しく作成された属性およびフィーチャー・コードを含むようにアプリを更新します。 

8. これでフィーチャーを使用する準備ができました。
![使用する準備ができたフィーチャー](images/feature_multiple_1.gif)


## オーディエンスの作成
{: #prerequisites_2}

オーディエンスを作成するには、以下の手順を実行します。

1. オーディエンス属性を作成します。 

	a. **「オーディエンス (Audience)」** > **「オーディエンス属性の作成 (Create Audience Attribute)」**をクリックします。

	b. 以下の値を入力します。

	- **名前**: 属性の適当な名前を入力します。
	- **説明**: 属性の簡単な説明。
	- **タイプ**:	属性タイプを選択します。
	- **許可される値**: 使用する属性値を入力します。

	![オーディエンス属性](images/audience_attribute_creation.gif)

	次の図で示すように、要件に応じて複数のオーディエンス属性を作成することを選択できます。
	
	![オーディエンス属性](images/audience_attributes.gif)


2. オーディエンスを作成します。

	a. **「オーディエンスの作成 (Create Audience)」**をクリックします。

	b. 「新規オーディエンス (New Audience)」ウィンドウで、適切な名前と説明を入力します。

	c. 属性を選択し、**「追加」**をクリックします。

	![オーディエンス属性](images/audience_platforms.gif)

	d. リストされた属性から、必要なオプションを選択します。

	e. **「保存」**をクリックします。

これで、[Feature Control](app_feature_toggle.html) オプションを使用してエンゲージメントを作成できるようになりました。
