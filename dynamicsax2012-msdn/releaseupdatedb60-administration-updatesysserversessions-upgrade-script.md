﻿---
title: ReleaseUpdateDB60_Administration.updateSysServerSessions Upgrade Script
TOCTitle: ReleaseUpdateDB60_Administration.updateSysServerSessions Upgrade Script
ms:assetid: f299cc1c-7a0a-729e-b20a-80f06f7ec9b3
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ737469(v=AX.60)
ms:contentKeyID: 49712163
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Administration.updateSysServerSessions Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_Administration</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>updateSysServerSessions</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Adds the SysServerSessions table to the bulk copy exception list to skip it from being copied during pre-synchronization bulk copy operation.</p></td>
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
<td><p>Administration</p></td>
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
<td><p>ReleaseUpdateBulkCopyTableExceptions</p></td>
</tr>
</tbody>
</table>

  


