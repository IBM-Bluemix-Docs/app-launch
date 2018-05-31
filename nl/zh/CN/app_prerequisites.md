---

copyright:
 years: 2017

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen:.screen}
{:codeblock:.codeblock}

# 先决条件
{: #prerequisites}
上次更新：2018 年 1 月 18 日
{: .last-updated}


## 创建 App Launch 服务实例
{: #prerequisites_1}

1. 在 [IBM Cloud 目录](https://console.ng.bluemix.net/catalog/)中，单击**移动** > **App Launch**。
2. 提供服务名称。
3. 单击**创建**。
4. 选择连接到其他现有应用程序，或者保持未绑定状态。


您可以选择创建绑定的服务或者未绑定的服务。绑定的服务连接到其他 IBM Cloud 应用程序，而未绑定的服务是独立的，未连接到其他应用程序。缺省情况下，App Launch 服务应用程序是未绑定的。

## 初始化应用程序
{: #prerequisites_app}

1. 单击**设置**。
1. 根据平台类型下载某个 SDK 的设置：
	- [iOS](https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-swift-applaunch)
	- [Android](https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-android-applaunch)

2. 复制配置密钥以初始化应用程序。使用应用程序私钥、应用程序 GUID、客户端私钥来配置应用程序并创建参与。

![SDK 和密钥](images/engagement_settings.gif)

## 创建功能部件
{: #prerequisites_2}

利用 {{site.data.keyword.engage_short}} 服务，可以创建功能部件并测试功能部件响应。 

要创建功能部件，请完成下列步骤：

![功能部件详细信息](images/feature_creation_animated.gif)

1. 在导航窗格中，单击**功能部件** > **创建新功能部件**。 

2. 使用相应的功能部件名称和描述来更新“创建新功能部件和度量值”表单。您还可以定义功能部件属性并添加度量值以测量参与的影响。单击**批量编辑**以通过编辑 JSON 来添加多个属性。

3. 单击**创建**。现在，新功能部件会显示在“功能部件”面板上。 

4. 功能部件开发后，请立即启用该功能部件。

5. 要支持将功能部件用作参与，请单击创建的功能部件。

6. 在“功能部件详细信息”窗口中，将功能部件的“更新状态”选择为**准备就绪**。

7. 单击**更新状态**。

8. 更新应用程序以在 iOS 或 Android 应用程序中包含新创建的属性和特征代码。 

9. 现在功能部件已准备就绪可以使用。

“功能部件详细信息”窗口具有将功能部件导出为 JSON 文件的选项，该文件可在客户端应用程序中用于装入缺省值。


## 创建受众
{: #prerequisites_2}

要创建受众，请完成下列步骤：

![创建受众](images/create_audience_animated.gif)

1. 创建受众属性。 

	单击**受众** > **创建属性**。

	提供以下值：

	- **名称**：提供属性的相应名称。
	- **描述**：属性的概要描述。
	- **类型**：选择属性类型。
	- **允许值**：输入您要使用的属性值。

    您可以根据需求选择创建多个受众属性，如下图中所示。
	
	
2. 创建受众。

	a. 单击**创建受众**。

	b. 在“新建受众”窗口中提供相应的名称和描述。

	c. 选择属性，然后单击**添加**。

    d. 从属性列表中选择所需选项。

	e. 单击**保存**。
	
	您现在可以创建参与。

<!-- You can now create an engagement using the [Feature Control](app_feature_toggle.html) option. -->
