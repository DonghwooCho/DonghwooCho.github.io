---
title: 알고리즘 - 동적 프로그래밍 (Dynamic programing, DP)
# author: DonghwooCho
date: 2023-01-01 00:00:00 +0900
categories: [자료구조 & 알고리즘, Dynamic programing]
tags: [Algorithm, Dynamic programing]
---

<h2>☑️ 동적 프로그래밍 (Dynamic programing)</h2>

> <b>복잡한 문제를 여러 개의 하위 문제로 나누어 원하는 결과를 찾는 방법</b>
{: .prompt-tip }

<h3>☑️ 알고리즘 특징</h3>
<ul>
    <li>연산 결과를 상위 문제 혹은 다른 하위 문제에서 사용하기 때문에 동일한 연산을 줄일 수 있다.</li>
    <li>반복되는 연산을 줄이기 때문에 시간 복잡도를 개선할 수 있다.</li>
    <li>모든 경우의 수를 확인하기 때문에 정확하게 원하는 결과를 얻을 수 있지만, 상대적으로 시간 복잡도가 크다. </li>
</ul>

<h3>☑️ 알고리즘 적용</h3>
<ul>
    <li><b>같은 연산을 반복적으로 여러 하위 문제에서 수행할 때</b> 사용하는 것이 이상적이다.</li>
    <li>반복되는 연산 결과를 저장하고, 재사용(메모이제이션, Memoization)하여 구현할 수 있다.</li>
    <li>DP 알고리즘 적용 가능 여부를 판단하는 것과 반복되는 연산 결과에 대한 점화식을 세우는 것이 관건이다.</li>
</ul>