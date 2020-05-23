# codingTestForKakaoPaySec
my source for coding test for KakaopaySec.

/* 
Subject: 카카오페이증권 코딩테스트 관련 정리
Author: 안재형
Date: 2020-05-23
*/

1. 개발 환경
 1) 개발 툴: Eclipse IDE for Java Developers (JAVA 8)
    Version: 2020-03 (4.15.0)

 2) 프레임워크: Spring Boot Framework
     Version: 2.3.0
     * 기타 dependency와 함께 pom.xml 에서 확인 가능.

 3) In Memory DB: H2

2. 주요 문제시 해결방법
HttpRequestMethodNotSupportedException 발생: 개발된 Method는 모두 GET 방식 호출을 기반으로 하니 이에 맞추어 테스트를 진행.

3. 빌드 및 실행
 1) 프로젝트 선택 - Run As - Spring Boot App 순서로 로컬환경에서 실행.
 2) API 호출 테스트: Postman을 PC에 설치 후 테스트 가능.
    > 설치 후 로그인(구글 계정 사용 가능).
    > 호출방식 GET 선택.
    > URL 란에 호출 URL 입력(URL은 "단위테스트_카카오페이증권" Excel 파일 참고).
    > 파라미터 입력이 필요한 케이스는 'Params' 섹션에 key&value 입력.
    > 'Send' 클릭하여 API호출 후 결과 확인.
