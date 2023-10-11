# 전남대학교 프로그램 경진대회 가이드
## Python3, Java, Javascript, C++ 중 택1, 다양한 알고리즘 문제를 주어진 시간내 해결하는 방식
---
## 참가대상: 전남대학교 재학생(학부생 및 대학원생)
## 경진대회 운영 관련
  - SW중심대학사업단: 062-530-5356, swysu@jnu.ac.kr
  - 채널톡: https://programmers-certi.channel.io/lounge

## 참고자료
  - [프로그래머스 코딩테스트 연습](https://school.programmers.co.kr/learn/challenges?order=recent&page=1)
  - [백준 코딩테스트](https://www.acmicpc.net/)
  - [프로그래머스 PCCP.E 샘플 문제](https://certi.programmers.co.kr/about/sample)

## jupyter lab 활용하기(Python, Java, Javascript)
  - [파이썬 다운로드:버전 3.11.5](https://www.python.org/downloads)
  - [자바 다운로드](https://www.oracle.com/java/technologies/downloads/)
  - [Nodejs 다운로드](https://nodejs.org/ko/download)
  - [바탕화면에 contest 폴더 생성 및 이동 후 자바 커널 다운로드](https://github.com/SpencerPark/IJava/releases)
<br>
## jupyterlab 환경 구성
```
#Powershell prompt 실행(위치: 바탕화면\contest)
pip install jupyterlab
$Env.Path += ';C:\Program Files\Java\jdk-21\bin'
$Env.JAVA_HOME='C:\Program Files\Java\jdk-21'
cd ijava-1.3.0;python install.py
```
<br>
```
#Node.js command prompt 실행(위치: 바탕화면\contest)
node --version
npm --version
npm install -g ijavascript
ijsinstall

#Python, Java, javascript 커널 설치 완료 후 주피터랩 실행
jupyter lab
```


