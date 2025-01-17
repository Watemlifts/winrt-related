---
author: mcleanbyron
title: desktop3:Device
description: Defines the device information of an AutoPlayHandler.
ms.author: mcleans
ms.date: 10/10/2017
ms.topic: reference


keywords: windows 10, uwp, schema, manifest, desktop, extension 
---

# desktop3:Device
Defines the device information of an AutoPlayHandler.


## Element Hierarchy
<dl>
<dt><a href="element-package.md">&lt;Package&gt;</a></dt>
<dd>
<dl>
<dt><a href="element-applications.md">&lt;Applications&gt;</a></dt>
<dd>
<dl>
<dt><a href="element-application.md">&lt;Application&gt;</a></dt>
<dd>
<dl>
<dt><a href="element-1-extensions.md">&lt;Extensions&gt;</a></dt>
<dd>
<dl>
<dt><a href="element-desktop3-extension.md">&lt;desktop3:Extension&gt;</a></dt>
<dd>
<dl>
<dt><a href="element-desktop3-AutoPlayHandler.md">&lt;desktop3:AutoPlayHandler&gt;</a></dt>
<dd>
<dl>
<dt><a href="element-desktop3-invokeaction.md">&lt;desktop3:InvokeAction&gt;</a></dt>
<dd><b>&lt;desktop3:Device&gt;</b></dd>
</dl>
</dd>
</dl>
</dd>
</dl>
</dd>
</dl>
</dd>
</dl>
</dd>
</dl>
</dd>
</dl>


## Syntax
```syntax
<desktop3:Device DeviceEvent    = A string between 1 and 255 characters in length. Backward slashes ('\') are not allowed.
                 HWEventHandler = A GUID in the form xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx.
                 InitCmdLine?   = A string between 1 and 255 characters in length. />
```

### Key
`?` optional (zero or one)

## Attributes
| Attribute | Description | Data type | Required |
|-----------|-------------|-----------|----------|
| DeviceEvent | The name of a content event raised when a volume device such as a camera memory card, USB drive, or DVD is inserted into the PC. | A string between 1 and 255 characters in length. Backward slashes ('\') are not allowed. | Yes |
| HWEventHandler | The Class ID of the app that implements the [IHWEventHandler](https://msdn.microsoft.com/library/windows/desktop/bb775492.aspx) interface. | A GUID in the form xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx. | Yes |
| InitCmdLine | A string parameter that should be passed into the [Initialize](https://msdn.microsoft.com/library/windows/desktop/bb775495.aspx) method of the [IHWEventHandler](https://msdn.microsoft.com/library/windows/desktop/bb775492.aspx) interface. | A string between 1 and 255 characters in length. | No |

## Requirements

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Namespace</p></td>
<td><p>http://schemas.microsoft.com/appx/manifest/desktop/windows10/3</p></td>
</tr>
</tbody>
</table>