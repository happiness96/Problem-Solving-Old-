https://www.acmicpc.net/problem/14919

## 문제
0과 1사이의 실수 a1, a2, ..., aN이 입력으로 주어졌다고 하자.  구간 [0,1)을 다음과 같이 m개의 길이 L=1/m인 부분구간으로 나누자. 각 구간은 순서대로 b1, b2, ..., bm이다.

b1: 0 ≤ x < L,

b2: L ≤ x < 2L,

...

bm: (m-1)L ≤ x < 1.

입력된 실수중, 각 구간 b1, b2, ..., bm에 포함되는 수의 개수를 출력하시오.

## 입력
첫줄에 m (1 ≤ m ≤ 1,000), 둘째 줄에 N (1 ≤ N ≤ 1,000,000)개의 실수 a1, …, aN이 빈칸으로 구분되어 입력된다. 실수는 소수점 여섯째 자리까지 주어진다.

## 출력
각 구간 b1, b2, ..., bm에 포함된 수를 빈 칸으로 구분해 출력한다.
