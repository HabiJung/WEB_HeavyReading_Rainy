<!-- 팀명 -->
# 진중한 문고 &#128218; Heavy Reading &#128218;
<img src="./project_docs/rok-logo.png" width="500" height="300" />


<!-- 팀 소개 -->
# &#128218; Team Rainy
## Team Members
- 오재엽 (ohbcj0831@gmail.com), [Github](https://github.com/Ohjaeyeop)
- 정하빈 (ororaskyx@gmail.com), [Github](https://github.com/habijung)

## About Rainy
팀 소개 내용


<!-- 프로젝트 설명 -->
# Project Abstract
진중문고를 활용한 독서 장려 서비스입니다.


<!-- 프로젝트 시연 동영상 -->
# 시연 동영상
[![Video](https://img.youtube.com/vi/S-thTTqefls/0.jpg)](https://youtu.be/S-thTTqefls)


<!-- 컴퓨터 구성 / 필수 조건 안내 -->
# Prerequisites
Name | Version (or Higher)
---- | -------
Python | 3.5.3
pip3 | 20.2.4
Django | 2.2.16
Html | 5
Chrome | 86 (64-bit)


<!-- 설치 안내 -->
# Installation Process
```bash
$ git clone https://github.com/osamhack2020/WEB_HeavyReading_Rainy.git
$ cd WEB_HeavyReading_Rainy
$ python3 --version
$ python3 -m pip install --upgrade pip
$ sudo apt-get install python3-setuptools
$ pip3 install -r requirements.txt
$ pip3 list
$ cd rainy_project
$ sudo pkill -f runserver
$ python3 manage.py runserver
```


<!-- 프로젝트 사용법 -->
# Getting Started
- 기능별 사용법 기술


<!-- 기술 스택 -->
# Technique Used
## front-end
- html
- css
- javascript
 
## back-end
 -  django
 -  python
 -  jquery


<!-- 파일 구성 -->
# File Tree
```bash
WEB_HeavyReading_Rainy
    ├── project_docs                // project description files
    ├── rainy_project
    │   ├── accounts                // [Django App] accounts
    │   │   ├── migrations
    │   │   └── templates/accounts  // accounts page html templates
    │   ├── mainpage                // [Django App] mainpage
    │   │   ├── migrations
    │   │   └── templates           // mainpage page html templates
    │   ├── media                   // img data of db
    │   │   ├── CACHE
    │   │   └── images
    │   ├── mypage                  // [Django App] mypage
    │   │   ├── migrations
    │   │   └── templates           // mypage page html templates
    │   ├── notice                  // notice django app
    │   │   ├── migrations
    │   │   └── templates           // notice page html templates
    │   ├── rainy                   // [Django Project]
    │   │   ├── settings.py         // project setting file
    │   │   └── urls.py             // url patterns file
    │   ├── static                  // static loading files
    │   │   ├── accounts/css        // accounts stylesheet
    │   │   ├── admin               // admin manage files
    │   │   ├── css                 // common & mainpage stylesheet
    │   │   ├── img                 // static image files
    │   │   ├── js                  // script files
    │   │   ├── mypage/css          // mypage stylesheet
    │   │   ├── notice/css          // notice stylesheet
    │   │   └── survey/css          // survey form stylesheet
    │   ├── staticfiles
    │   ├── db.sqlite3              // database
    │   └── manage.py               // Django manage file
    ├── .gitignore
    ├── LICENSE.md
    └── README.md
```


<!-- 저작권 및 사용권 정보 -->
# License
[MIT License](./LICENSE.md)