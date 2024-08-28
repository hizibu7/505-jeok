## 📝 오늘 공부한 내용
> React의 핵심 특징 중 하나인 VirtualDOM에 대해서 공부했다.

## 😲 오늘 깨달은 내용
VirtualDOM을 사용하면 실제 DOM 조작에 비해 성능이 훨씬 향상된다는 것을 알게 되었다. 
특히, VirtualDOM은 변경된 부분만 업데이트하여 전체 DOM을 다시 그리는 것을 방지해주기 때문에, 
대규모 애플리케이션에서 효율적이다. 이전에는 단순히 ‘빠르다’라고만 알고 있었는데, 
그 이유가 실제 DOM 조작을 최소화하는 데 있다는 것을 깨달았다.

## 🥲 오늘 이해못했거나 궁금한 내용
1. VirtualDOM의 동작 원리: VirtualDOM이 실제 DOM과 어떻게 비교하고 차이를 감지하는지, 그리고 그 과정을 어떻게 효율적으로 수행하는지에 대해 더 깊이 알고 싶다.
2. Reconciliation 과정: VirtualDOM에서 Reconciliation(화해) 과정이 정확히 어떻게 이루어지는지 구체적으로 이해하지 못했다. 이 과정에서 최적화는 어떤 방식으로 이루어지는지 궁금하다.
   
## 📁 참고한 자료 및 사진 첨부
- React 공식 문서: VirtualDOM과 Reconciliation에 대한 자세한 설명이 있는 페이지를 참고했다. React 공식 문서
- 블로그 포스트: React Virtual DOM 이해하기라는 블로그 글을 통해 VirtualDOM의 성능 향상 원리에 대한 개념을 보충했다.
- YouTube 강의: React Virtual DOM Explained라는 제목의 YouTube 강의를 시청하면서, 시각적으로 이해할 수 있었다.
