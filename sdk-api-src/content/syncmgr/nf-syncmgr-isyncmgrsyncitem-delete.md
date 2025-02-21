---
UID: NF:syncmgr.ISyncMgrSyncItem.Delete
title: ISyncMgrSyncItem::Delete (syncmgr.h)
description: Deletes a sync item.
old-location: shell\ISyncMgrSyncItem_Delete.htm
tech.root: shell
ms.assetid: 403c01fe-928d-4b9b-a087-6cc68d1aa90a
ms.date: 12/05/2018
ms.keywords: Delete, Delete method [Windows Shell], Delete method [Windows Shell],ISyncMgrSyncItem interface, ISyncMgrSyncItem interface [Windows Shell],Delete method, ISyncMgrSyncItem.Delete, ISyncMgrSyncItem::Delete, _shell_ISyncMgrSyncItem_Delete, shell.ISyncMgrSyncItem_Delete, syncmgr/ISyncMgrSyncItem::Delete
f1_keywords:
- syncmgr/ISyncMgrSyncItem.Delete
dev_langs:
- c++
req.header: syncmgr.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows Vista [desktop apps only]
req.target-min-winversvr: Windows Server 2008 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: Syncmgr.idl
req.max-support: 
req.namespace: 
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
- Syncmgr.h
api_name:
- ISyncMgrSyncItem.Delete
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# ISyncMgrSyncItem::Delete


## -description


Deletes a sync item.


## -parameters






## -returns



Type: <b>HRESULT</b>

If this method succeeds, it returns <b xmlns:loc="http://microsoft.com/wdcml/l10n">S_OK</b>. Otherwise, it returns an <b xmlns:loc="http://microsoft.com/wdcml/l10n">HRESULT</b> error code.




## -remarks



Sync Center calls this method when the user selects the item in the handler's folder and launches its <b>Delete</b> task, but only if the item has set the <a href="https://docs.microsoft.com/windows/desktop/api/syncmgr/ne-syncmgr-syncmgr_handler_policies">SYNCMGR_ICM_CAN_DELETE</a> flag. If the handler supports the <a href="https://docs.microsoft.com/windows/desktop/api/syncmgr/nf-syncmgr-isyncmgrsyncitem-getobject">SYNCMGR_OBJECTID_QueryBeforeDeactivate</a> object, this method is only called if the UI operation was successful.

If the handler does not need to perform any actions when it is activated, it can return either S_OK or E_NOTIMPL.



