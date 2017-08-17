---
layout: post
title: github 레포지토리 검색 팁
author: BBKim
---

# github 검색 팁
최근 github에서 일정 수 이상의 star를 가진 레포지토리 중에 하나를 잡아
취약점이 발생할 수 있는 부분을 찾아 컨트리뷰터가 되어 보자는 생각에서
github 레포지토리중에 특정 조건을 만족하는 레포지토리를 찾고다니던 와중에
github 자체적으로 검색 키워드를 지원한다는것을 알게되었습니다. 

<https://help.github.com/articles/searching-repositories/>


## 검색 꿀팁
-----

여러 검색 키워드 중 자주 쓸만한 검색 키워드들을 몇개 뽑아 보았습니다. 

1. fork 수 기반 검색
- forks:5 matches repositories with only five forks.

- forks:>=205 matches repositories with at least 205 forks.

- forks:10..20 matches repositories with 10 to 20 forks.

2. 토픽 기반 검색
- topic:TOPIC	topic:jekyll matches repositories that have been classified with the topic "jekyll."

3. star 기반 검색
- stars:10..20 matches repositories 10 to 20 stars, that are smaller than 1000 KB.

- stars:>=500 fork:true language:php matches repositories with the at least 500 stars, including forked ones, that are written in PHP.