---
page_type: sample
languages:
- powerapps-comma
products:
- power-apps
- powerapps
- canvas
name: Expandable Navigation Power App Template
description: This Canvas Application is an example for a expandable navigation using Fluent UI icons. It also shows how a lightbox-styled pop up works. 
urlFragment: powerapps-expandable-navigation
ms.date: 4/26/2021
author: luisefreese
ms.author: pnp
level: beginner
ms.prod: power-apps
---

# Expandable Navigation Power App Template

## Summary

This Canvas Application is an example for a expandable navigation using [Fluent UI](https://developer.microsoft.com/fluentui#/styles/web/icons) icons. It also shows how a lightbox-styled pop up works. 

![navigation](./assets/preview.gif)  

## Applies to

* [Microsoft Power Apps](https://docs.microsoft.com/powerapps/)

## Compatibility

![Power Apps Source File Pack and Unpack Utility 0.20](https://img.shields.io/badge/Packing%20Tool-0.20-green.svg)
![Premium License](https://img.shields.io/badge/Premium%20License-Not%20Required-green.svg "Premium Power Apps license not required")
![Experimental Features](https://img.shields.io/badge/Experimental%20Features-No-green.svg "Does not rely on experimental features")
![On-Premises Connectors](https://img.shields.io/badge/On--Premises%20Connectors-No-green.svg "Does not use on-premise connectors")
![Custom Connectors](https://img.shields.io/badge/Custom%20Connectors-Not%20Required-green.svg "Does not use custom connectors")

## Authors

Solution|Author(s)
--------|---------
Expandable Navigation | [Luise Freese](https://github.com/LuiseFreese) ([@luisefreese](https://www.twitter.com/luisefreese))

## Version history

Version|Date|Comments
-------|----|--------
1.0|April 26, 2021|Initial release

## Features

This sample illustrates the following concepts:

* Building an expandable navigation
* Using Fluent UI icons
* Building a lightbox-style pop-up

## Prerequisites

None

## Data Sources
 
None

## Minimal Path to Awesome

* [Download](./solution/expandable-navigation.msapp) the `.msapp` from the `solution` folder
* Use the `.msapp` file using **File** > **Open** > **Browse** within Power Apps Studio.
* Save and Publish

## Using the Source Code

You can also use the [Power Apps CLI](https://docs.microsoft.com/powerapps/developer/data-platform/powerapps-cli) to pack the source code by following these steps::

* Clone the repository to a local drive
* Pack the source files back into `.msapp` file:
  ```bash
  pac canvas pack --sources pathtosourcefolder --msapp pathtomsapp
  ```
  Making sure to replace `pathtosourcefolder` to point to the path to this sample's `sourcecode` folder, and `pathtomsapp` to point to the path of this solution's `.msapp` file (located under the `solution` folder)
* Use the `.msapp` file using **File** > **Open** > **Browse** in Power Apps Studio.


## Disclaimer

**THIS CODE IS PROVIDED *AS IS* WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**


## Support

While we don't support samples, if you encounter any issues while using this sample, you can [create a new issue](https://github.com/pnp/sharing-is-caring/issues/new?assignees=&labels=Needs%3A+Triage+%3Amag%3A%2Ctype%3Abug-suspected&template=bug-report.yml&sample=expandable-navigation&authors=@luisefreese&title=expandable-navigation%20-%20).

For questions regarding this sample, [create a new question](https://github.com/pnp/sharing-is-caring/issues/new?assignees=&labels=Needs%3A+Triage+%3Amag%3A%2Ctype%3Abug-suspected&template=question.yml&sample=expandable-navigation&authors=@luisefreese&title=expandable-navigation%20-%20).

Finally, if you have an idea for improvement, [make a suggestion](https://github.com/pnp/sharing-is-caring/issues/new?assignees=&labels=Needs%3A+Triage+%3Amag%3A%2Ctype%3Abug-suspected&template=suggestion.yml&sample=expandable-navigation&authors=@luisefreese&title=expandable-navigation%20-%20).

## For more information

- [Companion blog post about this sample](https://m365princess.com/how-to-beautify-your-power-apps/)
- [Overview of creating apps in Power Apps](https://docs.microsoft.com/powerapps/maker/)
- [Power Apps canvas apps documentation](https://docs.microsoft.com/en-us/powerapps/maker/canvas-apps/)

<img src="https://telemetry.sharepointpnp.com/sharing-is-caring/samples/expandable-navigation" />


