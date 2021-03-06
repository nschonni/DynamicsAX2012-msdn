﻿---
title: ReleaseUpdateDB60_HRM.updateHRMCompVarAwardEmpl Upgrade Script
TOCTitle: ReleaseUpdateDB60_HRM.updateHRMCompVarAwardEmpl Upgrade Script
ms:assetid: 2f0f5433-0e9e-fab5-4b8b-2954ac51d904
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ736026(v=AX.60)
ms:contentKeyID: 49707441
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_HRM.updateHRMCompVarAwardEmpl Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_HRM</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>updateHRMCompVarAwardEmpl</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the DefaultDimension and Worker fields in the HRMCompVarAwardEmpl table.</p></td>
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
<td><p>Human Resources</p></td>
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
<td><p>HRMCompVarAwardEmpl</p></td>
</tr>
</tbody>
</table>


## Remarks

Updates the DefaultDimension fields in the HRMCompVarAwardEmpl table with the corresponding value from the record ID field of the DimensionAttributeValueSet table. Updates the Worker field in the HRMCompVarAwardEmpl table with the corresponding value from the record ID field in the HcmWorker table.

## Data Migration Section

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>From Table: HRMCompVarAwardEmpl</p></th>
<th><p>To Table: HRMCompVarAwardEmpl</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Dimention</p></td>
<td><p>DefaultDimension</p></td>
</tr>
<tr class="even">
<td><p>del_EmplId</p></td>
<td><p>Worker</p></td>
</tr>
</tbody>
</table>


## New Tables or Fields

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Table</p></th>
<th><p>Field</p></th>
<th><p>Extended Data Type</p>
<p>-or- Base Enum</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>HRMCompVarAwardEmpl</p></td>
<td><p>DefaultDimension</p></td>
<td><p>DimensionDefault</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p>Worker</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


## Deleted Tables or Fields

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Table</p></th>
<th><p>Field</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>HRMCompVarAwardEmpl</p></td>
<td><p>Dimension</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p>del_EmplId</p></td>
</tr>
</tbody>
</table>

  


