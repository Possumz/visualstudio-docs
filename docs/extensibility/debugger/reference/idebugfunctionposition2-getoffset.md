---
description: "Retrieves the position of the function in the source document."
title: IDebugFunctionPosition2::GetOffset | Microsoft Docs
ms.date: 11/04/2016
ms.topic: reference
f1_keywords:
- IDebugFunctionPosition2::GetOffset
helpviewer_keywords:
- IDebugFunctionPosition2::GetOffset
ms.assetid: 60943782-aec7-4be2-b222-1984ed53a543
author: maiak
ms.author: maiak
manager: jmartens
ms.technology: vs-ide-debug
ms.workload:
- vssdk
dev_langs:
- CPP
- CSharp
---
# IDebugFunctionPosition2::GetOffset

 [!INCLUDE [Visual Studio](~/includes/applies-to-version/vs-windows-only.md)]
Retrieves the position of the function in the source document.

## Syntax

### [C#](#tab/csharp)
```csharp
int GetOffset(
   TEXT_POSITION[] pPosition
);
```
### [C++](#tab/cpp)
```cpp
HRESULT GetOffset( 
   TEXT_POSITION* pPosition
);
```
---

## Parameters
`pPosition`\
[in, out] A [TEXT_POSITION](../../../extensibility/debugger/reference/text-position.md) structure that is filled in with the position of the function in a document.

## Return Value
 If successful, returns `S_OK`; otherwise, returns an error code.

## See also
- [IDebugFunctionPosition2](../../../extensibility/debugger/reference/idebugfunctionposition2.md)
- [TEXT_POSITION](../../../extensibility/debugger/reference/text-position.md)
