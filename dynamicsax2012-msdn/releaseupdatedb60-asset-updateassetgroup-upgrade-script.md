﻿---
title: ReleaseUpdateDB60_Asset.updateAssetGroup Upgrade Script
TOCTitle: ReleaseUpdateDB60_Asset.updateAssetGroup Upgrade Script
ms:assetid: 43f77459-a97f-d9d1-842f-4a88945dcf9e
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ718897(v=AX.60)
ms:contentKeyID: 49707931
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Asset.updateAssetGroup Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_Asset</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>updateAssetGroup</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the number sequence references in the AssetGroup table.</p></td>
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
<td><p>AssetGroup</p></td>
</tr>
<tr class="even">
<td><p>NumberSequenceTable</p></td>
</tr>
<tr class="odd">
<td><p>NumberSequenceScope</p></td>
</tr>
</tbody>
</table>


## Data Migration Section

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>From Table: NumberSequenceTable</p></th>
<th><p>To Table: AssetGroup</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>RecId</p></td>
<td><p>AutoNumberSequenceTable</p></td>
</tr>
<tr class="even">
<td><p>RecId</p></td>
<td><p>BarcodeNumberSequenceTable</p></td>
</tr>
</tbody>
</table>

  


