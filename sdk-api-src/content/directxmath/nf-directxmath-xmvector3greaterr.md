---
UID: NF:directxmath.XMVector3GreaterR
title: XMVector3GreaterR function (directxmath.h)
description: Tests whether one 3D vector is greater than another 3D vector and returns a comparison value that can be examined using functions such as XMComparisonAllTrue.
old-location: dxmath\xmvector3greaterr.htm
tech.root: dxmath
ms.assetid: M:Microsoft.directx_sdk.comparison.XMVector3GreaterR(XMVECTOR,XMVECTOR)
ms.date: 12/05/2018
ms.keywords: Use DirectX..XMVector3GreaterR, XMVector3GreaterR, XMVector3GreaterR method [DirectX Math Support APIs], dxmath.xmvector3greaterr
f1_keywords:
- directxmath/XMVector3GreaterR
dev_langs:
- c++
req.header: directxmath.h
req.include-header: DirectXMath.h
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: Use DirectX.
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- directxmathvector.inl
api_name:
- XMVector3GreaterR
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# XMVector3GreaterR function


## -description


Tests whether one 3D vector is greater than another 3D vector and returns a comparison value that can be examined using functions such as <a href="https://docs.microsoft.com/windows/desktop/api/directxmath/nf-directxmath-xmcomparisonalltrue">XMComparisonAllTrue</a>.


## -parameters




### -param V1 [in]

3D vector.


### -param V2 [in]

3D vector.


## -returns



Returns a comparison value that can be examined using functions such as <a href="https://docs.microsoft.com/windows/desktop/api/directxmath/nf-directxmath-xmcomparisonalltrue">XMComparisonAllTrue</a>.




## -remarks



This function does the following test:


```
V1.x > V2.x
V1.y > V2.y
V1.z > V2.z
```


<h3><a id="Platform_Requirements"></a><a id="platform_requirements"></a><a id="PLATFORM_REQUIREMENTS"></a>Platform Requirements</h3>
Microsoft Visual Studio 2010 or Microsoft Visual Studio 2012 with the Windows SDK for Windows 8. Supported for Win32 desktop apps, Windows Store apps, and Windows Phone 8 apps.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/dxmath/ovw-xnamath-reference-functions-vector3-comparison">DirectXMath Library 3D Vector Comparison Functions</a>



<a href="https://docs.microsoft.com/windows/desktop/api/directxmath/nf-directxmath-xmvector3greater">XMVector3Greater</a>
 

 

