﻿---
title: 'Lync Server 2013: 새로운 클라이언트 기능'
TOCTitle: 새로운 클라이언트 기능
ms:assetid: 5c144677-4d58-4fc3-8445-74b76c9fcf07
ms:mtpsurl: https://technet.microsoft.com/ko-kr/library/JJ204933(v=OCS.15)
ms:contentKeyID: 49303761
ms.date: 08/24/2015
mtps_version: v=OCS.15
ms.translationtype: HT
---

# Lync Server 2013의 새로운 클라이언트 기능

 

_**마지막으로 수정된 항목:** 2013-02-19_

Microsoft Lync 2013에서는 사용자 인터페이스 및 중요한 새 기능이 새롭게 디자인되었습니다. 관리자를 위해 클라이언트가 이제는 Office 설치 프로그램에 포함되어 조직에서 Office를 배포하고 클라이언트를 사용자 지정하는 데 보다 유연한 접근 방식을 제공합니다.


> [!NOTE]
> Lync 2013 사용자 인터페이스 업데이트의 그림은 <A class=uri href="http://go.microsoft.com/fwlink/?linkid=273885">http://go.microsoft.com/fwlink/?linkid=273885</A>에서 " Lync 2013의 새로운 기능"을 참조하십시오.



## Office 설치 프로그램과의 통합

Lync 2013 메시징 및 공동 작업 클라이언트 내에서 모임 관리를 지원하는 Lync 2013용 온라인 모임 추가 기능 클라이언트 및 Outlook은 이제 Office 2013 설치 프로그램에 포함되어 있습니다.

이전 버전의 Lync 및 Office Communicator에서는 Windows Installer 속성을 사용해서 Office 설치를 사용자 지정하고 제어할 수 있었습니다. Lync 2013이 Office 설치에 포함되었기 때문에 다양한 방법으로 Lync 2013 설치를 사용자 지정할 수 있습니다.

  - OST(Office 사용자 지정 도구) 사용

  - Config.xml을 사용하여 설치 작업 수행

  - 설치 프로그램 명령줄 옵션 사용


> [!NOTE]
> Lync 2013 설치 프로그램은 이전 버전의 Lync 또는 Office Communicator를 설치하지 않습니다. Lync 2013 클라이언트는 다른 Lync 또는 Office Communicator 클라이언트와 함께 수평적으로 설치됩니다.



자세한 내용은 [Lync 클라이언트 배포](lync-server-2013-deploying-lync-clients.md)을 참고하세요.

## 그룹 정책 배포

Lync 2013이 이제 Office 설치 프로그램에 포함되었기 때문에 Lync 그룹 정책 설정을 배포하는 방법이 변경되었습니다. 이전 버전의 Lync 및 Office Communicator에서는 Communicator.adm을 사용하여 그룹 정책 설정을 정의할 수 있었지만 Lync 2013에서는 이제 Office 그룹 정책 관리 템플릿과 함께 제공되는 Lync ADMX 및 ADML 관리 템플릿을 사용할 수 있습니다.

자세한 내용은 [Lync 2013용 그룹 정책 설정](lync-server-2013-group-policy-settings-for-lync-2013.md)을 참고하세요.

## Outlook 예약 추가 기능 업데이트

Lync 2013용 온라인 모임 추가 기능에는 모임 초대 사용자 지정 및 새 모임 옵션이 포함됩니다.

  - 관리자는 사용자 지정 로고, 지원 URL, 법적 고지 사항 URL 또는 사용자 지정 바닥글 텍스트를 추가하여 조직의 모임 초대를 사용자 지정할 수 있습니다. 자세한 내용은 [온라인 모임 추가 기능 사용자 지정](lync-server-2013-customizing-the-online-meeting-add-in.md)을 참조하십시오.

  - 새로운 참석자 음소거 제어를 통해서는 모임 이끌이가 기본적으로 참석자의 오디오 및 비디오가 음소거된 상태로 회의를 예약할 수 있습니다.

## Virtual Desktop Infrastructure 플러그인

Lync 2013 클라이언트에서는 이제 VDI(Virtual Desktop Infrastructure) 환경에서 오디오 및 비디오가 지원됩니다. 사용자가 오디오 또는 비디오 장치(예: 헤드셋 또는 카메라)를 로컬 컴퓨터(예: 씬 클라이언트 또는 재활용 컴퓨터)에 연결한 후 가상 컴퓨터에 연결하여 가상 컴퓨터에서 실행되는 Lync 2013 클라이언트에 로그인하고, 클라이언트가 로컬로 실행되고 있는 것처럼 실시간 오디오 및 비디오 통신에 참가할 수 있습니다. 가상 데스크톱 환경에서 다음과 같은 기능이 지원됩니다.

  - 다음을 포함한 오디오 및 비디오에 대한 장치 통합:
    
      - 장치에서 통화 제어
    
      - 장치에 현재 상태 통합
    
      - 다중 HID(휴먼 인터페이스 장치) 지원

  - 위치 및 긴급 서비스 지원

  - IM, 오디오, 비디오, 응용 프로그램 공유, 데스크톱 공유, PowerPoint 공유, 화이트보드 및 파일 전송을 포함하여 모든 Lync 형식 지원

  - 일대일 통화 및 회의 통화에서 오디오 및 비디오 지원

VDI 플러그인 배포에 대한 자세한 내용은 [Lync Server 2013에서 Lync VDI 플러그 인 배포](lync-server-2013-deploying-the-lync-vdi-plug-in.md)을 참조하십시오.

## 향상된 비디오 기능

일부 새로운 기능으로 회의 참가자의 비디오 환경이 크게 향상되었습니다.

  - 참가자의 비디오에 참가자가 계속해서 화면 가운데에 표시되도록 하는 얼굴 인식 및 스마트 프레이밍 기술로 비디오 기능이 향상되었습니다.

  - 두 사용자간 통화 및 단체 회의에서 이제 고해상도 비디오가 지원됩니다. 사용자는 최대 HD 1080P까지 향상된 해상도를 경험할 수 있습니다.

  - 참가자는 다양한 모임 레이아웃 중에서 선택할 수 있습니다. 갤러리 보기에는 모든 참가자의 사진 또는 비디오가 표시되고, 발표자 보기에는 모임 콘텐츠 및 현재 발표자의 비디오 또는 사진만 표시되고, 프레젠테이션 보기에는 모임 콘텐츠만 표시되며, 간단히 보기에는 모임 컨트롤만 표시됩니다.

  - 새로운 갤러리 기능으로 참가자는 여러 개의 비디오 피드를 동시에 확인할 수 있습니다. 회의가 5명 이상의 참가자로 구성된 경우 가장 활동적인 참가의 비디오 피드가 위쪽에 표시되고 다른 참가자는 사진이 표시됩니다.

  - 참가자는 비디오 고정 기능을 사용해서 항상 표시할 비디오 피드 중 하나 이상을 선택할 수 있습니다.

  - 발표자는 비디오 스포트라이트 기능을 사용해서 한 사람의 비디오 피드를 선택하여 모든 회의 참가자가 해당 참가자만 볼 수 있도록 할 수 있습니다.

## 채팅방 통합

Lync 2013에는 이전에 Lync 2010 그룹 채팅에서 제공되던 기능들이 통합되어 있습니다. 개별 그룹 채팅 클라이언트가 더 이상 필요하지 않습니다.

  - Lync 2013 내에서 사용자는 채팅방을 검색하고, 채팅방을 자신의 연락처에 추가하고, 채팅방 활동을 모니터링하고, 메시지를 읽고 게시할 수 있습니다.

  - 사용자는 항목 피드를 만들어서 채팅방에 포함된 사용자가 특정 키워드가 포함된 게시물을 추가할 때 이에 대한 알림을 받을 수 있습니다.

  - 새로운 **영구 채팅** 옵션 페이지에서는 사용자가 자신의 채팅방에 메시지를 게시할 때 적용할 알림 경고 및 사운드를 설정할 수 있습니다.

## Lync Web App 업데이트

Lync Web App은 Lync Server 2013 모임을 위한 웹 기반 회의 클라이언트입니다. 이번 릴리스에서 Lync Web App에 추가된 컴퓨터 오디오 및 비디오 기능으로 Lync 클라이언트가 로컬로 설치되지 않은 모든 사용자에게 완벽한 모임 내 환경을 제공합니다. 모임 참가자는 모든 공동 작업 및 공유 기능과 발표자의 모임 컨트롤에 액세스할 수 있습니다.

클라이언트가 로컬로 설치되지 않은 상태에서 사용자가 모임에 참가하려고 하면 Lync Web App이 열립니다. 모임 참가를 위한 추가 옵션을 허용하려는 경우 모임 참가 페이지를 구성할 수 있습니다. 배포 설명서에서 [Lync Server 2013에서 모임 참가 페이지 구성](lync-server-2013-configuring-the-meeting-join-page.md)을 참조하십시오.

Lync Web App에 대한 향상된 기능 덕분에 Attendee의 업데이트 버전은 Lync Server 2013에서 제공되지 않습니다. Lync Web App은 조직 외부의 참가자를 위한 클라이언트 옵션입니다. 오디오, 비디오 및 공유 기능을 사용하기 위해서는 처음에 사용할 때 플러그인을 설치해야 하지만 로컬 클라이언트를 설치할 필요가 없습니다.

## 모바일 클라이언트 업데이트용 Lync 2013

이제 Lync 2013 모바일 클라이언트는 현재 상태 사용자 지정, 대화 상대 및 IM 기능 외에 인터넷 및 셀룰러 데이터 연결을 통한 음성 및 비디오 통화 기능도 제공합니다. 모바일 사용자는 일정 항목에서 모임 링크를 한 번 탭하여 간편하게 Lync 음성 및 비디오 모임에 참가할 수 있습니다. Lync 2013 모바일 클라이언트에 대한 자세한 내용은 [Lync Server 2013의 모바일 클라이언트 계획](lync-server-2013-planning-for-mobile-clients.md)을 참조하십시오.

## Lync 2013 사용자 인터페이스 업데이트

## 내게 필요한 옵션 업데이트

Lync 2013에는 몇 가지 새로운 내게 필요한 옵션 기능이 포함됩니다.

  - Lync 2013에서는 사용자가 텍스트 및 그래픽의 DPI(인치당 도트 수)를 125% 및 150%로 확장할 수 있게 해주는 높은 DPI 해상도가 지원됩니다.

  - Lync에서는 Windows에서 고대비 테마를 사용할 때 사용자 인터페이스가 완전히 작동하도록 고대비 지원을 제공합니다.

  - Lync는 마우스를 사용하지 않고도 중요한 기능에 액세스할 수 있도록 100개 이상의 키보드 단축키를 제공합니다. 예를 들어 사용자는 Tab을 옮기거나 포커스를 설정하지 않아도 Alt+C를 눌러서 통화를 수락하거나 Alt + I를 눌러서 무시할 수 있습니다. Alt+Q를 누르면 통화가 종료되고 Ctrl+N을 누르면 OneNote가 시작되며, Alt+T를 누르면 도구 메뉴가 열립니다.

  - Lync 2013의 포괄적인 화면 판독기 지원으로 화면 판독기가 설정되었을 때 모든 알림, 수신 요청 및 인스턴트 메시지가 크게 읽혀지도록 보장합니다.

## 공유 중 현재 상태

Lync에서 사용자가 공유 중인 것이 감지되면 Lync가 사용자에게 프레젠테이션 중 현재 상태를 자동으로 지정합니다. 이 상태는 보낸 사람이 작업 그룹 정보 공개 범위에 지정되지 않은 한 모든 들어오는 통신을 차단합니다. 사용자가 전적으로 보조 모니터에서만 공유 기능을 사용 중인 경우에는 Lync가 프레젠테이션 중 현재 상태를 지정하지 않습니다.

## 대화 창 업데이트

새롭게 디자인된 대화 창에서는 중요한 기능에 대한 빠른 액세스 기능을 제공합니다.

  - 새로운 대화 탭 기능으로 사용자는 이제 모든 IM 및 채팅방을 하나의 대화 창에 유지할 수 있습니다. 대화 창 왼쪽에 표시되는 탭을 이용해서 모든 활성 대화 간에 쉽게 이동할 수 있습니다.

  - 사용자는 개별 대화를 다른 분리된 창으로 빼내고 창 크기를 조절할 수 있습니다. 또한 창을 다시 기본 대화 창에 넣을 수도 있습니다.

  - 사용자가 로그아웃하고 다시 Lync에 로그인하면 Lync 2013이 사용자의 대화를 다시 엽니다.

  - 사용자는 어느 대화에도 IM, 비디오, 프로그램 공유, 데스크톱 공유 또는 웹 회의 도구(화이트보드, 모임 메모, 공유 전자 필기장 및 첨부 파일을 신속하게 추가할 수 있습니다.

  - 비디오 또는 콘텐츠를 공유 중인 모임에서는 사용자가 모임 비디오 또는 공유 콘텐츠를 빼내서 창 크기를 조절할 수 있습니다.

## Lync 기본 창 업데이트

새롭게 효율화된 화면 모양에 **새로운 소식** 메모 필드, 상태 선택기 및 **내 위치 설정** 선택기와 같은 익숙한 기능이 포함되어 있습니다.

  - 채팅방이 사용하도록 설정되면 기본 Lync 페이지에 새로운 **채팅방** 아이콘이 표시됩니다. **채팅방** 아이콘을 사용해서는 자신의 채팅방 및 필터에 빠르게 액세스할 수 있습니다.

  - 사용자는 보기 아이콘을 클릭해서 **연락처** 보기, **채팅방** 보기, **대화** 보기 또는 **전화** 보기로 전환할 수 있습니다.

  - 사용자가 Exchange 2013으로 마이그레이션한 경우 고해상도 사진을 업로드할 수 있습니다.

## 연락처 보기 및 대화 상대 카드 업데이트

Lync 2013에서는 **연락처** 보기에서 여러 가지 방법으로 연락처 및 그룹을 볼 수 있습니다.

  - 새로운 통합 연락처 저장소를 사용하여 사용자의 Lync 연락처를 Exchange 2013으로 마이그레이션한 후 Lync 2013, Outlook 또는 Outlook Web App에서 연락처를 액세스하고 관리할 수 있으며 즐겨찾기는 동기화된 상태로 유지됩니다. 예를 들어 사용자가 Outlook에서 즐겨찾기에 연락처를 하나 추가하면 이 연락처가 Lync 2013의 즐겨찾기 그룹에 표시됩니다.

  - XMPP 프록시 및 XMPP 게이트웨이를 추가하고 구성한 경우에는 사용자가 인스턴트 메시징 및 현재 상태를 위해 XMPP 기반 파트너에서 연락처를 추가할 수 있습니다.

  - 새로운 **내 조직 외부의 대화 상대 추가** 기능을 통해서는 조직 외부에 있는 사용자를 쉽게 추가할 수 있습니다.

  - 새로운 **즐겨찾기** 그룹을 통해서는 자주 사용하는 사용자를 더 빠르게 액세스할 수 있도록 사용자 목록으로 작성할 수 있습니다.

  - 사용자는 새로운 **대화 상대 목록** 옵션 페이지를 사용해서 사용자를 정렬하고 연락처를 표시하는 방법을 선택할 수 있습니다. 대화 상대의 사진이 표시된 확장된 2행 보기를 선택하거나 간결한 1행 보기를 선택할 수 있습니다. 또한 연락처를 알파벳 또는 상태별로 정렬할 수도 있습니다.

## 회의 업데이트

Lync 2013은 몇 가지 향상된 회의 기능을 제공합니다.

  - 모임 유형에 따라 사용자는 이제 모임을 예약할 때 모든 사용자를 음소거하거나 비디오 공유를 차단할 수 있습니다. 이러한 옵션은 **모임 옵션** 페이지에서 사용할 수 있으며 참가자 20명 이상인 대규모 모임에서 권장됩니다.

  - 모임 방에서 오디오 컨트롤을 쉽게 사용할 수 있으므로 음소거, 음소거 해제, 장치 변경 등의 오디오 옵션을 제어할 수 있습니다.

  - 프로그램을 공유할 때는 두 개 이상의 프로그램을 사용해야 하는 경우 여러 개의 프로그램을 공유하도록 선택할 수 있습니다.

  - 이제는 비디오 클립이 포함된 프레젠테이션을 업로드할 수 있습니다. PowerPoint 파일을 업로드하고 마우스를 슬라이드 위로 이동하면 재생, 일시 정지와 같은 비디오 컨트롤과 오디오 컨트롤을 표시할 수 있습니다.

  - 모임 중에는 **다른 옵션** ( **...** ) 메뉴에서 **이 호출을 다음으로 병합** 을 사용해서 열려 있는 다른 대화를 현재 모임에 병합할 수 있습니다.

  - 참가자의 이름을 보기 위해서는 **참가자 보기** 단추 위로 마우스를 가져가거나 **참가자 목록 표시** 를 클릭하여 패널을 모임에 도킹하면 됩니다.

  - 모임 유형에 따라 사용자는 여러 콘텐츠 및 참가자 보기 중에서 선택할 수 있습니다.

  - 모임 기록은 Windows Media Player(MP4)에서 재생되는 형식으로 자동으로 저장됩니다. 사용자는 이 파일을 다른 사용자와 쉽게 공유하거나 기록 관리자에서 **게시** 를 사용하여 공유 위치에 기록을 게시할 수 있습니다.

  - OneNote는 모임에서 공동 작업할 수 있는 새로운 방법들을 지원합니다. 모임 중 사용자는 모임 후 개인 목적으로 사용하기 위해 OneNote를 사용해서 메모를 작성하거나 공유 전자 필기장을 사용하고 실시간으로 모임 참가자들과 같이 편집할 수 있습니다. 모든 팀 구성원이 공유 전자 필기장에 액세스해서 정보를 나누거나, 생각을 브레인스토밍하거나, 전자 필기장 페이지를 가상의 화이트보드처럼 사용할 수 있습니다. 모임에서 공유되는 콘텐츠 및 사용자는 자동으로 해당 전자 필기장에 추가됩니다.

  - 사용자는 모임 방 아래의 **공유 콘텐츠 및 선행 모임 작업** 을 사용해서 콘텐츠 형식 간에 전환할 수 있습니다. 또한 **프레젠테이션 가능 콘텐츠 관리** 메뉴를 사용해서 공유하려는 콘텐츠를 선택할 수도 있습니다.

## 참고 항목

#### 기타 리소스

[Lync Server 2013의 클라이언트 계획](lync-server-2013-planning-for-clients.md)
