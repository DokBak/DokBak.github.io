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
# Env : MacOS, Windows, Linux
# Language : Java, C, C++, C#, Python, bash, zsh
# Tools : Terminal, Visual Studio Code, IntelliJ, Xcode
# etc : homebrew
#
tags: [MacOS, homebrew, Terminal]
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

# Homebrew 설치하기 

macOS용 패키지 관리자

## 1. Homebrew 공식사이트 접속하기
### 1-1. 영문 사이트
> https://brew.sh/

### 1-2. 한국어 사이트
> https://brew.sh/index_ko

### 1-3. 일본어 사이트
> https://brew.sh/index_ja

## 2. 인스톨 (Terminal)

```    
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)
```

## 3. 설치 확인 (Terminal)

### 3-1. Homebrew 버전 확인 (Terminal)
```
brew --version
```

### 3-2. 간단히 메뉴얼이 출력 (Terminal)
```
brew
```