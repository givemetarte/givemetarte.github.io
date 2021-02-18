---
title:  "Open Data Day 사이트 한글 번역하기"
excerpt: "opendataday.org/kr/의 한글 번역을 해보았다. github으로 다른 팀에 contribute할 수 있는 좋은 기회였다!"
header:
  teaser: /assets/images/blog/opendataday-korean.png

categories:
  - Team.Cayley
tags:
  - open data day
  - 오픈 데이터 데이
  - Team.Cayley 
  - 코로나19 데이터
last_modified_at: 2021-02-18T11:29:00-05:00
gallery:
  - url: /assets/images/blog/opendataday-korean.png
    image_path: /assets/images/blog/opendataday-korean.png
    alt: "opendataday-korean-translation"


---

`opendataday.org/kr/`의 한글 번역을 해보았다. github으로 다른 팀에 contribute할 수 있는 좋은 기회였다! 나름 서신 한영 번역 봉사를 1년 여간 했었는데도 번역투가 짙은 것은 좀 아쉽지만🥲 [여기](https://opendataday.org/kr/)를 클릭하면, 한국어로 번역된 Open Data Day 홈페이지를 확인할 수 있다. 

{% capture fig_img %}
[![foo](/assets/images/blog/opendataday-korean.png)](https://opendataday.org/kr/)
{% endcapture %}

{% capture fig_caption %}
Click it and go to Open Data Day website
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>{{ fig_caption | markdownify | remove: "<p>" | remove: "</p>" }}</figcaption>
</figure>

깃헙을 통해 다른 팀에 기여한 것은 참 색다른 경험이었다. 이제껏 혼자 만들고, 혼자 관리해왔던 터라 깃헙으로 하는 협업이 궁금했는데, 이번 작업이 번역과 오류 해결까지 경험해본 좋은 경험이 됐다. 내가 한 번역 파일에는 문제가 없었던 것 같은데, Pull Requests를 하는 과정에서 오류가 발생했다. 그래서 직접 `Open Data Knowledge`의 담당자에게 코멘트를 날려 오류를 해결해달라고 요청했다. 

![error image]({{ site.url }}{{ site.baseurl }}/assets/images/blog/asked-solving-error.png)

짧은 영어 메세지에도 문법을 생각하는 나란...🌝 얼마 지나지 않아 오류를 해결해주었고, 정식으로 한국어 홈페이지가 게시되었다🎉 

![error image]({{ site.url }}{{ site.baseurl }}/assets/images/blog/solved-error-message.png)

거기에 덤으로 [`cherry-picked`](https://dictionary.cambridge.org/dictionary/english/cherry-pick)란 단어까지 알게 됐다. 오류를 기록하려고 체리픽한 모양이다. 이렇게 오류를 해결하고 한국어로 번역된 페이지를 보니 재미있다! 

또 다른 포스팅으로 한국의 Open Data Day 때 열릴 세션을 자세히 소개하겠지만, 이번에 발표하는 `Team.Cayley`는 "코로나19 데이터 분석 A to Z"를 주제로 발표한다. 2021년 3월 6일 오후 2-5시까지 유투브 생방송으로 볼 수 있으니, 모두들 많은 참여를 부탁드립니다.


