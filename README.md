# P.S-Archive-
코딩테스트 학습과 기록을 위한 레포
🧩 폴더 구조
 ┣ 📁 baekjoon/
 ┣ 📁 programmers/
 ┣ 📁 Book/
 ┗ README.md

 ✏️ 문제 파일 템플릿
 ---
site: Baekjoon
id: 1000
title: A+B
lang: python
tags: [implementation, io]
difficulty: Bronze
---

## 🚀 접근 방식
- 입력값을 공백 기준으로 분리
- 두 수를 더한 결과 출력

## 📚 **참고 자료**
- [Baekjoon Online Judge](https://www.acmicpc.net/)
- 문제 풀이를 위한 학습 자료

## 🧾회고
- 문제 풀이를 하며 겪은 어려움 및 개선점 정

## 💻 코드
```python
a, b = map(int, input().split())
print(a + b)
