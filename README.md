# 숫자 야구 게임
## 진행 방법
* 숫자 야구 게임 요구사항을 파악한다.
* 요구사항에 대한 구현을 완료한 후 자신의 github 아이디에 해당하는 브랜치에 Pull Request(이하 PR)를 통해 과제를 제출한다.

## 과제 제출 과정
* [과제 제출 방법](https://github.com/next-step/nextstep-docs/tree/master/precourse)

---

# 요구 사항 정리

## 진행 방식
* 미션은 <U>**기능요구사항**</U>, <U>**프로그래밍요구사항**</U>, <U>**과제진행요구사항**</U> 세가지로 구성
* 세개의 요구사항을만족 해다 한다.
* 기능을 구현 하기 전에 기능목록을 만든다
* **기능단위로 commit** 하는 방식으로 진행한다

## 기능 요구 사항
* 1~9의 서로 다른 수 3개를 맞추는 게임
* 3개의 숫자는 모두 달라야 한다.
* 게임 조건 
    * 같은수/같은 자리 -> 스트라이크
    * 같은수/다른 자리 -> 볼
    * 수/자리 모두 다를경우 -> 낫싱
* 컴퓨터가 3개의 랜덤 숫자를 선택하고 사용자가 숫자를 입력하여 결과를 출력한다.
* 사용자가 3개의 스트라이크를 얻으면 게임이 종료
* 게임을 완전 종료 or 다시 진행 중 선택 한다.

## 프로그래밍 요구 사항 - 메소드 분리
* 자바 코드 컨벤션을 지킨다.
* indent depth는 2가넘지않도록구현한다.1까지만허용한다.
* **stream api 사용 금지** 
* 람다는 사용 가능
* else 예약어 사용 금지
* switch/case도 금지
* 함수(또는메소드)의 길이가 10라인을 넘어가지 않도록 구현
* 함수(또는메소드)가 한가지 일만 잘 하도록 구현


## 프로그래밍 요구사항 - 단위 테스트
* 로직에 단위테스트를 구현, UI(System.out,System.in,Scanner)로직은제외
* 핵심 로직을 구현하는 코드와 UI를 담당하는 로직을 구분한다.
* JUnit5 기반 단위 테스트를 구현한다.
