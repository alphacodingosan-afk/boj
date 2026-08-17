# [Gold V] 재미있는 파이프 퍼즐 - 32964 

[문제 링크](https://www.acmicpc.net/problem/32964) 

### 성능 요약

메모리: 111484 KB, 시간: 108 ms

### 분류

그래프 이론, 그래프 탐색

### 제출 일자

2026년 04월 22일 11:07:53

### 문제 설명

<p>진흥이는 재미있는 파이프 퍼즐을 풀고 있습니다. 이 퍼즐은 세로 $2$칸, 가로 $N$칸 크기입니다. 위에서 $i$번째이고 왼쪽에서 $j$번째인 칸은 $(i, j)$라고 표시합니다.</p>

<p>$(1, 1)$과 $(2, N)$을 제외한 각 칸에는 파이프가 하나씩 설치되어 있습니다. 파이프는 <code>I</code>자형 파이프와 <code>L</code>자형 파이프의 두 종류가 있습니다. 진흥이는 이 파이프들을 제자리에서 적절히 회전시켜 $(1, 1)$에서 $(2, N)$까지 파이프를 연결하려고 합니다.</p>

<p style="text-align: center;"><img alt="" src="" style="width: 235px; height: 145px;"></p>

<p style="text-align: center;">그림 1. <code>I</code>자형 파이프는 회전시켜서 위의 두 모양을 만들 수 있습니다.</p>

<p style="text-align: center;"><img alt="" src="" style="width: 474px; height: 150px;"></p>

<p style="text-align: center;">그림 2. <code>L</code>자형 파이프는 회전시켜서 위의 네 모양을 만들 수 있습니다.</p>

<p>각 칸마다 설치된 파이프의 종류가 주어질 때, 진흥이를 도와서 $(1, 1)$에서 $(2, N)$까지 파이프를 연결할 수 있는지 판단합시다.</p>

<p style="text-align: center;"><img alt="" src="" style="width: 593px; height: 238px;"></p>

<p style="text-align: center;">그림 3. $(1, 1)$에서 $(2, N)$까지 파이프를 연결한 한 가지 경우입니다.</p>

### 입력 

 <p>첫 번째 줄에 퍼즐의 가로 칸 수 $N$이 주어집니다.</p>

<p>두 번째 줄에 위쪽 칸들의 파이프 종류를 나타내는 길이 $N$의 문자열이 주어집니다.</p>

<p>세 번째 줄에 아래쪽 칸들의 파이프 종류를 나타내는 길이 $N$의 문자열이 주어집니다.</p>

<p>각 문자열에서 $(1, 1)$과 $(2, N)$에는 <code>X</code>가 대신 주어지며, <code>I</code>자형 파이프는 <code>I</code>로, <code>L</code>자형 파이프는 <code>L</code>로 주어집니다.</p>

### 출력 

 <p>파이프를 적절히 회전시켜 $(1, 1)$에서 $(2, N)$까지 파이프를 연결할 수 있으면 <code>YES</code>를, 불가능하면 <code>NO</code>를 출력합니다.</p>

