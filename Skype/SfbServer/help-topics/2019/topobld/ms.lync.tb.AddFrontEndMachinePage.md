---
title: "Add Front End Machine"
ms.reviewer: 
ms.author: serdars
author: SerdarSoysal
manager: serdars
audience: ITPro
ms.topic: article
f1.keywords:
- CSH
ms.custom:
- ms.lync.tb.AddFrontEndMachinePage
ms.prod: skype-for-business-itpro
ms.localizationpriority: medium
ms.assetid: e7fe2522-1bd2-416a-9dbb-51cacea9c6e0
ROBOTS: NOINDEX, NOFOLLOW
description: "Specify the fully qualified domain name (FQDN) of each computer that you want to add as a Front End Server in this pool. After adding a computer to the list, you can update the FQDN of the computer or remove it from the pool at any time prior to publishing the topology. After you publish the topology, changing the FQDN requires deleting the server in Topology Builder and then adding a new server to the pool with the new FQDN. For details about adding a Front End pool to the topology, see Define and Configure a Front End Pool in the Deployment documentation."
---

# Add Front End Machine

Specify the fully qualified domain name (FQDN) of each computer that you want to add as a Front End Server in this pool. After adding a computer to the list, you can update the FQDN of the computer or remove it from the pool at any time prior to publishing the topology. After you publish the topology, changing the FQDN requires deleting the server in Topology Builder and then adding a new server to the pool with the new FQDN. For details about adding a Front End pool to the topology, see [Define and Configure a Front End Pool](/previous-versions/office/lync-server-2013/lync-server-2013-define-and-configure-a-front-end-pool-or-standard-edition-server) in the Deployment documentation.

> [!IMPORTANT]
> Note that Topology Builder indicates that you can have up to 20 Front End Servers in a pool. The maximum supported number of servers is 12. You can have up to 20 statefull servers defined in the fabric, of which 12 can be active and online at any one time.