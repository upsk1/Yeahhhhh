# [PPC 만들기](https://www.acmicpc.net/problem/31778)

##### 분류 : Greedy + two Pointer 

##### 티어 : 골드3

##### 풀이
요구하는 바가 명확해서 직관적인 그리디 문제였다.   
PPC를 최대한 많이 만들기 위해서 최대한 많은 P가 C보다 앞에 있으면 된다.   
처음에는 deque를 써서 P를 뒤에서, C를 앞에서 꺼내서 스왑해줬다.   
후에는 우선순위큐를 써서 P를 내림차순, C를 오름차순해서 바꿔주는것으로 변경했다.
최대 K번 연산할 수 있지만 최적의 배열이 만들어졌으면 연산을 중지해야한다.   
연산이 끝났으면 누적합을 이용해서 답을 계산하면 된다.   
로직이 완벽하다고 생각했는데 틀려서 문제가 뭔지 고민하다가 int를 long으로 바꾸니까 문제가 풀렸다....   
앞으로 최대한 long을 사용해보자.
