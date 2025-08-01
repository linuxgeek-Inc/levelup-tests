## 💻 리얼리눅스 레벨업 챌린지 실습문제

| 퀘스트    | 배포판                | 문제 번호                                                 | 문제 수 |
| ------ | ------------------ | ----------------------------------------------------- | ---- |
| quest1 | Rocky-9.3          | Q.1 \~ Q.15, Q.20 \~ Q.36, Q.41 \~ Q.67, Q.81 \~ Q.85 | 64   |
| quest2 | Ubuntu-22.04       | Q.16 \~ Q.19, Q.76 \~ Q.80                            | 9    |
| quest3 | Docker             | Q.37 \~ Q.40, Q.68 \~ Q.75                            | 12   |
| quest4 | Kubernetes         | Q.87 \~ Q.100                                         | 14   |
| quest5 | Swarm              | Q.102 \~ Q.110                                        | 9    |
| quest6 | Kubernetes-default (설치전용) | Q.86                                                  | 1    |
| quest7 | Swarm-default(설치전용)      | Q.101                                                 | 1    |

👉 **[실습 문제번호(Q.) 기준 리스트](https://github.com/linuxgeek-Inc/levelup-tests/blob/main/README.md#%EB%A0%88%EB%B2%A8%EC%97%85-%EC%B1%8C%EB%A6%B0%EC%A7%80-%EC%8B%A4%EC%8A%B5%EB%AC%B8%EC%A0%9C-%EB%A6%AC%EC%8A%A4%ED%8A%B8)** 는 아래 정리 되어 있습니다.

---

## ❗ 오류 제보 및 수정 요청 안내

이 저장소는 **리얼리눅스 레벨업 챌린지 실습문제 저장소**입니다. 각 문제 파일은 \[`quest1` \~ `quest7`] 디렉터리 안에 `.md` 파일로 구성되어 있으며, 실습 환경에 따라 Rocky, Ubuntu, Docker, Kubernetes, Swarm 등의 배포판을 기반으로 작성되어 있습니다.

💻 웹 기반 터미널에서 실습할 수 있습니다:

🔗 **[reallinux.co.kr/level-up/home](https://reallinux.co.kr/level-up/home)**

👉 위 링크에서 리눅스 명령어 실습을 직접 해보세요!

### 🛠️ 오류 제보 / 수정 요청 방법

문제를 풀면서 다음과 같은 경우에 자유롭게 **Issue 또는 Pull Request**를 등록해 주세요:

* 문제 설명이 명확하지 않은 경우
* 오탈자나 잘못된 명령어가 포함된 경우
* 실습 환경에서 실행되지 않는 명령어가 있을 경우
* 문제 개선을 위한 제안 사항이 있는 경우

### 📝 Issue 작성 가이드

[Issue 게시판](https://github.com/linuxgeek-Inc/levelup-tests/issues)에 작성하실 때는 아래 양식을 참고해 주세요:

```
제목: [오류 제보] quest1 - 35번 문제에서 명령어 오류

본문:
- 파일 위치: quest1/35.md
- 오류 설명: 예시 명령어에서 `ls -Z`가 Rocky 9.3에서 정상 동작하지 않습니다.
- 제안 내용: `ls -Z` 대신 `ls -lZ`로 변경하면 동작합니다.
- 확인한 환경: Rocky Linux 9.3, Bash 쉘

추가 사항:
(해당되는 경우) 스크린샷이나 오류 메시지 첨부
```

---

### 🔧 Pull Request 작성 가이드

직접 수정을 제안하고 싶으신 경우, [Pull Requests](https://github.com/linuxgeek-Inc/levelup-tests/pulls) 탭을 통해 PR을 보내주시면 됩니다.

PR 작성 시에는 다음 사항을 지켜주시면 빠른 반영에 도움이 됩니다:

1. **브랜치 분기**: `main` 브랜치를 기준으로 새로운 브랜치에서 작업해 주세요.
2. **커밋 메시지 예시**:

   * `fix(quest1/35.md): ls -Z 명령어 수정`
   * `docs(quest3): 문제 설명 문장 자연스럽게 개선`
3. **PR 설명 예시**:

   ```
   변경 내용:
   - quest1/35.md 에서 ls -Z → ls -lZ 로 수정
   - 사용 환경 기준: Rocky 9.3, SELinux 활성화 상태에서 테스트 완료

   관련 이슈:
   - #32
   ```

---

### 🙏 기여해 주시는 모든 분들께 감사드립니다

레벨업 챌린지 학습자 여러분의 참여로 더욱 발전합니다.
작은 제안이나 오타 수정도 매우 환영합니다!

---

### 레벨업 챌린지 실습문제 리스트

| 문제번호 | 배포판 | 퀘스트번호 |
|--------|--------|------------|
| 1 | Rocky-9.3 | quest1 |
| 2 | Rocky-9.3 | quest1 |
| 3 | Rocky-9.3 | quest1 |
| 4 | Rocky-9.3 | quest1 |
| 5 | Rocky-9.3 | quest1 |
| 6 | Rocky-9.3 | quest1 |
| 7 | Rocky-9.3 | quest1 |
| 8 | Rocky-9.3 | quest1 |
| 9 | Rocky-9.3 | quest1 |
| 10 | Rocky-9.3 | quest1 |
| 11 | Rocky-9.3 | quest1 |
| 12 | Rocky-9.3 | quest1 |
| 13 | Rocky-9.3 | quest1 |
| 14 | Rocky-9.3 | quest1 |
| 15 | Rocky-9.3 | quest1 |
| 16 | Ubuntu-22.04 | quest2 |
| 17 | Ubuntu-22.04 | quest2 |
| 18 | Ubuntu-22.04 | quest2 |
| 19 | Ubuntu-22.04 | quest2 |
| 20 | Rocky-9.3 | quest1 |
| 21 | Rocky-9.3 | quest1 |
| 22 | Rocky-9.3 | quest1 |
| 23 | Rocky-9.3 | quest1 |
| 24 | Rocky-9.3 | quest1 |
| 25 | Rocky-9.3 | quest1 |
| 26 | Rocky-9.3 | quest1 |
| 27 | Rocky-9.3 | quest1 |
| 28 | Rocky-9.3 | quest1 |
| 29 | Rocky-9.3 | quest1 |
| 30 | Rocky-9.3 | quest1 |
| 31 | Rocky-9.3 | quest1 |
| 32 | Rocky-9.3 | quest1 |
| 33 | Rocky-9.3 | quest1 |
| 34 | Rocky-9.3 | quest1 |
| 35 | Rocky-9.3 | quest1 |
| 36 | Rocky-9.3 | quest1 |
| 37 | Docker | quest3 |
| 38 | Docker | quest3 |
| 39 | Docker | quest3 |
| 40 | Docker | quest3 |
| 41 | Rocky-9.3 | quest1 |
| 42 | Rocky-9.3 | quest1 |
| 43 | Rocky-9.3 | quest1 |
| 44 | Rocky-9.3 | quest1 |
| 45 | Rocky-9.3 | quest1 |
| 46 | Rocky-9.3 | quest1 |
| 47 | Rocky-9.3 | quest1 |
| 48 | Rocky-9.3 | quest1 |
| 49 | Rocky-9.3 | quest1 |
| 50 | Rocky-9.3 | quest1 |
| 51 | Rocky-9.3 | quest1 |
| 52 | Rocky-9.3 | quest1 |
| 53 | Rocky-9.3 | quest1 |
| 54 | Rocky-9.3 | quest1 |
| 55 | Rocky-9.3 | quest1 |
| 56 | Rocky-9.3 | quest1 |
| 57 | Rocky-9.3 | quest1 |
| 58 | Rocky-9.3 | quest1 |
| 59 | Rocky-9.3 | quest1 |
| 60 | Rocky-9.3 | quest1 |
| 61 | Rocky-9.3 | quest1 |
| 62 | Rocky-9.3 | quest1 |
| 63 | Rocky-9.3 | quest1 |
| 64 | Rocky-9.3 | quest1 |
| 65 | Rocky-9.3 | quest1 |
| 66 | Rocky-9.3 | quest1 |
| 67 | Rocky-9.3 | quest1 |
| 68 | Docker | quest3 |
| 69 | Docker | quest3 |
| 70 | Docker | quest3 |
| 71 | Docker | quest3 |
| 72 | Docker | quest3 |
| 73 | Docker | quest3 |
| 74 | Docker | quest3 |
| 75 | Docker | quest3 |
| 76 | Ubuntu-22.04 | quest2 |
| 77 | Ubuntu-22.04 | quest2 |
| 78 | Ubuntu-22.04 | quest2 |
| 79 | Ubuntu-22.04 | quest2 |
| 80 | Ubuntu-22.04 | quest2 |
| 81 | Rocky-9.3 | quest1 |
| 82 | Rocky-9.3 | quest1 |
| 83 | Rocky-9.3 | quest1 |
| 84 | Rocky-9.3 | quest1 |
| 85 | Rocky-9.3 | quest1 |
| 86 | Kubernetes-default | quest6 |
| 87 | Kubernetes | quest4 |
| 88 | Kubernetes | quest4 |
| 89 | Kubernetes | quest4 |
| 90 | Kubernetes | quest4 |
| 91 | Kubernetes | quest4 |
| 92 | Kubernetes | quest4 |
| 93 | Kubernetes | quest4 |
| 94 | Kubernetes | quest4 |
| 95 | Kubernetes | quest4 |
| 96 | Kubernetes | quest4 |
| 97 | Kubernetes | quest4 |
| 98 | Kubernetes | quest4 |
| 99 | Kubernetes | quest4 |
| 100 | Kubernetes | quest4 |
| 101 | Swarm-default | quest7 |
| 102 | Swarm | quest5 |
| 103 | Swarm | quest5 |
| 104 | Swarm | quest5 |
| 105 | Swarm | quest5 |
| 106 | Swarm | quest5 |
| 107 | Swarm | quest5 |
| 108 | Swarm | quest5 |
| 109 | Swarm | quest5 |
| 110 | Swarm | quest5 |
