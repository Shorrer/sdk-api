---
UID: NF:wsmandisp.IWSManEx.SessionFlagUseKerberos
title: IWSManEx::SessionFlagUseKerberos (wsmandisp.h)
description: Returns the value of the authentication flag WSManFlagUseKerberos for use in the flags parameter of IWSMan::CreateSession.
old-location: winrm\iwsmanex_sessionflagusekerberos.htm
tech.root: winrm
ms.assetid: 14b949d8-774b-4224-ab08-b52ff71ab1bb
ms.date: 12/05/2018
ms.keywords: IWSManEx interface [Windows Remote Management],SessionFlagUseKerberos method, IWSManEx.SessionFlagUseKerberos, IWSManEx::SessionFlagUseKerberos, SessionFlagUseKerberos, SessionFlagUseKerberos method [Windows Remote Management], SessionFlagUseKerberos method [Windows Remote Management],IWSManEx interface, winrm.iwsmanex_sessionflagusekerberos, wsmandisp/IWSManEx::SessionFlagUseKerberos
f1_keywords:
- wsmandisp/IWSManEx.SessionFlagUseKerberos
dev_langs:
- c++
req.header: wsmandisp.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows Vista
req.target-min-winversvr: Windows Server 2008
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: WSManDisp.idl
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: WSManDisp.tlb
req.dll: WSMAuto.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- WSMAuto.dll
api_name:
- IWSManEx.SessionFlagUseKerberos
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IWSManEx::SessionFlagUseKerberos


## -description


The <a href="https://docs.microsoft.com/windows/desktop/WinRM/wsman-sessionflagusekerberos">WSMan.WSMan.SessionFlagUseKerberos</a> method returns the value of the authentication flag <b>WSManFlagUseKerberos</b> for use in the <i>flags</i> parameter of <a href="https://docs.microsoft.com/windows/desktop/api/wsmandisp/nf-wsmandisp-iwsman-createsession">IWSMan::CreateSession</a>.

<b>WSManFlagUseKerberos</b> is a constant in the <b>__WSManSessionFlags</b> enumeration. For more information, see <a href="https://docs.microsoft.com/windows/desktop/WinRM/authentication-constants">Authentication Constants</a>.


## -parameters




### -param flags [out]

The value of the constant.


## -returns



If this method succeeds, it returns <b xmlns:loc="http://microsoft.com/wdcml/l10n">S_OK</b>. Otherwise, it returns an <b xmlns:loc="http://microsoft.com/wdcml/l10n">HRESULT</b> error code.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/wsmandisp/nn-wsmandisp-iwsmanex">IWSManEx</a>



<a href="https://docs.microsoft.com/windows/desktop/WinRM/wsman-sessionflagusekerberos">WSMan.WSMan.SessionFlagUseKerberos</a>
 

 

