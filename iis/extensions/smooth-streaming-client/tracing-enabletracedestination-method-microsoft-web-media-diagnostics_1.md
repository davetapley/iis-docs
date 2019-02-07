---
title: Tracing.EnableTraceDestination Method  (Microsoft.Web.Media.Diagnostics)
TOCTitle: EnableTraceDestination Method
ms:assetid: M:Microsoft.Web.Media.Diagnostics.Tracing.EnableTraceDestination(Microsoft.Web.Media.Diagnostics.TraceDestination)
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.media.diagnostics.tracing.enabletracedestination(v=VS.95)
ms:contentKeyID: 46307617
ms.date: 05/31/2012
mtps_version: v=VS.95
f1_keywords:
- Microsoft.Web.Media.Diagnostics.Tracing.EnableTraceDestination
dev_langs:
- CSharp
- JScript
- VB
- FSharp
- c++
api_location:
- Microsoft.Web.Media.SmoothStreaming.dll
api_name:
- Microsoft.Web.Media.Diagnostics.Tracing.EnableTraceDestination
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# Tracing.EnableTraceDestination Method

Enables the trace destination that is specified by the destination parameter.

**Namespace:**  [Microsoft.Web.Media.Diagnostics](microsoft-web-media-diagnostics-namespace_1.md)  
**Assembly:**  Microsoft.Web.Media.SmoothStreaming (in Microsoft.Web.Media.SmoothStreaming.dll)

## Syntax

``` vb
'Declaration

Public Shared Sub EnableTraceDestination ( _
    destination As TraceDestination _
)
'Usage

Dim destination As TraceDestination

Tracing.EnableTraceDestination(destination)
```

``` csharp
public static void EnableTraceDestination(
    TraceDestination destination
)
```

``` c++
public:
static void EnableTraceDestination(
    TraceDestination destination
)
```

``` fsharp
static member EnableTraceDestination : 
        destination:TraceDestination -> unit 
```

``` jscript
public static function EnableTraceDestination(
    destination : TraceDestination
)
```

#### Parameters

  - destination  
    Type: [Microsoft.Web.Media.Diagnostics.TraceDestination](tracedestination-enumeration-microsoft-web-media-diagnostics_1.md)  
    A [TraceDestination](tracedestination-enumeration-microsoft-web-media-diagnostics_1.md) enumeration object that specifies the destination to be enabled.

## Version Information

#### Silverlight

Supported in: 5  

#### Windows Phone

Supported in: Windows Phone OS 7.1, Windows Phone OS 7.0  

## See Also

#### Reference

[Tracing Class](tracing-class-microsoft-web-media-diagnostics_1.md)

[Microsoft.Web.Media.Diagnostics Namespace](microsoft-web-media-diagnostics-namespace_1.md)
