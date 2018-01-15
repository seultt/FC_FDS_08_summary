웹표준과 웹접근성 (HTML&CSS)
===
---
# Internet
인터넷 서비스라는 항목아래, email, telnet, 등 여러가지가 있었지만, 이제는 이런 항목들을 웹에서 처리하기 때문에, www(World Wide Web) 아래 통합됬다.

---
# Web
Web은 Back-end와 Front-end로 나뉜다. 
Back-end는 서버쪽에서 데이터를 응용레벨에서 다룬다면, Front-end는 사용자가 보여지는 Presentation 레이어에서 웹브라우저를 다룬다.

# Front-end Tools
1. HTML5 (Structure)
2. CSS3 (스타일링)
3. Javascript (Application)

---
# Web Standards
W3C에서 html4.0과 xhtml 1.0, 2.0까지 표준을 만들어왔다.
하지만, 애플, 모질라, 오페라가 뭉쳐서 새로운 표준을 만든다는 목표로 __WHATWG__ 라는 그룹을 만들었다. 
W3C에서 WHATWG와 협업해 새로운 표준을 만들게 되었고 그게 현재 쓰고있는 html5표준이다.

---
# Accessibility
웹서비스는 어떤 장애를 가지고있든 모두 사용 가능하게 접근성을 가지고 있어야한다.

---
# HTML + CSS
---

#### html 4.0- 기준과 rule이 느슨함
#### xhtml- rule이 더 엄격해짐
###### 예를 들면 html4에서는 태그를 닫지않고 넘어가도 됬다면 xhtml에서는 꼭 마치는 태그를 달아야 했다. 
---
## HTML코드  
### HTML역사와 초기설정 
   - HTML4 > XHTML > HTML5 발전 
   - 초기설정 사항 
      1. \<DOCTYPE> : 이것을 통해서 HTML버젼을 결정한다. (미사용시 비정상적 작동 가능) 
      2. \<html lang="ko"> : 웹피이지 사용 언어 설정값.   
      3. \<meta charset="UTF-8"> : 웹페이지 캐릭터 설정값. 
      4. \<link> : CSS 및 이미지 파일 연결 
      5. \<title> : 웹페이지 타이틀. 위의것들 보다 먼저 오면 안된다.  
---

# 만드는 순서  
   1. outline 설계 (웹페이지, 애플리케이션따라 다름) : 3단, 4단 등... 
   2. TAG구조 잡기 : semantic하게 설계
   3. TAG네이밍 잡기 : 네이밍인벤션을 통일하여 사용 (수업에서는 KebabCase 사용)