---
title: IMemoryAllocator Allocate method
description: The Allocate method allocates memory for the StgConvertPropertyToVariant function when the function converts a SERIALIZEDPROPERTYVALUE data type to a PROPVARIANT data type.
ms.assetid: aa9c9308-fb55-405c-901a-9d5abfac5395
keywords:
- Allocate method Structured Storage
- Allocate method Structured Storage , IMemoryAllocator interface
- IMemoryAllocator interface Structured Storage , Allocate method
topic_type:
- apiref
api_name:
- IMemoryAllocator.Allocate
api_location:
- Ole32.lib
- Ole32.dll
api_type:
- COM
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# IMemoryAllocator::Allocate method

The **Allocate** method allocates memory for the [**StgConvertPropertyToVariant**](https://msdn.microsoft.com/library/windows/desktop/aa380321) function when the function converts a **SERIALIZEDPROPERTYVALUE** data type to a **PROPVARIANT** data type.

## Syntax


```C++
virtual void* Allocate(
  [in] ULONG cbSize
);
```



## Parameters

<dl> <dt>

*cbSize* \[in\]
</dt> <dd>

Specifies the size of memory to be allocated.

</dd> </dl>

## Requirements



|                                     |                                                                                      |
|-------------------------------------|--------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows 2000 Professional \[desktop apps only\]<br/>                           |
| Minimum supported server<br/> | Windows 2000 Server \[desktop apps only\]<br/>                                 |
| Library<br/>                  | <dl> <dt>Ole32.lib</dt> </dl> |



 

 




