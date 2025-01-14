---
UID: NE:codecapi.eAVEncMPAEmphasisType
title: eAVEncMPAEmphasisType (codecapi.h)
description: Specifies the type of de-emphasis filter that should be used when decoding. This enumeration is used with the AVEncMPAEmphasisType property.
helpviewer_keywords: ["codecapi/eAVEncMPAEmphasisType","codecapi/eAVEncMPAEmphasisType_50_15","codecapi/eAVEncMPAEmphasisType_CCITT_J17","codecapi/eAVEncMPAEmphasisType_None","codecapi/eAVEncMPAEmphasisType_Reserved","dshow.eavencmpaemphasistype","eAVEncMPAEmphasisType","eAVEncMPAEmphasisType enumeration [DirectShow]","eAVEncMPAEmphasisTypeEnumeration","eAVEncMPAEmphasisType_50_15","eAVEncMPAEmphasisType_CCITT_J17","eAVEncMPAEmphasisType_None","eAVEncMPAEmphasisType_Reserved"]
old-location: dshow\eavencmpaemphasistype.htm
tech.root: dshow
ms.assetid: 29be42f2-42a2-4b0e-a05f-2ae2bfb5e633
ms.date: 4/26/2023
ms.keywords: codecapi/eAVEncMPAEmphasisType, codecapi/eAVEncMPAEmphasisType_50_15, codecapi/eAVEncMPAEmphasisType_CCITT_J17, codecapi/eAVEncMPAEmphasisType_None, codecapi/eAVEncMPAEmphasisType_Reserved, dshow.eavencmpaemphasistype, eAVEncMPAEmphasisType, eAVEncMPAEmphasisType enumeration [DirectShow], eAVEncMPAEmphasisTypeEnumeration, eAVEncMPAEmphasisType_50_15, eAVEncMPAEmphasisType_CCITT_J17, eAVEncMPAEmphasisType_None, eAVEncMPAEmphasisType_Reserved
req.header: codecapi.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 2000 Professional [desktop apps \| UWP apps]
req.target-min-winversvr: Windows 2000 Server [desktop apps \| UWP apps]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - eAVEncMPAEmphasisType
 - codecapi/eAVEncMPAEmphasisType
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - HeaderDef
api_location:
 - codecapi.h
api_name:
 - eAVEncMPAEmphasisType
---

# eAVEncMPAEmphasisType enumeration


## -description

\[The feature associated with this page, [DirectShow](/windows/win32/directshow/directshow), is a legacy feature. It has been superseded by [MediaPlayer](/uwp/api/Windows.Media.Playback.MediaPlayer) and [IMFMediaEngine](/windows/win32/api/mfmediaengine/nn-mfmediaengine-imfmediaengine). **MediaPlayer** and **IMFMediaEngine** have been optimized for Windows 10 and Windows 11. Microsoft strongly recommends that new code use **MediaPlayer** and **IMFMediaEngine** instead of **DirectShow**, when possible. Microsoft suggests that existing code that uses the legacy APIs be rewritten to use the new APIs if possible.\]

Specifies the type of de-emphasis filter that should be used when decoding. This enumeration is used with the <a href="/windows/desktop/DirectShow/avencmpaemphasistype-property">AVEncMPAEmphasisType</a> property.

## -enum-fields

### -field eAVEncMPAEmphasisType_None:0

None.

### -field eAVEncMPAEmphasisType_50_15:1

50/15 Î¼s.

### -field eAVEncMPAEmphasisType_Reserved:2

Reserved.

### -field eAVEncMPAEmphasisType_CCITT_J17:3

CCITT J.17.

## -see-also

<a href="/windows/desktop/DirectShow/codec-api-enumerations">Codec API Enumerations</a>



<a href="/windows/desktop/api/strmif/nn-strmif-icodecapi">ICodecAPI Interface</a>
