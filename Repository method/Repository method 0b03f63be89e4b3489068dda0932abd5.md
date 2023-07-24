# Repository method

<aside>
❓ `**method**
`*findBy*` : SQL문에서 특정한 칼럼의 값을 조회할 때는 쿼리 메소드의 이름을 findBy로 시작하는 방식을 이용, JPA에서 ID값을 파라미터로 SELECT 할 수 있는 기본 findById 메소드를 제공한다. 하지만 ID 필드가 아닌 다른 여러 필드들로도 데이터를 조회할 경우가 생기게된다
`*findAll*` : 일반적으로 데이터베이스나 다른 데이터 소스에서 모든 데이터를 검색하여 해당 데이터를 포함하는 객체의 목록을 반환하는 메서드입니다. "findAll" 메서드는 일반적으로 데이터 소스에 대한 쿼리를 실행하고, 결과를 객체 형태로 변환하여 목록으로 반환합니다.
`*save*` : insert, update 둘 다 할 수 있다.
`*valueOf*` : String값을 enum에서 가져옴. 값이 없으면  예외 발생.
`*.ofNullable*` : 값이 null일 수도, null이 아닐 수도 있는 경우에 사용

</aside>

---