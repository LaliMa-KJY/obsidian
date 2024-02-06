# <span style="background:rgba(255, 183, 139, 0.55)"> ✅ 절차형 SQL</span>

<font color="#4bacc6" size="5px">특징</font>
> <small>DBMS 엔진에서 직접 실행</small>
> <small>BEGIN/END의 블록 구조로 되어있어, 각 기능의 모듈화가 가능하다</small>
> <small>데이터관리 단순화</small>
> <small>무결성 유지 및 일관성 보장</small>
> <small>데이터를 DBMS 안에서 실행하기 때문에 INPUT/OUTPUT 패킷이 적다</small>
> <small>작업의 효율성이 낮다</small>

<font color="#4bacc6" size="5px">✅ 키</font>
> [기본키]
> 		- 테이블(릴레이션)을 대표하는 키로, 다른 테이블(릴레이션)에서 외래키로 참조할 수 있다.
> [외래키]
> 		 - 다른 테이블(릴레이션)의 기본키를 참조하는 키이다.

<font color="#4bacc6" size="5px">✅ 대칭키</font>
> <small>암호화 키와 복호화 키가 같다 -> 키를 알면 문서를 복호화할 수 있다.</small>
> <small>DES, AES</small>
> <small>장점 : 공개키보다 처리 속도가 빠르다</small>
> <small>단점 : 키를 교환해야 하기 때문에 탈취 가능성이 있고, 키 관리를 여러 방면으로 해야한다.</small>


<font color="#4bacc6" size="5px">✅ 공개키 암호화 방식</font>
> <small>공개키와 비밀키가 구분된다 (다르다) -> 키 전달, 교환에 적합하고 인증, 전자서명에 이용 할 수 있다.</small>
> <small>장점 : 대칭키보다 확장성이 좋고, 여러가지 분야에 응용이 가능하다. 키 변화의 빈도가 적다. </small>
> <small>단점 : 키 길이가 길고 복잡한 수학적 연산을 이용하기 때문에 암호화 복호화 속도가 느리다, 중간에 인증 과정이 없어 중간자 공격에 취약하다.</small>

<font color="#4bacc6" size="5px">✅ 트리거</font>
> <small>특정 테이블에 "수정/삽입/삭제" 등 데이터 변경 이벤트가 발생하면 DBMS가 자동으로 실행 되도록 구현된 프로그램</small>
> 데이터 무결성 유지 및 로그 메세지 출력 등 별도 처리를 위해 사용하기도 한다.