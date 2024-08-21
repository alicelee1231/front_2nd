## 체크포인트

### PR 올리기 전에 확인사항

1. head barnch와 sync를 맞춰주세요.

```bash
$ git pull https://github.com/hanghae-plus/front_2nd.git main
```

2. base branch를 `hanghae-plus:main`이 아니라 `hanghae-plus:<본안아이디>` 로 수정해주세요 확인해주세요.
  
### 성능 최적화 체크리스트

### 기본과제

1. SearchDialog.tsx 개선
    - [ ] API 호출 최적화
    - [ ] 불필요한 연산 방지
    - [ ] 불필요한 렌더링 방지
2. DnD 성능 개선
    - [ ] Drag 렌더링 최적화
    - [ ] Drop 렌더링 최적화

### 심화과제

- [ ] `server.tsx`만 수정하여 렌더링 최적화 완료

### 고민해보면 좋은 지점

Q. NextJS를 사용하고 있다면, 어떻게 SSR을 빠르게 할 수 있을까요??
A. (한번 본인의 생각을 이야기해주세요)
