Last login: Wed Dec  3 15:26:24 on ttys000
~ ❯ clear                                                              16:03:36
~ ❯ cd project/batchar                                                 16:03:40
~/project/batchar main !1 ❯ clear                                      16:03:47
~/project/batchar main !1 ❯ touch .gitmessage.txt                                16:03:56

code .gitmessage.txt
~/project/batchar main !1 ?1 ❯ git config commit.template .gitmessage.txt        16:04:31
~/project/batchar main !1 ?1 ❯ git add .gitmessage.txt                           16:04:51

git commit -m "add commit template"
[main 5f817e9] add commit template
 1 file changed, 33 insertions(+)
 create mode 100644 .gitmessage.txt
~/project/batchar main ⇡1 !1 ❯ mkdir -p .github/ISSUE_TEMPLATE                   16:04:56

cd .github/ISSUE_TEMPLATE
~/pr/batchar/.gith/ISSUE_TEMPLATE main ⇡1 !1 ❯ ----                              16:05:01
name: 기능 요청 (Feature Request)
about: 새로운 기능 추가나 개선을 요청합니다.
title: "[FEATURE] 간단한 제목을 입력하세요"
labels: feature
assignees: ''
---

## 📌 문제 제기 (Problem Statement)

이 기능이 왜 필요한가요?
어떤 문제를 해결하거나 개선할 수 있나요?

## ✅ 제안하는 기능 (Proposed Feature)

어떤 기능을 추가하거나 변경하고 싶으신가요?
가능하다면 구체적인 동작 방식이나 예시를 들어주세요.

## 🔁 대안 (Alternatives Considered)

다른 가능한 해결 방법이나 대안을 고려해 보셨나요?

## ℹ️









