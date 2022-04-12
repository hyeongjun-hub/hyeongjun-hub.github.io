---
title: "1월 27일 공부내용 정리"
excerpt: "Take note of what I studied on January 27th"

categories:    
    - Study
tags:
    - Spring
    - Git
---
> 스프링 핵심 원리 - 기본편 (김영한, 인프런)  
* Notion Link: [섹션 8. 빈 생명주기 콜백](https://funny-gourd-490.notion.site/143a2142025541a5aa420942b8dc86b3)
> 깃과 깃허브 
* Notion Link: [깃과 깃허브 공부](https://funny-gourd-490.notion.site/b955ab5a7dce41bca02818cfa89e1ab0)
  
---
오늘은 오전에는 깃허브 블로그와 깃에 대한 궁금증을 해결하기 위해 정보를 찾아보았고 오후에는 스프링 빈의 생명주기와 콜백메소드에 대해서 공부하였다.  
빈 생명주기에 대해 처음에는 이해가 가지 않았는데 예제코드를 천천히 살펴보니 이해가 되었다.  
이해가 안갔던 내용은 setUrl() 부분이었는데 스프링빈이 등록될 때 생성자가 호출되고 그 뒤에 url도 같이 등록된다고 생각하니 이해가 되었다.  
처음엔 setUrl 부분이 초기화 부분이라고 생각하고 강의를 들어서 이해가 되지 않았었다. 하지만 init() 콜백메소드에 있는 collect()메소드가 초기화를 뜻하는 코드였다.