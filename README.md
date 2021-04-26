# 숫자 야구 게임
## 진행 방법
* 숫자 야구 게임 요구사항을 파악한다.
* 요구사항에 대한 구현을 완료한 후 자신의 github 아이디에 해당하는 브랜치에 Pull Request(이하 PR)를 통해 과제를 제출한다.

## 과제 제출 과정
* [과제 제출 방법](https://github.com/next-step/nextstep-docs/tree/master/precourse)

## 진행 방식
* 미션
 	+ 기능 요구사항
 	+ 프로그래밍 요구사항
  	+ 과제 진행 요구사항
  	
## 기능 요구사항
+ [o] 1~9 사이의 서로 다른 수로 이루어진 3자리의 수 생성
	* 1~9 사이의 난수 생성
	* 제공된 수를 가지고 있는지 확인
	
+ [o] 사용자에게 값 입력받기 (야구)
	* 사용자에게 값 입력받기
	* 사용자가 입력한 값 체크 (예외처리)
	* 사용자 값 반환하기
	
+ [o] 사용자 값과 야구공 비교하기
	* 3스트라이크 여부
	* 유저에게 힌트 주기 (볼, 스트라이크, 낫싱 메세지 출력)
	* ball 갯수 반환
	* strike 갯수 반환
	
+ [o] 게임 종료여부 체크하기

+ [o] 게임 시작
	* 1~9 사이의 서로 다른 수로 이루어진 3자리의 수(야구공) 생성
	* 사용자에게 값 입력받기
	* 사용자 값과 야구공 비교하기
	* 게임 종료여부 체크하기
	
## 프로그래밍 요구사항

# 메소드 분리
* 자바 코드 컨벤션
* indent depth가 1이어야한다.
* stream api를 사용하지 않는다.
* else (switch)를 사용하지 않는다.
* 메소드의 길이가 10라인을 넘어가지 않는다.

#단위테스트
* 로직에 단위 테스트를 구현한다.
* UI와 구현 코드르 구별한다.
* JUnit5 와 AssertJ 를 사용한다.

## 과제 진행 요구사항
* 미션은 저장소를 fork/clone해 시작한다.
* readme.md 에 기능목록을 정리해 추가한다.
* git의 commit 단위는 앞단계에서 정리한 기능 목록 단위로 추가한다.