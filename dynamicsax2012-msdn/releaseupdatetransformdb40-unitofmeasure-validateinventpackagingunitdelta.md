﻿---
title: ReleaseUpdateTransformDB40_UnitOfMeasure.validateInventPackagingUnitDelta
TOCTitle: ReleaseUpdateTransformDB40_UnitOfMeasure.validateInventPackagingUnitDelta
ms:assetid: 0bdbadec-1138-890b-fa84-56b7e7a9cc7c
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ735661(v=AX.60)
ms:contentKeyID: 49706572
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateTransformDB40\_UnitOfMeasure.validateInventPackagingUnitDelta 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateTransformDB40_UnitOfMeasure</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>validateInventPackagingUnitDelta</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Validates that there will be no unique index violations because of potential units merging in the &lt;c&gt;InventPackagingUnit&lt;/c&gt; and &lt;c&gt;InventPackagingUnitMaterial&lt;/c&gt; tables.</p></td>
</tr>
<tr class="even">
<td><p><strong>Script Type</strong></p></td>
<td><p>Pre-processing60: Live</p></td>
</tr>
<tr class="odd">
<td><p><strong>Ax Version</strong></p></td>
<td><p>4.01</p></td>
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
<td><p>Inventory management</p></td>
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
<td><p>InventPackagingUnitMaterial</p></td>
</tr>
<tr class="even">
<td><p>InventPackagingUnit</p></td>
</tr>
</tbody>
</table>

  


