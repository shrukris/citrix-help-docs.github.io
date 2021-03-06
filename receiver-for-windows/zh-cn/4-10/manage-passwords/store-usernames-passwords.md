---
layout: leftnav
title: 存储用户名和密码
menu: subnav
category: 管理我的密码
---

如果贵公司启用了此功能，则 Single Sign-On 会在您打开受密码保护的 Web 站点或启动受密码保护的程序时自动执行检测。 如果您之前在 Single Sign-On 中存储过该 Web 站点或程序的用户名、密码或其他登录信息，Single Sign-On 会自动将您登录。

打开受密码保护的 Web 站点或启动受密码保护的程序时，如果尚未存储登录信息，则可以通过以下方法在 Single Sign-On 中存储您的登录信息，具体取决于贵公司启用的 Single Sign-On 功能：

* 如果 Single Sign-On 检测到您打开了一个受密码保护的 Web 站点或启动了一个受密码保护的程序，则将自动显示一个对话框，询问您是否希望存储此信息
* 如果 Single Sign-On 未检测到程序，您可以手动添加登录信息

Single Sign-On 将存储以下各项的相关登录信息：

* **基于 Windows 的程序：** 这些程序通常从“开始”菜单或桌面进行启动。 例如 Lotus Notes。
* **基于 Web 的程序或站点：** 这些程序或站点通常通过 Web 浏览器进行查看以及与之交互。 例如网上商店或基于 Web 的培训程序。

**重要：** Microsoft Internet Explorer（32 位版本）是 Single Sign-On 唯一支持的 Web 浏览器。

* **基于终端仿真器的程序：** 这些程序基于文本，通常与终端仿真器相关联。 这些程序的窗口通常以深色（例如绿色）作为背景色，以稍浅的相同颜色作为文本色。

**备注:** 请求的登录信息可能因程序而异。 在大多数情况下，您需要提供自己的用户名或 ID 以及密码。 如果您不知道系统要求您输入的信息，请联系贵公司的计算机技术支持人员。

## 自动存储登录信息

1. 打开一个受密码保护的 Web 站点或启动一个受密码保护的程序。 系统将显示该 Web 站点的登录页面或程序的登录对话框。
1. 在所显示的询问您是否希望 Single Sign-On 记住此 Web 站点或程序的密码的对话框中，单击**记住**。
1. 如果您要存储某个 Web 站点或基于 Web 的程序的登录信息，Web 站点登录窗口中用于提交登录信息的对话框和按钮周围可能会显示多个矩形。 在所显示的询问您是否选择了正确的框和按钮的对话框中，单击**是**。
1. 在**新建登录**对话框中，键入您的登录信息并单击**完成**。 新建登录对话框将关闭，您的登录信息将存储到 Single Sign-On 中，Single Sign-On 将您登录到相应的程序。

## 手动存储登录信息

1. 打开一个受密码保护的 Web 站点或启动一个受密码保护的程序。 系统将显示该 Web 站点的登录页面或程序的登录对话框。
1. 如果系统未显示询问您是否希望 Single Sign-On 记住此 Web 站点或程序的密码的对话框，请提示 Single Sign-On 允许您手动存储自己的登录信息： 在 Microsoft Windows 通知区域中（通常在任务栏的最右侧），右键单击 Citrix Receiver 图标，然后依次选择**密码** > **提交密码**。

**备注:** 此时贵公司可能已激活身份验证过程。 如果已激活，则请在出现提示时输入您的 Windows 用户名和密码。 （如果您使用智能卡或其他不需要输入用户名和密码的身份验证方法进行登录，则请在出现提示时使用这些方法验证您的身份。）

1. 在所显示的询问您是否希望 Single Sign-On 记住此 Web 站点或程序的密码的对话框中，单击**记住**。
1. 如果您要存储某个 Web 站点或基于 Web 的程序的登录信息，Web 站点登录窗口中用于提交登录信息的对话框和按钮周围将显示多个矩形。 在所显示的询问您是否选择了正确的框和按钮的对话框中，单击**是**。
1. 在**新建登录**对话框中，键入您的登录信息并单击**完成**。 **新建登录**对话框将关闭，您的登录信息将存储到 Single Sign-On 中，Single Sign-On 将您登录到相应的程序。

## 存储一个程序的多个用户名和密码

有时您可能拥有某个程序或 Web 站点的多个帐户。 例如：

* 您有权访问您部门的普通电子邮件帐户（称为访问请求）以及您自己的电子邮件帐户
* 您负责为两个项目购买材料，在供应商 Web 站点下，每个项目都有一个独立的帐户

如果贵公司启用了 Single Sign-On 的多个帐户功能，您可以为同一个程序或 Web 站点存储两组或多组帐户信息。 存储多组帐户信息后，Single Sign-On 将使用登录选择器，允许您挑选登录时要使用的一组登录信息。

## 添加 Single Sign-On 中已存储的多个程序和 Web 站点的其他密码

1. 在 Microsoft Windows 通知区域中（通常在任务栏的最右侧），右键单击 Citrix Receiver 图标，然后依次选择**密码** > **管理密码**。
1. 在“管理密码”窗口中，选择要向其中添加其他登录帐户的程序或 Web 站点。
1. 单击**复制**。
**注意**： 此时贵公司可能已激活身份验证过程。 如果已激活，则请在出现提示时输入您的 Windows 用户名和密码。 （如果您使用智能卡或其他不需要输入用户名和密码的身份验证方法进行登录，则请在出现提示时使用这些方法验证您的身份。）

列表中将额外列出该程序或 Web 站点。

1. 选择新列出的程序或 Web 站点，然后单击**编辑**。 系统将显示一个对话框，其中包含该程序或 Web 站点的登录信息。
1. 更改登录信息（如有必要）。
1. 在**应用程序名称**框中，修改程序名称或 Web 站点名称，以帮助您将其与该程序的其他实例区分开来。
1. 单击**确定**。

## 在有多个帐户的情况下进行登录

如果某个程序或 Web 站点有多个帐户，Single Sign-On 将启动登录选择器，允许您选择登录时要使用的帐户。

登录具有多个帐户（存储在 Single Sign-On 中）的程序或 Web 站点：

1. 启动该程序或 Web 站点。 系统将显示**登录选择器**对话框以及程序的登录页面。
1. 在**登录选择器**对话框中，单击相应的登录帐户，然后单击**确定**。 **登录选择器**对话框将关闭，Single Sign-On 将您登录到该程序或 Web 站点。

