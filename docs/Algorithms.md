## 힙자료구조(in c++ template)
---

1. 정의: 완전 이진 트리로, 모든 정점(vertex)들이 자기 자식들보다 우선순위가 높은 자료구조.
1.  특징 : 탐색과 삽입, 삭제 모두 O(logN) 시간만에 할 수있음, 삽입과 삭제를 O(logN)만에 할 수 있는 것이 메리트.
1. 라이브러리 : #include<priority_queue>
1. 라이브러리 상의 정의(?) :힙또는 우선순위 큐로도 불림. 설정한 우선순위(default는 값이 높은 것 먼저)를 따져서 젤 위로 보낸다.
1. 연산 : push,top, pop 연산.
1. 단순구현: 최대힙, 최소힙, 절댓값 힙 등등
1. 응용 : 다익스트라 알고리즘(VlogE 시간복잡도), 힙 정렬알고리즘(까먹은듯.. ㅠ).

- 풀어볼 문제 :boj 11279 최대힙, boj 1927 최소힙, boj11286 절댓값 힙, boj 1715,2075,2014,2696

## greedy algorithm

1. Def: Selecting best solution at that moment(satisfying greedy choice property & optimal substructure)
1. can used with heap structure
1. application : dijkstra algorithm(with heap)
1. problems : scheduling algorithm, coin selecting, 