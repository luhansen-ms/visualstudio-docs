---
title: "How to: Add and Remove Items to SharePoint Features | Microsoft Docs"
description: Manually add and remove SharePoint project items to SharePoint features using Feature Designer in Visual Studio.
ms.custom: SEO-VS-2020
ms.date: "02/02/2017"
ms.topic: how-to
f1_keywords:
  - "VS.SharePointTools.RAD.FeatureDesigner"
dev_langs:
  - "VB"
  - "CSharp"
helpviewer_keywords:
  - "SharePoint development in Visual Studio, features"
author: John-Hart
ms.author: johnhart
manager: jmartens
ms.technology: sharepoint-development
ms.workload:
  - "office"
---
# How to: Add and remove items to SharePoint features

 [!INCLUDE [Visual Studio](~/includes/applies-to-version/vs-windows-only.md)]
  When you create a SharePoint solution, Visual Studio adds the default SharePoint project items to your Feature. Before deployment, you can add and remove SharePoint project items to modify the SharePoint Feature.

## Add SharePoint project items to a feature

#### To add SharePoint project items with the Feature Designer

1. Open the Feature Designer.

    For more information, see [How to: Customize a SharePoint feature](../sharepoint/how-to-customize-a-sharepoint-feature.md).

2. Add one or more items from the **Items in the Solution** list to the **Items in the Feature** list by performing one or more of the following steps:

   - Double-click each item that you want to add.

   - Choose an item that you want to add, and then choose the **Add** button (>).

   - Choose the **Add All** button (>>).

     The SharePoint Project Items appear in the **Items in the Feature** list.

## Remove SharePoint project items from a feature

#### To remove SharePoint items with the Feature Designer

1. Choose one or more items in the **Items in the Feature** list.

2. Choose the **Remove** button (<) to remove one item at a time, or choose the **Remove All** button (<<) to remove all items.

     The SharePoint Project Items appear in the **Items in the Solution** list.

## See also
- [Create SharePoint features](../sharepoint/creating-sharepoint-features.md)
- [Package and deploy SharePoint solutions](../sharepoint/packaging-and-deploying-sharepoint-solutions.md)
