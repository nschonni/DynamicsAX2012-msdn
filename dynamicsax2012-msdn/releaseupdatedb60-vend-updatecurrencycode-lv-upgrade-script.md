﻿---
title: ReleaseUpdateDB60_Vend.updateCurrencyCode_LV Upgrade Script
TOCTitle: ReleaseUpdateDB60_Vend.updateCurrencyCode_LV Upgrade Script
ms:assetid: 957b792e-f05f-4120-ca71-bd02e0ef2e85
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ686158(v=AX.60)
ms:contentKeyID: 49709862
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Vend.updateCurrencyCode\_LV Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_Vend</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>updateCurrencyCode_LV</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Migrate the DEL_CurrencyCode_LV field of the VendBankAccount table to the CurrencyCode field for all records where the LVDefaultBank value is equal to the NoYes::Yes value.</p></td>
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
<td><p>Accounts payable</p></td>
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
<td><p>VendBankAccount</p></td>
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
<th><p>From Table: VendBankAccount</p></th>
<th><p>To Table: VendBankAccount</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>CurrencyCode_LV</p></td>
<td><p>CurrencyCode</p></td>
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
<td><p>VendBankAccount</p></td>
<td><p>CurrencyCode_LV</p></td>
</tr>
</tbody>
</table>

  


