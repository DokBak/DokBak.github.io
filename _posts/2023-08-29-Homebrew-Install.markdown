---
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)
lng_pair: id_2023_08_29_post
title: Homebrew 설치

# post specific
# if not specified, .name will be used from _data/owner/[language].yml
author: DokBak
# multiple category is not supported
category: Setting
# multiple tag entries are possible
# Env : Macos, Windows, Linux
# Language : Java, C, C++, C#, Python, bash, zsh
# Tools : Terminal, Visual Studio Code, IntelliJ, Xcode
# etc : homebrew
#
tags: [Macos, homebrew, Terminal]
# thumbnail image for post
img: ":settings.png"
# disable comments on this page
#comments_disable: true

# publish date
date: 2023-08-29 22:51:00 +0900

# seo
# if not specified, date will be used.
#meta_modify_date: 2022-02-10 08:11:06 +0900
# check the meta_common_description in _data/owner/[language].yml
#meta_description: ""

# optional
# please use the "image_viewer_on" below to enable image viewer for individual pages or posts (_posts/ or [language]/_posts folders).
# image viewer can be enabled or disabled for all posts using the "image_viewer_posts: true" setting in _data/conf/main.yml.
#image_viewer_on: true
# please use the "image_lazy_loader_on" below to enable image lazy loader for individual pages or posts (_posts/ or [language]/_posts folders).
# image lazy loader can be enabled or disabled for all posts using the "image_lazy_loader_posts: true" setting in _data/conf/main.yml.
#image_lazy_loader_on: true
# exclude from on site search
#on_site_search_exclude: true
# exclude from search engines
#search_engine_exclude: true
# to disable this page, simply set published: false or delete this file
#published: false
---

<!-- outline-start -->

MacOS 환경에서 프로그램 관리시 유용한 패키지 관리 툴

<!-- outline-end -->

# Homebrew
### 1. Homebrew 공식사이트 접속하기
###### 1-1. 영문 사이트
> https://brew.sh/
###### 1-2. 한국어 사이트
> https://brew.sh/index_ko
###### 1-3. 일본어 사이트
> https://brew.sh/index_ja
### 2. Homebrew 인스톨 (Terminal)
```    
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)
```
### 3. Homebrew 설치 확인 
###### 3-1. Homebrew 버전 확인
```
brew --version
```
###### 3-2. 간단히 메뉴얼을 출력
```
brew
```

## 4. Mas
앱스토에서 설치하는 애플리케이션을 설치 할 수 있도록 도와주는 패키지
###### 4-1. Mas 검색
```
brew search mas
```
###### 4-2. Mas 설치
```
brew install mas
```
###### 4-3. Mas 설치 확인
```
brew list
mas version
```
###### 4-4. Mas 추천 프로그램

1) 마그넷  
**441258766** Magnet マグネット (2.11.0)

```
mas search magnet
mas install 441258766
mas list
mas upgrade
```

> 주 사용 단축키 확인   
> 
> 화면의 1/2만 표시  
>> 왼쪽 : ^ + ⌥ + ◀︎  
>> 오른쪽 : ^ + ⌥ + ▶︎  
>> 위 : ^ + ⌥ + ▲  
>> 아래 : ^ + ⌥ + ▼  
>
> 화면의 1/4만 표시  
>> 왼쪽 위 : ^ + ⌥ + U  
>> 오른쪽 위: ^ + ⌥ + I  
>> 왼쪽 아래 : ^ + ⌥ + J  
>> 오른쪽 아래 : ^ + ⌥ + K  
>
> 화면의 2/3만 표시  
>> 좌측 2/3 : ^ + ⌥ + E  
>> 우측 2/3 : ^ + ⌥ + T  
>
> 화면 전체  
>> 최대화 : ^ + ⌥ + ↩︎  
>> 중앙 : ^ + ⌥ + C  
>> 복구 : ^ + ⌥ + ⌫  

2) 카카오톡  
**869223134**  KakaoTalk (3.2.5)

```
mas search KakaoTalk
mas install 869223134
mas list
mas upgrade
```
3) Xcode  
**497799835** Xcode (14.3)

```
mas search Xcode
mas install 497799835
mas list
mas upgrade
```
4) 라인메신저  
**539883307** LINE (8.2.0)

```
mas search LINE
mas install 539883307
mas list
mas upgrade
```
## 5. homebrew 추천 프로그램
1) Visual Studio Code
```
brew search visual-studio-code
brew install --cask visual-studio-code
brew list
```
2) springtoolsuite
```
brew search springtoolsuite
brew install --cask springtoolsuite
brew list
```
3) Xcode
```
brew search Xcode
brew install --cask Xcodes
brew list
```
