---
title: "Headers (XMLA) | Microsoft Docs"
ms.custom: ""
ms.date: "03/14/2017"
ms.prod: analysis-services
ms.prod_service: "analysis-services, azure-analysis-services"
ms.component: ""
ms.reviewer: ""
ms.suite: "pro-bi"
ms.technology: 
  

ms.tgt_pltfrm: ""
ms.topic: "reference"
applies_to: 
  - "SQL Server 2016 Preview"
helpviewer_keywords: 
  - "XMLA, headers"
  - "SOAP headers [XML for Analysis]"
  - "XML for Analysis, headers"
  - "headers [XML for Analysis]"
ms.assetid: 36407b5c-d98d-47e4-8d36-d8896e15a748
caps.latest.revision: 14
author: "Minewiskan"
ms.author: "owend"
manager: "kfile"
---
# XML Elements - Headers
[!INCLUDE[ssas-appliesto-sqlas-aas](../../../includes/ssas-appliesto-sqlas-aas.md)]
  The XML for Analysis (XMLA) protocol uses XML elements within the SOAP header to manage protocol-level features, such as session support and the negotiation of supported features.  
  
## In This Section  
 The following topics describe the XMLA header elements implemented by [!INCLUDE[msCoName](../../../includes/msconame-md.md)] [!INCLUDE[ssNoVersion](../../../includes/ssnoversion-md.md)] [!INCLUDE[ssASnoversion](../../../includes/ssasnoversion-md.md)].  
  
|Method|Description|  
|------------|-----------------|  
|[BeginSession Element &#40;XMLA&#41;](../../../analysis-services/xmla/xml-elements-headers/beginsession-element-xmla.md)|Uses a SOAP header in a SOAP request message to start a new session on an instance of [!INCLUDE[ssASnoversion](../../../includes/ssasnoversion-md.md)].|  
|[EndSession Element &#40;XMLA&#41;](../../../analysis-services/xmla/xml-elements-headers/endsession-element-xmla.md)|Uses the SOAP header in a SOAP request message to end an existing session on an instance of [!INCLUDE[ssASnoversion](../../../includes/ssasnoversion-md.md)].|  
|[Session Element &#40;XMLA&#41;](../../../analysis-services/xmla/xml-elements-headers/session-element-xmla.md)|Uses the SOAP header in a SOAP request message to identify an existing, explicit session on an instance of [!INCLUDE[ssASnoversion](../../../includes/ssasnoversion-md.md)].|  
|[ProtocolCapabilities Element &#40;XMLA&#41;](../../../analysis-services/xmla/xml-elements-headers/protocolcapabilities-element-xmla.md)|Uses the SOAP header in a SOAP request message to identify protocol capabilities between an instance of [!INCLUDE[ssASnoversion](../../../includes/ssasnoversion-md.md)] and a client application.|  
  
## See Also  
 [XML Elements &#40;XMLA&#41;](http://msdn.microsoft.com/library/40ab2360-efb6-4ba6-bf23-e84964e51008)   
 [XML Data Types &#40;XMLA&#41;](../../../analysis-services/xmla/xml-data-types/xml-data-types-xmla.md)   
 [XML Elements &#40;XMLA&#41;](http://msdn.microsoft.com/library/40ab2360-efb6-4ba6-bf23-e84964e51008)  
  
  
