---
title: "Component Naming"
description: "Provides information on disk and interface naming changes related to the change from FreeBSD storage and sharing in CORE to Linux in TrueNAS SCALE."
weight: 35
aliases:
tags:
 - scalemigrate
---

{{< toc >}}

TrueNAS SCALE incorporates all the major TrueNAS CORE storage and sharing features with a web interface based on Debian GNU/Linux.
Because SCALE shares the same UI as the FreeBSD-based TrueNAS CORE, users might notice there are similarities.
However, SCALE does incorporate some differences, primarily in component naming.

## Disks

TrueNAS Core utilizes a numerical listing of drives in a system.

![ComponentNamingDrivesCore](/images/SCALE/ComponentNamingDrivesCore.png "TrueNAS Core Drive Listing")

TrueNAS SCALE uses a lettered format for drive identification.  

![ComponentNamingDrivesSCALE](/images/SCALE/ComponentNamingDrivesSCALE.png "TrueNAS SCALE Drive Listing")

{{< hint type=note >}}
SCALE still labels NVMe drives with a numeric value.
{{< /hint >}}

## Interfaces

{{< include file="/_includes/NetworkPortIdentifications.md" >}}

See the [TrueNAS Systems](https://www.truenas.com/docs/hardware/) section for lists of the default port names for each platform.

{{< taglist tag="scalemigrate" depth="2" >}}