# Getter, Setter

---

## Getter, Setter 란?

Getter은 **인스턴스 변수를 반환하고** Setter은 **인스턴스 변수를**

**대입하거나 수정한다**

관습에 따라 getter은 변수 앞에 get, setter은 변수 앞에 set 이 붙고

그 변수들의 앞글자는 대문자로 한다

---

```java
public class Vehicle {
  private String color;
  
  // Getter
  public String getColor() {
    return color;
  }
  
  // Setter
  public void setColor(String c) {
    this.color = c;
  }
}
```

```java
public static void main(String[] args) {
  Vehicle v1 = new Vehicle();
  v1.setColor("Red");
  System.out.println(v1.getColor());
}
//color 필드는 private로 선언되어 있기 때문에, 클래스 외부에서는 직접 접근할 수 없습니다. 
//대신에 setColor와 getColor 메소드를 통해서만 값을 설정하고 가져올 수 있습니다.
```

getter 은 객체의 attribute(변수) 를 반환하고 setter 은

파라미터를 받아서 attribute 에 할당한다.