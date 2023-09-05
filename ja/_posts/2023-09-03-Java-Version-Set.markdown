---
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)
lng_pair: id_2023_09_03_post
title: Java Version Set

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
tags: [Macos, Java]
# thumbnail image for post
img: ":settings.png"
# disable comments on this page
#comments_disable: true

# publish date
date: 2023-09-03 22:51:00 +0900

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

MacOS環境で使用したいジャバのバージョンに変更する方法

<!-- outline-end -->

# Homebrew
### 1. バージョン確認
###### 1-1. インストールされているジャババージョン確認 / パス確認
```
/usr/libexec/java_home -V
```
###### 1-2. 現在使用中のジャババージョン確認
```
java -version
```
###### 1-3. 注使用ジェル確認
```
echo $SHELL
```
|     | **zsh Shell** | **bash Shell** | 
| :-: | :-----------: | :------------: |
| 결과 | /bin/zsh      | /bin_bash      |

### 2. 設定ファイル修正
###### 2-1. VIエディター実行
```
# zsh Shell
vi ~/.zshrc
# bash Shell
vi ~/.bash_profile
```
|         | **zsh Shell** | **bash Shell**     | 
| :-----: | :-----------: | :----------------: |
| 실행명령어 | vi ~/.zshrc   | vi ~/.bash_profile |
###### 2-2. 設定ファイルに追加する内容(1-1.で確認した内容追加)

```
# 使用しないバージョンの先頭に#を追加しで注釈処理
# Java 8 
export JAVA_HOME=/Library/Java/JavaVirtualMachines/adoptopenjdk-8.jdk/Contents/Home
# Java 11
export JAVA_HOME=/Library/Java/JavaVirtualMachines/adoptopenjdk-11.jdk/Contents/Home
```
###### 2-3. 編集した環境変数ファイルを適用
```
# zsh Shell
source ~/.zshrc
# bash Shell
source ~/.bash_profile 
```
### 3. バージョン確認
###### 3-1. ジャババージョン確認
```
java -version
```