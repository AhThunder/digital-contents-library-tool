---
name: Feature request
about: Suggest an idea for this project
title: ''
labels: ''
assignees: ''

---

name: 💡 기능 제안
description: 새로운 아이디어나 개선 사항을 제안해 주세요.
title: "[Feature] "
labels: ["enhancement"]
body:
  - type: textarea
    id: pitch
    attributes:
      label: 어떤 기능이 추가되면 좋을까요?
      description: 제안하고 싶은 기능에 대해 설명해 주세요.
    validations:
      required: true
  - type: textarea
    id: context
    attributes:
      label: 왜 이 기능이 필요한가요?
      description: 이 기능이 어떤 문제를 해결해주거나 편리함을 주는지 설명해 주세요.
