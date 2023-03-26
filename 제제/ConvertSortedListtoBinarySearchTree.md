# 109. Convert Sorted List to Binary Search Tree
### https://leetcode.com/problems/convert-sorted-list-to-binary-search-tree/

![img.png](img.png)

- 접근법 : 균형이진트리?
  - 각 노드의 왼쪽 서브 트리의 높이hL와 오른쪽 서브 트리의 높이 hR의 차이가 1 이하인 트리
  - hL-hR 값인 높이 차이를 노드의 균형 인수(BF)라고 한다
  - 균형 인수를 -1, 0, +1만 가지게 함으로써 균형을 항상 유지한다
  - https://foxtrotin.tistory.com/191


