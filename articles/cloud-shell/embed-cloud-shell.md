---
title: Embed Azure Cloud Shell | Microsoft Docs
description: Learn to embed Azure Cloud Shell.
services: cloud-shell
documentationcenter: ''
author: jluk
manager: timlt
tags: azure-resource-manager
 
ms.assetid: 
ms.service: azure
ms.workload: infrastructure-services
ms.tgt_pltfrm: vm-linux
ms.devlang: na
ms.topic: article
ms.date: 12/11/2017
ms.author: juluk
---
# Embed Azure Cloud Shell

Embedding Cloud Shell enables developers and content writers to directly open Cloud Shell from a dedicated URL, [shell.azure.com](https://shell.azure.com). This immediately brings the full power of Cloud Shell's authentication, tooling, and up-to-date Azure CLI/Azure PowerShell tools to your users.

[![](https://shell.azure.com/images/launchcloudshell.png "Launch Azure Cloud Shell")](https://shell.azure.com)

## How-to

Integrate Cloud Shell's launch button into markdown files by copying the following:

```markdown
[![Launch Cloud Shell](https:shell.azure.com/images/launchcloudshell.png "Launch Cloud Shell")](https://shell.azure.com)
```

The HTML to embed a pop-up Cloud Shell is below:
```html
<a style="cursor:pointer" onclick='javascript:window.open("https://shell.azure.com", "_blank", "toolbar=no,scrollbars=yes,resizable=yes,menubar=no,location=no,status=no")'><image src="https://shell.azure.com/images/launchcloudshell.png" /></a>
```

## Next steps
[Bash in Cloud Shell quickstart](quickstart.md)<br>
[PowerShell in Cloud Shell quickstart](quickstart-powershell.md)