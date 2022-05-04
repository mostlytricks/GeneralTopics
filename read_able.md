# 기억남는 읽을거리들

## 2022-04

- [기술 부채와 새로운 도메인 이해에 대한 이야기](https://engineering.linecorp.com/ko/blog/about-messaging-hub-1/)

> 생각해보니 아무리 뛰어난 IT기업이고 좋은 기술 블로그를 쓰는 기업이라 하더라도, 항상 그 첨단의 안정적인 기술을 쓰기만 하는 것을 아닐터였다. 분명 더 나은 툴, 더 나은 문화, 
> 혹은 더 나은 온보딩과 새로운 아키텍쳐 이식까지, 고민을 하고 공유하고, 그걸 다시 살을 붙여 바꿔나가는 사람이 있는가 없는가의 차이 아니었을까.
> 바꾸는 방법과 흐름에 대한 내용을 담기 좋은 글이었다.


> - 서버 코드를 보다가, '어, 있어야 할 게 왜 없지?'
> - 그러나 놀라울 만큼 관심을 받지 못했습니다.


- [Domain Logic? SQL? App에서 구현?](https://medium.com/inato/our-experience-using-sql-with-ddd-96c2024d435c)

> hospital을 상속 받은 BaseHospital vs DB에서는 어떻게 저장하지의 관점
> - 결국 DB에서 큰 하나의 테이블을 만들거면 똑같은거 아닌가? 고민하던 부분인데 비슷한 고민을 하고 있었다!
> - single table에 nullable column 넣어서 flag/option을 주는 방법 : 역직렬화 시점에 어떤 타입인지 해석해야 하고 해석하는 코드를 구현해야 해서 복잡도 증가
> - multi table : sql제약이 커지고 복잡해진다.

> 그래서 DDD를 어떻게 썼느냐, 그냥 복잡한 쿼리를 감수하고 domain object를 통합하는데 사용한다. multi table 전략.
