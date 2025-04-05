https://www.hackerrank.com/challenges/bear-and-steady-gene/problem?isFullScreen=true

풀이 : 연속된 문자열 중에 문자를 바꿔 A, C, T, G의 갯수가 동일하게 만들 수 있는 연속 문자열 중 최소 길이를 구하는 문제로
동일한 값으로 만들기 위해 필요한 문자의 갯수를 구한 후 
투 포인터로 문자를 더해 필요한 문자의 갯수에 부합하면 right += 1 그렇지 않다면 right - left를 하여 최소값을 갱신하고 left -= 1을 하면 됩니다.