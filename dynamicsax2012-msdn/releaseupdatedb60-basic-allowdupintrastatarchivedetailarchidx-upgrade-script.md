﻿---
title: ReleaseUpdateDB60_Basic.allowDupIntrastatArchiveDetailArchIdx Upgrade Script
TOCTitle: ReleaseUpdateDB60_Basic.allowDupIntrastatArchiveDetailArchIdx Upgrade Script
ms:assetid: dee0c48e-f31b-b3cb-55d6-7a0785fee84b
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ737267(v=AX.60)
ms:contentKeyID: 49711709
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Basic.allowDupIntrastatArchiveDetailArchIdx Upgrade Script 


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
<td><p>allowDupIntrastatArchiveDetailArchIdx</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the ArchIdx index in the IntrastatArchiveDetail table to allow duplicate records.</p></td>
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
<td><p>Basic</p></td>
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
<td><p>IntrastatArchiveDetail</p></td>
</tr>
</tbody>
</table>


## Remarks

The IntrastatArchiveId field is replaced with the new IntrastatArchiveGeneral surrogate key field in the unique ArchIdx index. Initially this field contains no value. So the index is set to allow duplicates before the field is updated with the value of the record ID field of the IntrastatArchiveGeneral table.

  


