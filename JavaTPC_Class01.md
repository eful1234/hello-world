# Class

1. Private

---

- **정보은닉** : 다른 객체로부터의 접근을 막는 것.<br>
  - 상태를 보호하는 것 -> 외부로부터의 직접적인 접근을 막는다<br>
  - 사람의 **위** 같은 역할.

```java
public class MemberVO{
    private String name;

    public MemberVO(){

    }
}

MemberVO m = new MemberVO();

m.name = "Man";

```

~~m.name = "Man";~~

private으로 변수를 지정한 경우 m을 통해 접근할 수 없다.
