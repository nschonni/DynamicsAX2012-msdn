﻿---
title: ReleaseUpdateDB60_Cust.updateEximCustInvoiceTrans_IN Upgrade Script
TOCTitle: ReleaseUpdateDB60_Cust.updateEximCustInvoiceTrans_IN Upgrade Script
ms:assetid: c0ae2925-99e2-dd82-dc4a-788686176e72
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ686786(v=AX.60)
ms:contentKeyID: 49710983
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Cust.updateEximCustInvoiceTrans\_IN Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_Cust</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>updateEximCustInvoiceTrans_IN</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the EximCustInvoiceTrans_IN table. The record IDs of Incentive scheme group, Exim Ports, Exim Product Group and Customs tariff code are now stored in place of the TariffCode, IncentiveSchemeGroup, PortId and ProductGroup field values.</p></td>
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
<td><p>Accounts receivable</p></td>
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
<td><p>CustomsTariffCodeTable_IN</p></td>
</tr>
<tr class="even">
<td><p>EximCustInvoiceTrans_IN</p></td>
</tr>
<tr class="odd">
<td><p>EximIncentiveSchemeGroup_IN</p></td>
</tr>
<tr class="even">
<td><p>EximPorts_IN</p></td>
</tr>
<tr class="odd">
<td><p>EximProductGroupTable_IN</p></td>
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
<th><p>From Table: EximIncentiveSchemeGroup_IN</p></th>
<th><p>To Table: EximCustInvoiceTrans_IN</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>RecId</p></td>
<td><p>EximIncentiveSchemeGroup</p></td>
</tr>
</tbody>
</table>


<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>From Table: EximPorts_IN</p></th>
<th><p>To Table: EximCustInvoiceTrans_IN</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>RecId</p></td>
<td><p>EximPorts</p></td>
</tr>
</tbody>
</table>


<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>From Table: EximProductGroupTable_IN</p></th>
<th><p>To Table: EximCustInvoiceTrans_IN</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>RecId</p></td>
<td><p>EximProductGroupTable</p></td>
</tr>
</tbody>
</table>


<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>From Table: CustomsTariffCodeTable_IN</p></th>
<th><p>To Table: EximCustInvoiceTrans_IN</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>RecId</p></td>
<td><p>CustomsTariffCodeTable</p></td>
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
<td><p>EximCustInvoiceTrans_IN</p></td>
<td><p>EximIncentiveSchemeGroup</p></td>
<td><p>RefRecId</p></td>
</tr>
<tr class="even">
<td><p>EximCustInvoiceTrans_IN</p></td>
<td><p>EximPorts</p></td>
<td><p>RefRecId</p></td>
</tr>
<tr class="odd">
<td><p>EximCustInvoiceTrans_IN</p></td>
<td><p>EximProductGroupTable</p></td>
<td><p>RefRecId</p></td>
</tr>
<tr class="even">
<td><p>EximCustInvoiceTrans_IN</p></td>
<td><p>CustomsTariffCodeTable</p></td>
<td><p>RefRecid</p></td>
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
<td><p>EximCustInvoiceTrans_IN</p></td>
<td><p>del_IncentiveSchemeGroup</p></td>
</tr>
<tr class="even">
<td><p>EximCustInvoiceTrans_IN</p></td>
<td><p>del_PortId</p></td>
</tr>
<tr class="odd">
<td><p>EximCustInvoiceTrans_IN</p></td>
<td><p>del_ProductGroup</p></td>
</tr>
<tr class="even">
<td><p>EximCustInvoiceTrans_IN</p></td>
<td><p>del_TariffCode</p></td>
</tr>
</tbody>
</table>

  


