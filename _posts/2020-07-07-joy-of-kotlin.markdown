---
layout: post
title: "코틀린을 다루는 기술"
date: 2020-07-07
categories: book
author: Gamgoon
---

코틀린 입문서로 ['Kotlin in Action'](https://www.aladin.co.kr/shop/wproduct.aspx?ItemId=120267010) 다음으로 점찍어 뒀던 ['Joy of Kotlin'](https://www.manning.com/books/the-joy-of-kotlin?query=joy%20of) 이란 책이 번역서로 나왔다.

사실 원서 e-book을 구입해 둔 상태였지만, 실제 업무에서 코틀린을 사용하지 않다보니 의욕이 생기지 않는 상태였다. 다만, 코틀린이란 언어에 대한 인상은 'Kotlin in Action'을 통해 매우 긍정적으로 남아 있었고, 마침 역자 또한 오현석님이라 읽을 수 밖에 없었다.

먼저 kotlin in action을 통해 코틀린에 대한 긍정적인 인상이 남은 첫번째 이유는 "자바와의 상호운용성의 강조였"다. (참고로 kotlin in action의 저자들은 코틀린 언어 개발에 참여한 개발자이다.) 그런 느낌은 책 전반에서 느낄 수 있었는데, 이는 특정 프로그래밍 패러다임을 강조하기 보다는 자바라는 언어의 개선과 함께 실용적인 변화를 추구했다는 점이 자바 개발자입장에서는 긍정적으로 다가왔다.

'코틀린을 다루는 기술' 이 책을 얘기하기에 앞서 엉뚱한 책 얘기만 늘어놓은 것 같은데, 결론부터 얘기 하자면 이책은 내가 기대했던 그런 책은 아니었다. 나는 코틀린에 대한 입문서 이후 실제 개발에 사용함에 있어서 도움이 될 만한 실용적인 내용을 기대했었지만, 그렇지 못했다. 이 책의 제목을 다시 지어보라고 한다면 "코틀린을 이용한 함수형 프로그래밍 (functional programming in kotlin)" 또는 "코틀린으로 함수형 프로그래밍을 다루는 기술" 정도가 어울리지 않을까? (나중에 알게 되었지만 이 책의 저자는 ['Functional Programming in Java](https://www.manning.com/books/functional-programming-in-java?query=Pierre-Yves%20Saumont) 라는 책도 썼었다.)

정리하자면 이 책은 코틀린을 좀 더 함수형답게 사용하도록 알려주는 책이다. 사실 함수형 프로그래밍은 새롭지 않다. 이미 자바도 8버전부터 함수형 프로그래밍의 기능들이 일부 반영되기 시작하였고, 언젠가 부터 '함수형 프로그래밍' 이란 문구가 앞에 붙은 기존의 많은 언어들의 책들이 쏟아져 나오기 시작했다. 하지만 정작 '함수형 프로그래밍'에 대한 개념을 제대로 잡기란 쉽지 않았다.

이 책에서는 역자의 말처럼 '안전한' 프로그래밍을 강조한다. 프로그램을 좀 더 안전하게 만들기 위한 특징들을 이야기하며 그 특징들은 함수형 프로그래밍을 통해 도달할 수 있음을 얘기한다.

그리고 함수형 프로그래밍에 대한 기본적인 개념과 코틀린을 이용해 사용하는 방법들을 차근차근 설명한다. 설명자체가 어렵게 느껴지진 않지만, 익숙하지 않은 개념과 단어들은 머리속에 쏙 들어오지만은 않는다. 그리고 제대로 학습하기 위해서는 책의 연습문제들을 모두 풀어봐야만 한다. 어떤 개념을 설명하고 부차적인 연습문제를 내는게 아니라 해당 개념이나 방법을 설명하기 위한 문제이기 때문이다. 해답이 바로 이어지기에 정답을 찾아 뒤로 앞으로 책장을 넘길 필요는 없다. 그리고 챕터별로 만들게 되는 클래스들은 이후 예제에서 계속적으로 사용하기 때문에 예제코드를 모드 작성하고 싶다면 중간에 띄어 넘지 않는게 좋다. 

그렇게 11장 정도까지 읽다보면 이런 물음이 생긴다.

> "이렇게 까지 해야 하는 것인가?"

안전한 프로그래밍을 위해 필요한 함수를 활용하는 방법들과 부가적으로 필요한 여러 객체들을 만드는데... 코틀린을 사용해서 안전한 프로그래밍을 하기 위해 이런 것들이 없으면 안되는 것인가? 이와 같은 현자타임을 수시로 마주하게 된다. 

처음 코틀린 언어에 가지고 있던 실용적인 언어라는 인상에서 '함수형 언어'라는 넘어야 할 장벽이 추가로 생긴 것 같지만 함수형 프로그래밍에 대해 조금은 알게 되었다는 생각이 든다. 몇번 더 읽어 봐야겠다.