﻿---
title: 'Lync Server 2013: PSTN 게이트웨이 위치'
TOCTitle: PSTN 게이트웨이 위치
ms:assetid: 49693a35-fad3-49ee-a71e-c7e4537b79aa
ms:mtpsurl: https://technet.microsoft.com/ko-kr/library/JJ994031(v=OCS.15)
ms:contentKeyID: 52056831
ms.date: 08/10/2015
mtps_version: v=OCS.15
ms.translationtype: HT
---

# Lync Server 2013의 PSTN 게이트웨이 위치

 

_**마지막으로 수정된 항목:** 2013-03-09_

PSTN 게이트웨이 및 PBX를 통해 라우팅된 통화에는 해당 시스템의 위치에 따라 위치 기반 라우팅 제한이 필요할 수 있습니다. 위치 기반 라우팅은 트렁크 기반 단위로 활성화할 수 있습니다.

위치 기반 라우팅이 트렁크에서 설정된 경우 다음 규칙 집합을 가져옵니다.

  - 위치 기반 라우팅이 트렁크 기반으로 설정된 경우, 해당 트렁크의 규칙은 트렁크를 통해 라우팅되는 통화에만 적용됩니다.

  - PSTN 게이트웨이가 있는 네트워크 사이트가 아닌 다른 네트워크 사이트에서 전화가 걸려온 경우, 위치 기반 라우팅은 PSTN 유료 전화 우회를 방지하기 위해 네트워크 사이트의 연결을 지정된 트렁크로 가져옵니다. 이렇게 하면 통화가 지정된 트렁크로 라우팅되도록 허용하는 네트워크 사이트가 정의됩니다.

다음 두 가지 방법으로 트렁크에 위치 기반 라우팅을 사용하도록 설정할 수 있습니다.

  - 통화를 PSTN으로 내보내는 PSTN 게이트웨이에 대해 트렁크를 정의합니다. 이 유형의 트렁크에 의해 라우팅되는 수신 전화는 트렁크와 동일한 네트워크에 있는 끝점으로만 라우팅됩니다.

  - 통화를 PSTN으로 내보내지 않는 중재 서버 피어 및 고정된 위치에 있는 기존 전화를 사용하는 서비스 사용자(예: PBX 전화)에 대해 트렁크를 정의합니다. 이 특정 구성의 경우 이 유형의 트렁크에 의해 라우팅되는 모든 수신 통화는 트렁크와 동일한 네트워크 사이트에서 걸린 것으로 간주됩니다. PBX에서 전화를 거는 사용자에게는 트렁크와 동일한 네트워크 사이트에 있는 Lync 사용자와 동일한 위치 기반 라우팅이 적용됩니다. 다른 위치에 있는 두 개의 PBX 시스템이 Lync Server를 통해 연결된 경우, 위치 기반 라우팅은 한 네트워크 사이트에 있는 한 PBX 끝점에서 다른 네트워크 사이트에 있는 다른 PBX 끝점으로의 라우팅을 허용합니다. 이 시나리오는 위치 기반 라우팅에 의해 차단되지 않습니다. 이 시나리오 외에도 동일한 위치에 있는 Lync 사용자와 비슷한 방법으로 이 구성을 사용하여 중재 서버 피어에 연결된 끝점에서 중재 서버 피어가 연결된 네트워크 사이트와 관계없이 통화를 PSTN로 라우팅하지 않는 다른 중재 서버 피어(예: 다른 PBX에 연결된 끝점)로 전화를 걸거나 받을 수 있습니다. PSTN 끝점을 포함하는 모든 인바운드 통화, 아웃바운드 통화, 통화 전송 및 착신 전환에는 해당 중재 서버 피어에 대해 로컬로 정의된 PSTN 게이트웨이만 사용하도록 위치 기반 라우팅이 적용됩니다.

## 참고 항목

#### 기타 리소스

[Lync Server 2013의 위치 기반 라우팅에 대한 지침](lync-server-2013-guidance-for-location-based-routing.md)
