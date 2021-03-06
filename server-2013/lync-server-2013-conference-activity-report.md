﻿---
title: 'Lync Server 2013: 전화 회의 활동 보고서'
TOCTitle: 전화 회의 활동 보고서
ms:assetid: 22ddb509-af16-4fc8-9b98-6f58caa6f37e
ms:mtpsurl: https://technet.microsoft.com/ko-kr/library/Gg558627(v=OCS.15)
ms:contentKeyID: 49303056
ms.date: 08/10/2015
mtps_version: v=OCS.15
ms.translationtype: HT
---

# Lync Server 2013의 전화 회의 활동 보고서

 

_**마지막으로 수정된 항목:** 2015-03-09_

전화 회의 활동 보고서를 사용하면 매일 진행되는 전화 회의의 수와 시간 등의 정보를 쉽게 파악할 수 있습니다. 이러한 정보는 그 자체로도 유용할 뿐 아니라 문제 해결 시에도 적절하게 활용할 수 있습니다. 예를 들어 사용자가 하루 중 특정 시간에 네트워크 속도가 특히 느리다는 불만을 제기하는 경우를 가정해 보겠습니다. 이 경우 전화 회의 활동 보고서를 통해 한 가지 가능한 원인, 즉 다른 시간대에 비해 오전 10시에서 오후 2시 사이에 전화 회의가 훨씬 많이 예약됨을 확인할 수 있습니다.

속도가 느린 네트워크로 인해 문제가 발생하는 경우에는 사용자가 하루 중 트래픽이 더 적은 시간에 일부 전화 회의를 다시 예약하도록 할 수 있습니다.

## 전화 회의 활동 보고서 액세스

[Lync Server 2013의 회의 요약 보고서](lync-server-2013-conference-summary-report.md)에서 다음 메트릭 중 하나를 클릭하여 전화 회의 활동 보고서에 액세스할 수 있습니다.

  - 총 전화 회의

  - 총 참가자

## 전화 회의 활동 보고서를 가장 효율적으로 활용

전화 회의 활동 보고서에는 기본적으로 지정된 기간 동안의 총 전화 회의 수(예: 하루 동안의 총 전화 회의 수 또는 하루 중 시간별 총 전화 회의 수)가 표시됩니다. 그러나 해당 기간 동안의 총 참가자 수나 참가자의 총 참가 시간을 표시하도록 선택할 수도 있습니다. 이렇게 하려면 매개 변수 표시/숨기기 단추를 클릭하여 필터링 옵션을 표시한 다음 보고서 작성자 드롭다운 목록에서 다음 중 하나를 선택합니다.

  - 참가자 수

  - 참가 시간(분)

  - 전화 회의 수

## 필터

필터를 사용하면 여러 방식으로 반환된 데이터를 보거나 보다 세부적으로 대상화된 데이터 집합을 반환할 수 있습니다. 다음 표에서는 전화 회의 활동 보고서에서 사용할 수 있는 필터를 보여 줍니다.

### 전화 회의 활동 보고서 필터

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>이름</th>
<th>설명</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>시작</strong></p></td>
<td><p>시간 범위의 시작 날짜/시간입니다. 시간별 데이터를 보려면 다음과 같이 시작 날짜 및 시간을 입력합니다.</p>
<p>7/7/2012 1:00 PM</p>
<p>시작 시간을 입력하지 않으면 보고서가 자동으로 지정된 날짜의 오전 12시부터 시작됩니다. 일별 데이터를 보려면 날짜만 입력합니다.</p>
<p>7/7/2012</p>
<p>주 또는 월별로 보려면 데이터를 보려는 해당 주 또는 월에 속하는 날짜를 입력합니다. 주 또는 월의 첫 번째 날짜를 입력할 필요가 없습니다.</p>
<p>7/3/2012</p>
<p>주는 항상 일요일부터 토요일까지로 실행됩니다.</p></td>
</tr>
<tr class="even">
<td><p><strong>종료</strong></p></td>
<td><p>시간 범위의 종료 날짜/시간입니다. 시간별 데이터를 보려면 다음과 같이 종료 날짜 및 시간을 입력합니다.</p>
<p>7/7/2012 1:00 PM</p>
<p>종료 시간을 입력하지 않으면 보고서가 자동으로 지정된 날짜의 오전 12시에 종료됩니다. 일별 데이터를 보려면 날짜만 입력합니다.</p>
<p>7/7/2012</p>
<p>주 또는 월별로 보려면 데이터를 보려는 해당 주 또는 월에 속하는 날짜를 입력합니다. 주 또는 월의 첫 번째 날짜를 입력할 필요가 없습니다.</p>
<p>7/3/2012</p>
<p>주는 항상 일요일부터 토요일까지로 실행됩니다.</p></td>
</tr>
<tr class="odd">
<td><p><strong>간격</strong></p></td>
<td><p>시간 간격입니다. 다음 중에서 선택합니다.</p>
<ul>
<li><p>시간별(최대 25시간 표시 가능)</p></li>
<li><p>일별(최대 31일 표시 가능)</p></li>
<li><p>주별(최대 12주 표시 가능)</p></li>
<li><p>월별(최대 12개월 표시 가능)</p></li>
</ul>
<p>시작 및 종료 날짜가 선택한 간격에 허용되는 최대 값 수를 초과하면 시작 날짜로부터 최대 값 수만 표시됩니다. 예를 들어 일별 간격을 선택하는 경우 시작 날짜가 2012/8/7이고 종료 날짜가 2012/9/28이면 2012/8/7 오전 12:00부터 2012/9/7 오전 12:00까지 총 31일의 데이터만 표시됩니다.</p></td>
</tr>
<tr class="even">
<td><p><strong>보고서 작성자</strong></p></td>
<td><p>보고서에 사용할 값을 나타냅니다. 다음 중 하나를 선택할 수 있습니다.</p>
<ul>
<li><p>참가자 수</p></li>
<li><p>참가 시간(분)</p></li>
<li><p>전화 회의 수</p></li>
</ul></td>
</tr>
</tbody>
</table>


## 풀별 전화 회의 메트릭

다음 표에서는 각 풀에 대한 전화 회의 등록 보고서의 정보를 보여 줍니다.

### 풀별 전화 회의 메트릭

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th>이름</th>
<th>이 항목에 대한 정렬 가능 여부</th>
<th>설명</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>풀</strong></p></td>
<td><p>아니요</p></td>
<td><p>전화 회의에 사용된 등록자 풀 또는 에지 서버의 이름입니다.</p></td>
</tr>
<tr class="even">
<td><p><strong>날짜/시간</strong></p></td>
<td><p>아니요</p></td>
<td><p>전화 회의가 보류된 날짜 및 시간입니다.</p></td>
</tr>
<tr class="odd">
<td><p><strong>합계</strong></p></td>
<td><p>아니요</p></td>
<td><p>총 참가자 수, 총 참가 시간(분) 또는 총 전화 회의 수입니다.</p></td>
</tr>
</tbody>
</table>


## 서버 유형별 전화 회의 메트릭

다음 표에서는 각 서버 유형에 대한 전화 회의 등록 보고서의 정보를 보여 줍니다.

### 서버 유형별 전화 회의 메트릭

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th>이름</th>
<th>이 항목에 대한 정렬 가능 여부</th>
<th>설명</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>회의 서버 유형</strong></p></td>
<td><p>아니요</p></td>
<td><p>전화 회의에 사용된 서버 유형이며, 일반적으로 다음 중 하나입니다.</p>
<ul>
<li><p>웹 회의 서버</p></li>
<li><p>IM 회의 서버</p></li>
<li><p>전화 회의 서버</p></li>
<li><p>AV 회의 서버</p></li>
<li><p>응용 프로그램 공유</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>날짜/시간</strong></p></td>
<td><p>아니요</p></td>
<td><p>전화 회의가 보류된 날짜 및 시간입니다.</p></td>
</tr>
<tr class="odd">
<td><p><strong>합계</strong></p></td>
<td><p>아니요</p></td>
<td><p>총 참가자 수, 총 참가 시간(분) 또는 총 전화 회의 수입니다.</p></td>
</tr>
</tbody>
</table>

