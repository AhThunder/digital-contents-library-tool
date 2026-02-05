---
name: Bug report
about: Create a report to help us improve
title: ''
labels: ''
assignees: ''

---

name:  버그 제보
description: 작동하지 않는 기능이나 오류를 제보해 주세요.
title: "[Bug] "
labels: ["bug"]
body:
  - type: textarea
    id: description
    attributes:
      label: 어떤 문제가 발생했나요?
      description: 발생한 오류에 대해 자세히 설명해 주세요.
      placeholder: 예: 미리보기 창이 떴다가 바로 사라집니다.
    validations:
      required: true
  - type: input
    id: browser
    attributes:
      label: 브라우저 및 OS 정보
      placeholder: 예: Chrome 120.0, Windows 11
  - type: textarea
    id: steps
    attributes:
      label: 재현 방법
      description: 문제를 재현하기 위해 어떤 행동을 했나요?
      placeholder: 1. 리스트 페이지 접속 2. 동기화 버튼 클릭 ...
