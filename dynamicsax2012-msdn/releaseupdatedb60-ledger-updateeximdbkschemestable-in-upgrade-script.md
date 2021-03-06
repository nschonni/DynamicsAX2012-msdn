﻿---
title: ReleaseUpdateDB60_Ledger.updateEximDBKSchemesTable_IN Upgrade Script
TOCTitle: ReleaseUpdateDB60_Ledger.updateEximDBKSchemesTable_IN Upgrade Script
ms:assetid: fa30d131-cb81-0eb8-c3f4-596f0097c8cc
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ720090(v=AX.60)
ms:contentKeyID: 49712396
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Ledger.updateEximDBKSchemesTable\_IN Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_Ledger</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>updateEximDBKSchemesTable_IN</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the EximDBKSchemesTable_IN table. The record IDs of the DimensionAttributeValueCombination table are now stored in place of the receivable account. The record IDs of the EximPorts_IN table is now stored in place of PortId.</p></td>
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
<td><p>General ledger</p></td>
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
<td><p>DIMENSIONATTRIBUTE</p></td>
</tr>
<tr class="even">
<td><p>DIMENSIONATTRIBUTEDIRCATEGORY</p></td>
</tr>
<tr class="odd">
<td><p>DIMENSIONATTRIBUTELEVELVALUE</p></td>
</tr>
<tr class="even">
<td><p>DIMENSIONATTRIBUTESET</p></td>
</tr>
<tr class="odd">
<td><p>DIMENSIONATTRIBUTESETITEM</p></td>
</tr>
<tr class="even">
<td><p>DIMENSIONATTRIBUTEVALUE</p></td>
</tr>
<tr class="odd">
<td><p>DIMENSIONATTRIBUTEVALUECOMBINATION</p></td>
</tr>
<tr class="even">
<td><p>DIMENSIONATTRIBUTEVALUECOMBINATIONSTATUS</p></td>
</tr>
<tr class="odd">
<td><p>DIMENSIONATTRIBUTEVALUEGROUP</p></td>
</tr>
<tr class="even">
<td><p>DIMENSIONATTRIBUTEVALUEGROUPCOMBINATION</p></td>
</tr>
<tr class="odd">
<td><p>DIMENSIONATTRIBUTEVALUEGROUPSTATUS</p></td>
</tr>
<tr class="even">
<td><p>DIMENSIONATTRIBUTEVALUESET</p></td>
</tr>
<tr class="odd">
<td><p>DIMENSIONATTRIBUTEVALUESETITEM</p></td>
</tr>
<tr class="even">
<td><p>DIMENSIONFINANCIALTAG</p></td>
</tr>
<tr class="odd">
<td><p>DIMENSIONHIERARCHY</p></td>
</tr>
<tr class="even">
<td><p>DIMENSIONHIERARCHYLEVEL</p></td>
</tr>
<tr class="odd">
<td><p>DIMENSIONVALUEGROUPJOURNALCONTROLSTATUS</p></td>
</tr>
<tr class="even">
<td><p>EXIMDBKSCHEMESTABLE_IN</p></td>
</tr>
<tr class="odd">
<td><p>EXIMPORTS_IN</p></td>
</tr>
<tr class="even">
<td><p>FINANCIALTAGCATEGORY</p></td>
</tr>
<tr class="odd">
<td><p>LEDGERPARAMETERS</p></td>
</tr>
<tr class="even">
<td><p>MAINACCOUNT</p></td>
</tr>
</tbody>
</table>

  


