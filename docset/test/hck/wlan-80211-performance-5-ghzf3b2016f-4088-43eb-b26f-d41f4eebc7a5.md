---
author: joshbax-msft
title: WLAN 802.11 Performance 5 GHz
description: WLAN 802.11 Performance 5 GHz
MSHAttr:
- 'PreferredSiteName:MSDN'
- 'PreferredLib:/library/windows/hardware'
ms.assetid: dc9c79cb-2325-4c91-9cdd-91a68f687b12
---

# WLAN 802.11 Performance 5 GHz


This test suite verifies that 802.11n and 802.11ac network adapters meet required throughput metrics.

## Test details


<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Associated requirements</strong></p></td>
<td><p>Device.Network.WLAN.Base.ImplementIEEE802.11ac Device.Network.WLAN.Base.MeetPerformanceReq Device.Network.WLAN.CSBBase.ImplementIEEE802.11ac Device.Network.WLAN.CSBBase.MeetPerformanceReq</p>
<p>[See the device hardware requirements.](http://go.microsoft.com/fwlink/p/?linkid=254483)</p></td>
</tr>
<tr class="even">
<td><p><strong>Platforms</strong></p></td>
<td><p>Windows RT 8.1 Windows 8.1 x64 Windows 8.1 x86</p></td>
</tr>
<tr class="odd">
<td><p><strong>Expected run time</strong></p></td>
<td><p>~10 minutes</p></td>
</tr>
<tr class="even">
<td><p><strong>Categories</strong></p></td>
<td><p>Certification Reliability</p></td>
</tr>
<tr class="odd">
<td><p><strong>Type</strong></p></td>
<td><p>Manual</p></td>
</tr>
</tbody>
</table>

 

## Running the test


Before you run the test, complete the test setup as described in the test requirements: [Wireless LAN (802.11) Testing Prerequisites](wireless-lan--80211--testing-prerequisites.md).

During the test run, a WTT: Manual Task message box on the access point (AP) machine prompts the user to configure the 802.11 ac-capable-AP to each channel width that is being verified. You must configure the AP to use the 80 Mhz channel, then the 40 Mhz channel, and finally the 20 MHz channel.

## Troubleshooting


For troubleshooting information, see [Troubleshooting Wireless LAN (802.11) Tests](troubleshooting-wireless-lan--80211--tests.md).

## More information


### Parameters

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>Parameter</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>NumSpatialStreams</strong></p></td>
<td><p>The number of spatial streams for the radio.</p>
<p>Default value: 2</p></td>
</tr>
<tr class="even">
<td><p><strong>PhyType</strong></p></td>
<td><p>The PHY type of the wireless adapter (<em>ac</em> or <em>n</em>).</p>
<p>Default value: <em>ac</em></p></td>
</tr>
<tr class="odd">
<td><p><strong>SSID</strong></p></td>
<td><p>The SSID of the access point.</p>
<p>Default value: &lt;none&gt;</p></td>
</tr>
<tr class="even">
<td><p><strong>WPA2Key</strong></p></td>
<td><p>The WPA2 Personal key of the SSID, if encryption is used. (If encryption is used, it is assumed to be AES.)</p>
<p>Default value: &lt;blank&gt;</p></td>
</tr>
</tbody>
</table>

 

 

 





