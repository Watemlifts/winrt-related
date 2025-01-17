---
Description: Contains the X.509 certificate subject field of the Signature element from the last provisioning attempt.
Search.Product: eADQiWindows 10XVcnh
title: Subject
ms.assetid: b570cbcd-b017-43f4-83d1-7023701622c7
author: mcleblanc
ms.author: markl
keywords: windows 10, uwp, schema, mobile broadband schema


ms.topic: reference
ms.date: 04/05/2017
---

# Subject


Contains the X.509 certificate subject field of the [**Signature**](https://msdn.microsoft.com/library/windows/apps/hh868330) element from the last provisioning attempt.

## Element hierarchy

<dl>
<dt><a href="element-carrierprovisioningresult.md">&lt;CarrierProvisioningResult&gt;</a></dt>
<dd>
<dl>
<dt><a href="element-signature.md">&lt;Signature&gt;</a></dt>
<dd><b>&lt;Subject&gt;</b></dd>
</dl>
</dd>
</dl>

## Syntax

``` syntax
<Subject>

  string

</Subject>
```

## Attributes and Elements


### Attributes

None.

### Child Elements

None.

### Parent Elements

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>Parent Element</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="element-signature.md">Signature</a> </td>
<td><p>Contains any errors from processing the <a href="https://msdn.microsoft.com/library/windows/apps/hh868330"><strong>Signature</strong></a>  element from the last provisioning attempt.</p></td>
</tr>
</tbody>
</table>

 

## Requirements

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Namespace</p></td>
<td><p>http://www.microsoft.com/networking/CarrierControlResults/v1</p></td>
</tr>
</tbody>
</table>

 

 



