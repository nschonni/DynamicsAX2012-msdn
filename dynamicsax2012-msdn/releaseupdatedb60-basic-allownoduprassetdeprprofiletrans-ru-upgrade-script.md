﻿---
title: ReleaseUpdateDB60_Basic.allowNoDupRAssetDeprProfileTrans_RU Upgrade Script
TOCTitle: ReleaseUpdateDB60_Basic.allowNoDupRAssetDeprProfileTrans_RU Upgrade Script
ms:assetid: 9d942324-15e7-e8d0-b912-5ba807c9d671
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ736629(v=AX.60)
ms:contentKeyID: 49710070
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Basic.allowNoDupRAssetDeprProfileTrans\_RU Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_Basic</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>allowNoDupRAssetDeprProfileTrans_RU</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the index DeprProfileTransIdx in the table RAssetDeprProfileTrans not to allow duplicate records.</p></td>
</tr>
</tbody>
</table>


## Affected Modules and Tables

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Affected Modules</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Fixed Asset</p></td>
</tr>
</tbody>
</table>


<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Affected Tables</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>RAssetDeprProfileTrans</p></td>
</tr>
</tbody>
</table>


## Remarks

After updating the RAssetDeprProfile surrogate key field with the value of the record ID field of the RAssetDeprProfile table, the DeprProfileTransIdx index is reset not to allow duplicate records.

  


