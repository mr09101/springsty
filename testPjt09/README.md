의존객체 자동 주입이란 ?
스프링설정 파일에서 의존 객체를 주입할 때 <constructor arg> 또는 <property> 태그로 의존 대상 객체를 명시하지 않아도 스프링 컨테이너가 자동으로 필요한 의존 대상 객체를 찾아서 의존 대상 객체가 필요한 객체에 주입해 주는 기능이다 .
구현방법은 @Autowired 와 @Resource 어노테이션을 이용해서 쉽게 구현할 수 있다

@Autowired - 주입하려고 하는 객체의 타입이 일치 하는 객체를 자동으로 주입한다

@Resource  - 주입하려고 하는 객체의 이름이 일치 하는 객체를 자동으로 주입한다