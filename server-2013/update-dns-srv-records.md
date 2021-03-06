﻿---
title: DNS SRV 레코드 업데이트
TOCTitle: DNS SRV 레코드 업데이트
ms:assetid: 9542b91a-108c-4980-89ec-634905cbbf26
ms:mtpsurl: https://technet.microsoft.com/ko-kr/library/JJ688139(v=OCS.15)
ms:contentKeyID: 49885879
ms.date: 08/24/2015
mtps_version: v=OCS.15
ms.translationtype: HT
---

# DNS SRV 레코드 업데이트

 

_**마지막으로 수정된 항목:** 2012-09-29_

이 절차를 성공적으로 완료하려면 서버 또는 도메인에 Domain Admins 그룹의 구성원 또는 DnsAdmins 그룹의 구성원으로 로그온해야 합니다.

이 항목에서는 Lync Server 2013으로 마이그레이션하기 전에 DNS(Domain Name System) 레코드를 업데이트하는 방법에 대해 설명합니다. 모든 사용자가 Lync Server 2013으로 이동한 후 레거시 Lync Server 2010 풀 또는 디렉터를 해제하기 전에 모든 SIP 도메인에 대해 내부 DNS에서 DNS SRV 레코드를 업데이트해야 합니다. 이 절차에서는 내부 DNS에 SIP 사용자 도메인의 영역이 있다고 가정합니다.

**DNS SRV 레코드를 구성하려면**

1.  DNS 서버에서 **시작** , **관리 도구** 를 차례로 클릭한 다음 **DNS** 를 클릭합니다.

2.  SIP 도메인의 콘솔 트리에서 **정방향 조회 영역** 을 확장하고 Lync Server 2013을 설치할 SIP 도메인을 확장한 후에 **\_tcp** 설정으로 이동합니다.

3.  오른쪽 창에서 **\_sipinternaltls**를 마우스 오른쪽 단추로 클릭한 후에 **속성**을 선택합니다.

4.  **이 서비스를 제공하는 호스트** 에서 Lync Server 2013 풀을 가리키도록 호스트 FQDN을 업데이트합니다.

5.  **확인** 을 클릭합니다.

**프런트 엔드 풀 또는 Standard Edition Server의 FQDN을 확인할 수 있는지 확인하려면**

1.  도메인의 클라이언트 컴퓨터에 로그온합니다.

2.  **시작** 을 클릭한 다음 **실행** 을 클릭합니다.

3.  **열기** 상자에 **cmd** 를 입력한 다음 **확인** 을 클릭합니다.

4.  명령 프롬프트에서 **nslookup** *\<프런트 엔드 풀의 FQDN\>* 또는 *\<Standard Edition Server의 FQDN\>* 을 입력한 다음 Enter 키를 누릅니다.

5.  FQDN에 대해 적절한 IP 주소로 확인되는 응답이 수신되는지 점검합니다.

