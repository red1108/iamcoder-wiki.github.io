# Radix Sort

## 소개

카운팅 정렬의 약점을 완벽하게 보완해주는 정렬 방법이다. 시간복잡도의 `d`는 각 원소의 자릿수중 최댓값인데, 각 자리수별로 카운팅 정렬을 실행하여 정렬하여 큰 수에 대해서도 정렬을 시행할 수 있다. 물론 가장 큰 자릿수부터 정렬을 시행해 주어야 할 것이다. 래딕스 정렬은 Big Integer라 불리는 `unsigned long long int` 범위를 훨씬 벗어나는, \\(10^{100}\\)과 같은 수들을 정렬할 때 유용하게 쓰일 수 있다. 코드는 카운팅 정렬의 것을 약간만 수정하면 되므로 생략하도록 하겠다.

