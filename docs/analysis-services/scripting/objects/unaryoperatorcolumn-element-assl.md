---
title: "UnaryOperatorColumn Element (ASSL) | Microsoft Docs"
ms.custom: ""
ms.date: "03/06/2017"
ms.prod: analysis-services
ms.prod_service: "analysis-services"
ms.component: ""
ms.reviewer: ""
ms.suite: "pro-bi"
ms.technology: 
  

ms.tgt_pltfrm: ""
ms.topic: "reference"
apiname: 
  - "UnaryOperatorColumn Element"
apilocation: 
  - "http://schemas.microsoft.com/analysisservices/2003/engine"
apitype: "Schema"
applies_to: 
  - "SQL Server 2016 Preview"
f1_keywords: 
  - "UnaryOperatorColumn"
helpviewer_keywords: 
  - "UnaryOperatorColumn element"
ms.assetid: 10889e51-69e5-4f50-9749-ecbc66c247d3
caps.latest.revision: 34
author: "Minewiskan"
ms.author: "owend"
manager: "kfile"
---
# UnaryOperatorColumn Element (ASSL)
[!INCLUDE[ssas-appliesto-sqlas](../../../includes/ssas-appliesto-sqlas.md)]
  Defines the details of a column providing a unary operator.  
  
## Syntax  
  
```xml  
  
<DimensionAttribute>  
   ...  
   <UnaryOperatorColumn xsi:type="DataItem">...</UnaryOperatorColumn>  
   ...  
</DimensionAttribute>  
```  
  
## Element Characteristics  
  
|Characteristic|Description|  
|--------------------|-----------------|  
|Data type and length|[DataItem](../../../analysis-services/scripting/data-type/dataitem-data-type-assl.md)|  
|Default value|None|  
|Cardinality|0-1: Optional element that can occur once and only once.|  
  
## Element Relationships  
  
|Relationship|Element|  
|------------------|-------------|  
|Parent elements|[DimensionAttribute](../../../analysis-services/scripting/data-type/dimensionattribute-data-type-assl.md)|  
|Child elements|None|  
  
## Remarks  
 For more information about the **DataItem** type, including a table of Analysis Services Scripting Language (ASSL) objects and properties of the **DataItem** type, see [DataItem Data Type &#40;ASSL&#41;](../../../analysis-services/scripting/data-type/dataitem-data-type-assl.md).  
  
 The element that corresponds to the parent of **UnaryOperatorColumn** in the Analysis Management Objects (AMO) object model is <xref:Microsoft.AnalysisServices.DimensionAttribute>.  
  
## See Also  
 [Objects &#40;ASSL&#41;](../../../analysis-services/scripting/objects/objects-assl.md)  
  
  
