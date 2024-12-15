# TIL
Today I Learned - 그날 공부한 내용 정리

## 2024-12-15
### 주제: 리눅스
####  디렉토리 다루기, 파일 다루기, 파일 입출력 연습 문제 풀이

## 2024-12-11
### 주제: 응용소프트웨어공학
####  아키텍처 설계와 패턴, 클래스다이어그램, 코드, 테스트 공부, 유지보수(버전 관리 부분)공부와 복습

## 2024-12-10
### 주제: 자바
#### 스윙 콤포넌트, 이벤트 처리, 스레드, 멀티태스킹, 네트워크, JDBC 복습

## 2024-12-09
### 주제: 응용소프트웨어공학
####  태스트, 테스트 케이스, 테스트 종류 공부

## 2024-12-08
### 주제: 자바
####  스레드, 멀티태스킹 공부

## 2024-12-07
### 주제: 자바
####  자바의 이벤트 처리, 스윙 컴포넌트, 그래픽복습

## 2024-12-06
### 주제: 응용소프트웨어공학
#### 아키텍처 스타일, 좋은 코딩 스타일을 유지하기 위한 방법,리펙토링 복습

## 2024-12-04
### 주제: 리눅스
#### 프로세스 생성과 실행

## 2024-12-03
### 주제: 응용소프트웨어공학 공부
#### 아키텍처 스타일
#### 좋은 코딩 스타일을 유지하기 위한 방법
#### 리펙토링

## 2024-12-02
### 주제: 프로젝트
#### 앱 jetpack-compose-camera 구현중

## 2024-12-01
### 주제: 코딩테스트
####  2566 주어진 9x9 행렬에서 최댓값과 그 위치를 찾기
- 문제 설명
  - 입력: 9x9 행렬의 각 원소, 각 원소는 0 이상 100 이하의 정수
  - 출력: 행렬에서 최댓값과 그 위치(행과 열의 인덱스)를 출력. 위치는 1부터 시작
- 접근 방법
  - 9x9 행렬을 입력받아 저장
  - 행렬을 순회하여 최댓값을 갱신하고, 최댓값이 위치한 인덱스를 기록
  - 최댓값과 그 위치를 출력

## 2024-11-30
### 주제: 자바 공부
#### 자바의 이벤트 처리, 스윙 컴포넌트, 그래픽

## 2024-11-28
### 주제: 자바 공부
####  스트림, 파일 입출력
- FileWriter
- FileOutputStream
- FileIntputStream
- BufferedOutputStream
- File
#### GUI, AWT, Swing(1)
- AWT  vs 스윙
- 스윙 프레임
- 컨테이너와 배치관리자
  - FlowLayout
  - BorderLayout
  - GridLayout
  - CardLayout

## 2024-11-27
### 주제: UML 클래스 다이어 그램 작성하고 이거로부터 코드 생성하기(순공학 기능 이용)


## 2024-11-26
### 주제: 코딩테스트
####  소인수분해
- 문제 설명
  - 입력: 하나의 정수 ( N )
  - 출력: ( N )의 소인수를 오름차순으로 출력
- 접근 방법
  - 2부터 ( \sqrt{N} )까지의 수로 ( N )을 나눠가며 소인수
  - 해당 수로 나누어 떨어질 때마다 ( N )을 그 수로 나누고, 그 수를 출력
  - 마지막에 남은 수가 1이 아니면 그 수 자체가 소수이므로 출력
    
## 2024-11-25
### 주제: Python과 OpenCV를 사용하여 RTSP 캠의 실시간 스트리밍에서 지연 문제를 해결하기 위한 프로젝트
####  `FreshestFrame` 클래스는 항상 최신 프레임을 유지하여 지연을 최소화합니다.
- 주요 기능
  - 최신 프레임 유지
    - 스레드를 사용하여 카메라로부터 최신 프레임만을 유지하고, 오래된 프레임은 버림
  - 스레드 기반 설계
    - 별도의 스레드에서 프레임을 읽어 메인 스레드에서 블로킹 없이 최신 프레임을 사용
  - 조건 변수 사용
    - `Condition` 객체를 사용하여 프레임 갱신 시 대기 중인 스레드에 알림을 전달
  - 프레임 소비 제어
    - `read` 메서드를 통해 다양한 모드로 프레임을 소비할 수 있도록 설계

## 2024-11-24
### 주제: 자기소개서 초안 작성
####  직무 관련 경험
  - 도서관 DB
  - AI를 이용한 유실물 방지 시스템

## 2024-11-23
### 주제: 리눅스 과제
#### 파일 입출력 : 고수준 파일 입출력 및 임시 파일 사용 예제
- 구현 방법
  - 문자 기반 입출력
    - 함수: fgetc(), fputc()
    - 목적: 파일에서 문자 단위로 읽기 및 쓰기
  - 문자열 기반 입출력
    - 함수: fgets(), fputs()
    - 목적: 파일에서 문자열 단위로 읽기 및 쓰기
  - 바이너리 데이터 입출력
    - 함수: fread(), fwrite()
    - 목적: 파일에서 바이너리 데이터 읽기 및 쓰기
  - 형식화된 입출력
    - 함수: fscanf(), fprintf()
    - 목적: 파일에서 형식화된 데이터 읽기 및 쓰기
  - 파일 오프셋 조정
    - 함수: fseek(), ftell()
    - 목적: 파일의 특정 위치로 이동 및 위치 확인


## 2024-11-22
### 주제: 프로젝트
#### CCTV에서 영상을 가져와 AI를 이용한 객체 인식 후 유실물 감지 프로젝트 동영상 촬영

## 2024-11-21
### 주제: 프로젝트
#### 문제: 젯슨 나노의 SD 카드 용량 부족
- 목표
  - SD 카드를 초기화하고, Python, CUDA, PyTorch, pip 등 필요한 환경을 재설정

## 2024-11-20
### 주제: 코딩 테스트 문제 풀이
#### 9095 1, 2, 3 더하기
- 문제 설명
  - 입력
    - 첫 번째 줄에 테스트 케이스의 수 ( t )
    - 각 테스트 케이스마다 정수 ( n )
  - 출력
    - 각 테스트 케이스에 대해 ( n )을 1, 2, 3의 합으로 나타내는 방법 출력
- 접근 방법
  - 점화식
    - 점화식: ( dp[n] = dp[n-1] + dp[n-2] + dp[n-3] )
    - ( dp[1] ), ( dp[2] ), ( dp[3] )는 각각 1, 2, 4로 초기화

    
## 2024-11-19
### 주제: 프로젝트 
#### Yolo, CLAHE, SAHI 코드 연결

## 2024-11-18
### 주제: 프로젝트 
#### clahe clipLimit.py 코드 함수로 나누어서 최적화 해놨음

## 2024-11-17
### 주제: 프로젝트
#### 계산기, 가위바위보, 구구단 코드 작성

## 2024-11-16
### 주제: 프로젝트
#### 이미지의 평균 조도를 기준으로 CLAHE를 적용하여 이미지의 대비를 적절히 조정
- 구현 방법
  - 어두운 이미지 (평균 조도 100 이하)
    - clipLimit 값을 2.5 사이로 설정
    - 목적: 어두운 이미지의 세부 사항을 강조하여 더 잘 드러냄
  - 밝은 이미지 (평균 조도 100 이상)
    - clipLimit 값을 1.5 설정
    - 목적: 과도한 대비 조정을 피하여 이미 충분한 조도와 명암비를 가진 이미지를 과도하게 조정하지 않음
    
## 2024-11-15
### 주제: 코딩 테스트 문제 풀이
#### 1065 한수
- 문제 설명
  - 입력
    - 자연수 ( N )
  - 출력
    - 1부터 ( N )까지의 수 중 한수(각 자리의 숫자가 등차수열을 이루는 수)의 개수를 출력
    - 1부터 99까지의 모든 수는 한수
- 접근 방법
  - 1부터 99까지는 모든 수가 한수이므로 100 미만은 그대로 리턴
  - 100부터 ( N )까지 각 수에 대해 자릿수를 분리
  - 각 자리의 차이가 일정한지 확인하여 한수인지 판별

## 2024-11-14
### 주제: 코딩 테스트 문제 풀이
#### 1316 그룹 단어 체커
- 문제 설명
  - 입력
    - 첫 번째 줄에 단어의 개수 ( N )
    - 다음 ( N )개의 줄에 각각 단어가 주어짐
  - 출력
    - 그룹 단어의 개수를 출력
- 접근 방법
  - 각 단어에 대해 문자가 연속해서 나타나는지 확인
  - 이미 등장한 문자가 다시 등장하는 경우 그룹 단어가 아님
  - 그룹 단어인 경우에만 카운트를 유지

## 2024-11-13
### 주제: 코딩 테스트 문제 풀이
#### 2941 크로아티아 알파벳
- 문제 설명
  - 입력
    - 크로아티아 알파벳으로 구성된 문자열
    - 각 문자열은 소문자
  - 출력
    - 크로아티아 알파벳을 단일 문자로 간주하여 전체 문자의 개수를 출력
- 접근 방법
  - 문자열을 순회하면서 크로아티아 알파벳 패턴 찾기
  - 발견한 패턴에 따라 인덱스를 조정하여 다음 문자를 건너뛰고, 카운트를 증가
   
## 2024-11-11
### 주제: 코딩 테스트 문제 풀이
#### 2501 약수 구하기
- 문제 설명
  - 입력
    - 첫 번째 줄에 두 개의 자연수 ( N )과 ( K )
  - 출력
    - ( N )의 약수 중 ( K )번째로 작은 수를 출력
    - 만약 약수의 개수가 ( K )보다 적다면 0을 출력
- 접근 방법
  - 1부터 ( N )까지의 수를 순회하며, ( N )을 나누어 떨어뜨리는 수를 찾아 약수로 판단
  - 약수를 찾을 때마다 카운트를 증가
  - 카운트가 ( K )에 도달하면 해당 약수를 출력

## 2024-11-10
### 주제: 코딩 테스트 문제 풀이
#### 1157 단어 공부
- 문제 설명
  - 입력
    - 단어가 주어집니다. 이 단어는 대소문자로 구성
  - 출력
    - 가장 많이 사용된 알파벳을 대문자로 출력
    - 만약 가장 많이 사용된 알파벳이 여러 개라면 '?'를 출력
- 접근 방법
  - 대소문자를 구별하지 않으므로 입력받은 모든 문자를 대문자 또는 소문자로 통일하여 처리
  - 알파벳의 개수는 26개이므로, 크기가 26인 배열을 사용하여 각 알파벳의 빈도수를 저장
  - 배열을 순회하여 가장 큰 빈도수를 찾고, 해당 알파벳을 기록

## 2024-11-09
### 주제: 코딩 테스트 문제 풀이
#### 1978 소수 찾기
- 문제 설명
  - 입력
    - 첫 번째 줄에 숫자의 개수 ( N )
    - 다음 줄에 ( N )개의 숫자
  - 출력
    - 주어진 숫자들 중 소수의 개수를 출력
- 접근 방법
  - 각 숫자에 대해 소수인지 판단
  - 소수는 1과 자신을 제외한 다른 수로 나누어 떨어지지 않는 수
  - 2부터 해당 숫자의 제곱근까지의 수로 나누어 보면서 나누어 떨어지는지 확인

## 2024-11-08
### 주제: 코딩 테스트 문제 풀이
#### 2750 수 정렬하기
- 문제 설명
  - 입력
    - 첫 번째 줄에 테스트 케이스의 수 ( T )
    - 각 테스트 케이스마다 정수 ( N )
  - 출력
    - 각 테스트 케이스마다 피보나치 수열을 계산할 때 0과 1이 각각 몇 번 호출되는지를 출력
- 접근 방법
  - 피보나치 수열의 특성을 활용하여, ( N )일 때 0과 1이 호출되는 횟수를 미리 계산하여 저장
  - 재귀 호출을 통해 이미 계산된 결과를 재사용하여 효율적으로 문제를 해결

## 2024-11-07
### 주제: 코딩 테스트 문제 풀이
#### 2750 수 정렬하기
- 문제 설명
  - 입력
    - 정수 ( N )이 주어지고, 그 다음 ( N )개의 정수
  - 출력
    - 주어진 수를 오름차순으로 정렬한 결과를 출력
- 접근 방법
  - 배열을 순회하면서 가장 작은 요소를 찾아 현재 위치에 있는 요소와 교환하는 방식으로 정렬

## 2024-11-06
### 주제: 코딩 테스트 문제 풀이
#### 2444 별 찍기 - 7
- 문제 설명
  - 입력
    - 정수 ( N )
  - 출력
    - 높이가 ( 2N-1 )인 다이아몬드 형태의 별을 출력
- 접근 방법
  - 상단 삼각형 출력
    - 1부터 ( N )까지 증가하는 별의 개수를 출력
    - 각 줄마다 공백을 출력하여 별의 위치를 조정
  - 하단 삼각형 출력
    - ( N-1 )부터 1까지 감소하는 별의 개수를 출력
    - 각 줄마다 공백을 출력하여 별의 위치를 조정

## 2024-11-05
### 주제: 코딩 테스트 문제 풀이
#### 5622 다이얼
- 문제 설명
  - 입력
    - 단어가 주어집니다. 각 문자들은 대문자
  - 출력
    - 해당 단어를 전화기 다이얼을 이용해 걸기 위해 걸리는 시간을 출력
- 다이얼 규칙
  - 각 문자에 대해 다이얼 번호에 따라 걸리는 시간이 다름
  - 'A', 'B', 'C'는 3초, 'D', 'E', 'F'는 4초 등으로 할당
- 접근 방법
  - 입력받은 문자열을 하나씩 처리하며 각 문자의 다이얼 시간을 계산
  - 각 문자에 대해 switch 문을 사용하여 해당하는 시간을 누적

## 2024-11-04
### 주제: 코딩 테스트 문제 풀이
#### 1546 평균
- 문제 설명
  - 입력
    - 두 개의 세 자리 수가 주어집니다. 각 숫자는 공백으로 구분
  - 출력
    - 두 수를 거꾸로 읽어서 더 큰 수를 출력
- 접근 방법
  - 숫자 역순 읽기
  - 입력 처리
    - System.in.read()를 사용하여 문자를 하나씩 읽기
    - 각 자리의 숫자를 역순으로 조합하여 수를 만듦
  - 수 비교 및 출력
    - 두 수 중 더 큰 수를 삼항 연산자를 사용하여 출력

## 2024-11-03
### 주제: 코딩 테스트 문제 풀이
#### 1546 평균
- 문제 설명
  - 입력
    - 첫 번째 줄에 시험 본 과목의 개수 ( n )이 주어짐
    - 두 번째 줄에 각 과목의 시험 점수가 주어짐
  - 출력
    - 점수를 조작한 새로운 평균을 출력
- 조작 방법
  - 각 점수를 모든 점수 중 최댓값으로 나눈 후 100을 곱하여 새로운 점수를 계산
  - 새로운 점수들의 평균을 계산하여 출력
- 접근 방법
  - 점수 배열을 입력받고 저장
  - 배열을 정렬하여 최댓값 찾기
  - 각 점수를 최댓값으로 나누고 100을 곱하여 조작된 점수를 합산
  - 합산된 점수를 과목 수로 나누어 평균을 출력

## 2024-11-02
### 주제: 코딩 테스트 문제 풀이
#### 10811 바구니 뒤집기
- 문제 설명
  - 입력
    - 정수 ( n ): 바구니의 수
    - 정수 ( count ): 뒤집기 작업의 횟수
    - 뒤집기 정보: 각 작업마다 두 개의 정수 ( a, b )가 주어짐. 이는 ( a )번 바구니부터 ( b )번
      바구니까지의 순서를 역순으로 뒤집음
  - 출력
    - 배열 상태: 모든 뒤집기 작업이 끝난 후 각 바구니에 들어 있는 공의 번호를 공백으로 구분하여 출력
- 접근 방법
  - 배열 초기화: 크기가 ( N )인 배열을 생성하고, 각 인덱스에 해당하는 초기 값을 설정
  - 뒤집기 작업 반복: ( count )번의 뒤집기 작업에 대해 지정된 구간의 배열 값을 역순으로 교환
  - 결과 출력: 최종 배열 상태를 출력

## 2024-11-01
### 주제: 코딩 테스트 문제 풀이
#### 10813 공 바꾸기
- 문제 설명
  - 입력
    - 정수 ( N ): 바구니의 수
    - 정수 ( M ): 공을 교환할 횟수
    - 교환 정보: 각 교환 작업마다 두 개의 정수 ( n1, n2 )가 주어짐. 이는 ( n1 )번째 바구니와 ( n2 )번째 바구니의 공을 교환함을 의미
  - 출력
    - 배열 상태: 모든 교환 작업이 끝난 후 각 바구니에 들어 있는 공의 번호를 공백으로 구분하여 출력
- 접근 방법
  - 배열 초기화: 크기가 ( N )인 배열을 생성하고, 각 인덱스에 해당하는 초기 값을 설정
  - 교환 작업 반복: ( M )번의 교환 작업에 대해 지정된 인덱스의 배열 값을 서로 교환
  - 결과 출력: 최종 배열 상태를 출력

## 2024-10-31
### 프로젝트: 이미지 설명 생성
- 프로젝트 설명
  - Google Generative AI와 Python을 활용하여 이미지에 대한 설명을 생성하고 출력하는 프로젝트
- 구현 방법
  - API 키 설정을 통한 Google Generative AI 접근
  - GenerativeModel을 사용한 모델 생성
  - pathlib을 사용한 이미지 파일 로드
  - 텍스트 프롬프트 설정
  - 모델 요청을 통한 컨텐츠 생성
  - 텍스트 설명 출력

### 주제: 코딩 테스트 문제 풀이
#### 10810 공 넣기
- 문제 설명
  - 입력
    - 정수 ( N ): 바구니의 개수
    - 정수 ( M ): 공을 넣는 작업의 횟수
    - 작업 정보: 각 작업마다 세 개의 정수 ( I, J, K )가 주어짐
      - ( I )번 바구니부터 ( J )번 바구니까지 공 번호 ( K )를 넣음
  - 출력
    - 배열 상태: 모든 작업이 끝난 후 각 바구니에 들어 있는 공의 번호를 공백으로 구분하여 출력
- 접근 방법
  - 배열 사용: 크기가 ( N )인 배열을 생성하여 각 바구니에 들어 있는 공의 번호를 저장
  - 작업 반복: 각 작업에 대해 주어진 범위에 해당하는 배열 요소를 업데이트
  - 결과 출력: 최종 배열 상태를 출력

## 2024-10-30
### 주제: 코딩 테스트 문제 풀이
#### 11022 A+B - 8
- 문제 설명
  - 입력
    - 테스트 케이스 수 ( T ): 첫 번째 줄에 주어짐
    - 두 정수 ( A )와 ( B ): 각 테스트 케이스마다 주어짐
  - 출력
    - 결과 형식: "Case #x: A + B = C" 형식으로 출력 (x는 테스트 케이스 번호, C는 ( A + B )의 결과)
- 접근 방법
  - 반복문 사용: ( T )번 반복하여 각 테스트 케이스에 대해 두 정수를 입력받고, 형식에 맞춰 결과를 출력
  - 출력 형식 설정: 각 테스트 케이스 번호와 더한 결과를 포함하는 문자열을 출력
 
## 2024-10-29
### 주제: 코딩 테스트 문제 풀이
#### 25314 코딩은 체육과목 입니다
- 문제 설명
  - 입력
    - 정수 ( n ): 자연수 ( n ) (4의 배수)
  - 출력
    - 문자열: "long"이 ( n/4 )번 반복된 후 "int"를 덧붙인 문자열
- 접근 방법
  - 반복문 사용: ( n/4 )번 "long "을 문자열에 추가
  - 출력: 반복된 "long" 문자열에 "int"를 덧붙여 출력
 
## 2024-10-28
### 주제: 코딩 테스트 문제 풀이
#### 25304 영수증
- 문제 설명
  - 입력
    - 총 금액: 영수증에 적힌 총 금액 ( X )
    - 물건 종류 수: ( N )
    - 물건 정보: 각 물건의 가격 ( a )와 개수 ( b )
  - 출력
    - 결과: 계산된 총 금액과 영수증의 총 금액 비교 결과 "Yes" 또는 "No"
- 접근 방법
  - 총합 계산: 각 물건의 가격과 개수를 곱한 값을 누적하여 계산
  - 비교: 누적된 총합과 영수증의 총 금액 비교
  - 결과 출력: 비교 결과에 따라 "Yes" 또는 "No" 출력

## 2024-10-27
### 프로젝트: 이미지 객체 감지 및 시각화
- 프로젝트 설명
  - OpenCV와 YOLO를 활용하여 이미지에서 객체를 감지하고, 결과를 시각적으로 표시한 후 HTML 파일로 저장하는 프로젝트
- 구현 방법
  - OpenCV로 이미지 처리 및 시각화를 수행
  - YOLO를 통해 이미지에서 객체를 감지
  - 각 객체에 고유한 색상의 경계 상자를 그려 표시
  - 클래스 이름과 신뢰도를 이미지에 표시
  - 전처리 여부에 따라 원본 또는 변환된 이미지를 사용하고 이를 HTML에 기록
  - 결과 이미지를 저장하고 감지된 객체 정보를 HTML 파일로 생성해 웹에서 확인 가능

## 2024-10-26
### 주제: 코딩 테스트 문제 풀이
#### 2920 음계
- 문제 설명:
  - 입력
    - 8개의 정수가 주어지며, 각 정수는 1부터 8까지의 숫자를 포함
  - 출력
    - 주어진 숫자 배열이 오름차순이면 "ascending", 내림차순이면 "descending", 그 외의 경우는 "mixed"를 출력
- 접근 방법
  - 주어진 숫자 배열을 순회하면서 인접한 두 수를 비교
  - 첫 번째 숫자가 두 번째 숫자보다 1 작으면 오름차순, 1 크면 내림차순
  - 처음부터 끝까지 모든 숫자가 오름차순 혹은 내림차순 조건을 만족하면 해당 문자열을 출력
  - 중간에 해당 조건을 만족하지 않는 경우가 나오면 "mixed"를 출력하고 루프를 종료

## 2024-10-25
### 주제: 코딩 테스트 문제 풀이
#### 18018 불기 연도 변환
- 문제 설명:
  - 입력
    - 태국의 불기 연도가 주어짐. 불기 연도는 1000 이상 3000 이하의 정수
  - 출력
    - 입력된 불기 연도를 서기 연도로 변환하여 출력
- 접근 방법
  - 태국의 불기 연도는 서기 연도보다 543년이 더 많다
  - 따라서, 불기 연도에서 543을 빼면 서기 연도가 된다.

## 2024-10-24
### 주제: 학교 중간고사 시험 및 준비
  - 응용소프트웨어공학 시험 

### 주제: 코딩 테스트 문제 풀이
#### 2577 숫자의 개수
- 문제 설명:
  - 입력
    - 세 개의 자연수가 차례로 주어짐. 각 수는 100보다 크거나 같고, 1,000보다 작은 자연수
  - 출력
    - 세 수를 곱한 결과에서 0부터 9까지의 숫자가 각각 몇 번씩 쓰였는지를 출력
- 접근 방법
  - 세 수를 입력받아 곱한 결과를 저장
  - 결과값의 각 자리 숫자를 확인하여, 그 숫자가 몇 번 나왔는지를 카운트
  - 0부터 9까지의 숫자에 대한 카운트를 배열에 저장하고, 이를 출력

## 2024-10-23
### 주제: 학교 중간고사 시험 및 준비
  - 시스템 프로그래밍 시험
  - 고급 자바프로그래밍 시험
  - 응용소프트웨어 공학 시험 준비

### 주제: 코딩 테스트 문제 풀이
#### 10926 ??!
- 문제 설명:
  - 입력
    - 사용자로부터 하나의 문자열 ( s )를 입력
  - 출력
    - 입력된 아이디 뒤에 "??!"를 붙여 출력
- 접근 방법
  - 사용자로부터 입력된 문자열을 읽어옴
  - 입력된 문자열에 "??!"를 붙여서 출력

## 2024-10-22
### 주제: 코딩 테스트 문제 풀이
#### 3052 나머지
- 문제 설명:
  - 입력
    - 총 10개의 정수가 입력
  - 출력
    - 입력된 정수를 42로 나눈 나머지의 서로 다른 값의 개수를 출력
- 접근 방법
  - HashSet 사용
    - HashSet은 중복을 허용하지 않는 특성이 있으므로, 각 숫자를 42로 나눈 나머지를 HashSet에 저장하면 서로 다른 나머지 값만 저장
  - 10개의 숫자를 입력받아 각각 42로 나눈 나머지를 HashSet에 추가
  - HashSet의 크기를 출력하면 서로 다른 나머지 값의 개수

## 2024-10-21
### 주제: 코딩 테스트 문제 풀이
#### 8958 OX퀴즈
- 문제 설명:
  - 입력
    - 첫 번째 줄에 테스트 케이스의 수 ( n )
  - 출력
    - 다음 각 줄에는 O와 X로 이루어진 문자열,  문자열의 길이는 80 미만
- 접근 방법
  - 각 테스트 케이스에 대해 문자열을 순회하면서 점수를 계산
  - 점수 계산
    - 'O'가 연속되면 점수를 증가, 연속된 'O'의 수가 많을수록 점수가 더 많이 증가
    - 'X'를 만나면 연속 점수를 리셋
  -문자열에 대해 총점을 계산하여 출력

## 2024-10-20
### 주제: 코딩 테스트 문제 풀이
#### 1152 단어의 개수
- 문제 설명:
  - 입력
    - 한 줄에 영어 대소문자와 공백으로 이루어진 문자열이 주어집니다. 문자열의 길이는 1,000,000 이하
  - 출력
    - 입력된 문자열에서 단어의 개수를 출력합니다. 단어는 공백으로 구분
- 접근 방법
  - StringTokenizer 사용
    - 입력된 문자열을 StringTokenizer를 사용하여 공백을 기준으로 분리합
    - StringTokenizer는 주어진 구분자(여기서는 공백)를 기준으로 문자열을 분리하여 각각의 토큰을 저장
  - 토큰의 개수 세기
    - StringTokenizer의 countTokens() 메서드를 사용하여 분리된 단어의 개수를 구합니다.
   
## 2024-10-19
### 주제: 코딩 테스트 문제 풀이
#### 9375 패션왕 신해빈
- 문제 설명:
  - 입력
    - 첫 번째 줄에 테스트 케이스의 수 ( t )
    - 각 테스트 케이스의 첫 번째 줄에는 의상의 수 ( n )
    - 다음 ( n )개의 줄에는 각 의상의 이름과 종류가 주어짐
  - 출력
    - 각 테스트 케이스마다, 서로 다른 의상 조합의 수를 출력합니다. 단, 아무것도 입지 않는 경우는 제외
- 접근 방법
  - HashMap을 사용하여 의상 종류별로 카운트
    - 각 테스트 케이스마다 의상 종류를 키로 하고 해당 종류의 의상 수를 값으로 하는 맵을 생성
  - 경우의 수 계산
    - 각 의상 종류에 대해, 해당 종류의 의상을 입거나 입지 않는 경우를 포함하여 경우의 수를 계산
    - 이를 위해 모든 의상 종류의 경우의 수를 곱
  - 결과 조정
    - 아무것도 입지 않는 경우를 제외하기 위해 최종 결과에서 -1
     
## 2024-10-18
### 주제: 코딩 테스트 문제 풀이
#### 1620 나는야 포켓몬 마스터 이다솜
- 문제 설명:
  - 입력
    - 첫 번째 줄에 두 개의 정수  ( n )은 포켓몬의 수, ( m )은 맞춰야 하는 문제의 수
    - 다음 ( n )개의 줄에는 각각 하나의 포켓몬 이름이 주어지며, 이는 1번부터 ( n )번까지의 번호가 부여
    - 이후 ( m )개의 줄에 문제로 주어지며, 포켓몬의 이름 또는 번호를 줌
  - 출력
    - 각 문제에 대해, 번호가 주어지면 해당 번호의 포켓몬 이름을 출력하고, 이름이 주어지면 해당 포켓몬의 번호를 출력
- 접근 방법
  - 두 개의 HashMap을 사용하여 이름과 번호를 서로 매핑
    - mp: 이름을 키로 하고 번호를 값으로 하는 맵
    - mp2: 번호를 키로 하고 이름을 값으로 하는 맵
  - 입력된 이름과 번호를 HashMap에 저장하여 빠른 검색을 가능
  - 각 문제에 대해 문자열을 입력받아 숫자인지 판단
    - 숫자라면 해당 번호의 포켓몬 이름을 출력
    - 문자열이라면 해당 이름의 포켓몬 번호를 출력

### 프로젝트: 이미지 객체 감지 및 시각화
- 프로젝트 설명
  - YOLO와 OpenCV를 활용하여 이미지에서 객체를 감지하고, 이를 이미지 위에 시각적으로 표시한 후, 결과를 HTML 파일로 저장하는 프로젝트
- 구현 방법
  - 이미지 처리 및 객체 탐지
    - OpenCV를 사용하여 이미지를 불러오고 전처리
    - YOLO 모델을 통해 이미지에서 객체를 탐지
  - 시각화
    - 감지된 객체의 라벨에 따라 고유한 색상을 지정하여 경계 상자를 그립니다.
  - 결과 저장
    - 시각화된 이미지를 파일로 저장
    - 감지된 객체 정보를 포함한 HTML 파일을 생성하여 웹 브라우저에서 결과를 확인 가능

## 2024-10-17
### 주제: 코딩 테스트 문제 풀이
#### 2559 수열
- 문제 설명:
  - 입력
    - 첫 번째 줄에 두 개의 정수 ( n )과 ( k )가 주어집니다. 여기서 ( n )은 수열의 길이이며, ( k )는 연속 부분 수열의 길이
    - 두 번째 줄에는 ( n )개의 정수로 이루어진 수열
  - 출력
    - 길이가 ( k )인 연속 부분 수열의 합 중 최대값을 출력
- 접근 방법
  - 누적 합 배열 사용
    - 배열 psum을 사용하여 각 인덱스까지의 누적 합을 저장합니다. 즉, psum[i]는 1번부터 i번까지의 수열의 합
  - 최대 합 계산
    - 각 가능한 ( k ) 길이의 구간에 대해 합을 계산합니다. 이를 위해, ( i )를 ( k )부터 ( n )까지 반복하면서, 각 구간의 합을 psum[i] - psum[i-k]로 계산
    - 각 구간의 합을 계산할 때마다 현재까지의 최대 합과 비교하여 갱신
  - 최대 합을 출력

## 2024-10-16
### 주제: 코딩 테스트 문제 풀이
#### 9996 한국이 그리울 땐 서버에 접속하지
- 문제 설명: 주어진 패턴과 여러 문자열들을 비교하여 패턴과 일치하는지 확인하는 문제입니다. 패턴에는 '' 문자가 포함되어 있으며, ''는 임의의 문자열을 대체할 수 있습니다
- 접근 방법
  - 첫 번째로, 테스트할 문자열의 수 (n)을 입력받습니다.
  - 두 번째로, 패턴 문자열을 입력받고 ''의 위치를 찾아 '' 이전 부분과 이후 부분으로 문자열을 분리합니다.
  - 각 테스트 문자열에 대해 다음을 수행합니다:
    - 패턴의 앞부분과 뒷부분의 길이 합이 테스트 문자열의 길이보다 크면 "NE"를 출력합니다.
    - 그렇지 않으면, 테스트 문자열의 시작 부분과 끝 부분을 패턴의 앞부분과 뒷부분과 각각 비교합니다.
    - 시작 부분과 끝 부분이 각각 패턴의 앞부분과 뒷부분과 같으면 "DA"를 출력하고, 그렇지 않으면 "NE"를 출력합니다.
      
#### 11655 ROT13
- 문제 설명: 입력된 문자열에 ROT13 암호화를 적용하는 문제
  - ROT13: 알파벳을 13글자씩 밀어서 변환하는 간단한 암호화 기법
  - 대문자와 소문자는 각각 알파벳 범위 내에서 순환하며 변환
  - 알파벳이 아닌 문자는 변경하지 않음
- 접근 방법
  - 문자열을 입력받음
  - 문자열의 각 문자를 순회하며 대문자, 소문자에 대해 ROT13 변환 적용
  - 대문자(A-Z): 'A'에서 'Z' 사이의 글자에 대해 13을 더한 후, 26을 초과하면 순환
  - 소문자(a-z): 'a'에서 'z' 사이의 글자에 대해 13을 더한 후, 26을 초과하면 순환
  - 알파벳이 아닌 문자는 그대로 유지
  - 변환된 문자 배열을 출력하여 결과 문자열을 생성

## 2024-10-15
### 주제: 코딩 테스트 문제 풀이
#### 1159 농구 경기
- 문제 설명: 농구 팀의 선수들의 성이 주어졌을 때, 성의 첫 글자가 같은 선수가 5명 이상인 경우 해당 글자를 출력하는 문제.
              그런 글자가 없으면 "PREDAJA"를 출력
- 접근 방법
  - 선수의 수 (n)을 입력받음
  - 각 선수의 이름을 입력받아 첫 글자의 빈도 수를 기록할 배열 생성 (크기 26, 알파벳 소문자 수)
  - 각 선수의 이름의 첫 글자를 사용하여 해당 인덱스의 빈도를 증가시킴
  - 배열을 순회하여 빈도 수가 5 이상인 알파벳을 출력
  - 빈도 수가 5 이상인 알파벳이 없으면 "PREDAJA" 출력

## 2024-10-14
### 주제: 코딩 테스트 문제 풀이
#### 10808 알파벳 개수
- 문제 설명: 입력된 문자열에서 각 알파벳(a-z)의 개수를 구하여 빈도 수를 출력하는 문제
- 접근 방법
  - 문자열을 입력받음
  - 소문자 알파벳 a-z의 빈도 수를 저장할 정수 배열을 생성 (크기 26)
  - 문자열의 각 문자를 순회하며 해당 문자의 아스키 값을 이용해 배열의 인덱스를 계산하고 빈도 수를 증가시킴
    - 예를 들어, 'a'의 아스키 값은 97이므로, 'a'는 배열의 인덱스 0에 해당 (c - 97)
  - 배열을 순회하며 각 알파벳의 빈도 수를 출력

#### 2979 트럭 주차
- 문제 설명: 세 대의 트럭이 주차장에 주차된 시간에 따라 주차 요금을 계산하는 문제
  - 주차 요금은 트럭의 대수에 따라 다르게 부과됨
  - 한 대일 때 요금: a 원, 두 대일 때 요금: b 원, 세 대일 때 요금: c 원
- 접근 방법
  - 요금 정보를 입력받음: a, b, c
  - 각 트럭의 주차 시작 시간과 종료 시간을 입력받음
  - 시간대를 나타내는 배열을 생성하여 1분 단위로 해당 시간에 주차된 트럭의 수를 기록
  - 각 분에 대해 주차된 트럭 수에 따라 요금을 누적하여 총 요금을 계산

#### 10988 팰린드롬인지 확인하기
- 문제 설명:  입력된 문자열이 팰린드롬인지 확인하는 문제
  - 팰린드롬: 앞에서 읽으나 뒤에서 읽으나 같은 문자열
- 접근 방법
  - 문자열을 입력받음
  - 입력된 문자열을 뒤집은 문자열과 비교
  - 비교 결과가 동일하면 팰린드롬이므로 1을 출력, 그렇지 않으면 0을 출력
    

## 2024-10-13
### 주제: 코딩 테스트 문제 풀이
#### 31403 입출력
- 문제 설명: 세 개의 정수 입력을 받아 특정 연산을 수행하여 결과를 출력하는 문제
- 접근 방법
  - 세 개의 정수 (a), (b), (c)를 입력받음
  - 첫 번째 연산: (a)와 (b)를 더한 후 (c)를 뺀 결과를 출력
  - 두 번째 연산: (a)와 (b)를 문자열로 이어 붙인 후 정수로 변환하여 (c)를 뺀 결과를 출력

## 2024-10-12
### 주제: 코딩 테스트 문제 풀이
#### 2439 별 찍기 - 2
- 문제 설명: 주어진 정수 N에 대해, N줄에 걸쳐 오른쪽 정렬된 형태로 별을 출력하는 문제
- 접근 방법
  - 정수 N을 입력받음
  - 1부터 N까지의 각 줄에 대해 반복
  - 각 줄에 대해 (N-현재 줄 번호) 만큼 공백을 출력하고, 현재 줄 번호만큼 별을 출력
  - 각 줄의 결과를 출력

### 주제: 자바 개념 복습
- 생성자, 오버로딩, 가비지, 패키지, static, final,
- 상속, 캐스팅, 오버라이딩, abstract, 인터페이스
- Object 클래스, Wrapper 클래스, String

## 2024-10-11
### 주제: 코딩 테스트 문제 풀이
#### 11720 숫자의 합
- 문제 설명: 주어진 숫자들을 모두 더한 합을 출력하는 문제
- 접근 방법
  - 숫자의 개수 N을 입력받음
  - N개의 숫자로 이루어진 문자열을 입력받음
  - 문자열의 각 문자를 정수로 변환하여 합을 계산
  - 계산된 합을 출력

## 2024-10-10
### 주제: 코딩 테스트 문제 풀이
#### 10818 최솟값과 최댓값 찾기
- 문제 설명: 주어진 수열에서 최솟값과 최댓값을 찾아 출력하는 문제
- 접근 방법
  - 수열의 크기 N을 입력 받음
  - N개의 정수를 입력 받아 리스트에 저장
  - 리스트를 정렬하여 첫 번째와 마지막 원소를 각각 최솟값과 최댓값으로 찾음
  - 최솟값과 최댓값을 공백으로 구분하여 출력

## 2024-10-09
### 주제: 코딩 테스트 문제 풀이
#### 2675 문자열 반복 (반복문)
- 문제 설명: 주어진 문자열의 각 문자를 입력된 횟수만큼 반복하여 새로운 문자열을 생성하는 문제
- 접근 방법
  - 테스트 케이스의 개수를 입력
  - 각 테스트 케이스마다, 반복 횟수와 문자열을 입력
  - 문자열의 각 문자를 주어진 반복 횟수만큼 반복하여 새로운 문자열생성
  - 반복된 문자열을 출력

### 프로젝트: 이미지 객체 감지 및 시각화
- 프로젝트 설명
  -OpenCV와 Google Cloud Vision API를 사용하여 이미지에서 객체를 감지하고, 감지된 객체를 이미지 위에 시각적으로 표시한 후, 결과를 HTML 파일로 저장하는 프로젝트
- 구현 방법
  -OpenCV를 통해 이미지 처리 및 시각화를 수행합니다.
  -Google Cloud Vision API를 사용하여 이미지에서 객체를 감지합니다.
  -감지된 객체의 라벨에 따라 고유한 색상을 지정하여 경계 상자를 그립니다.
  -결과 이미지를 파일로 저장하고, 감지된 객체 정보를 포함한 HTML 파일을 생성하여 웹 브라우저에서 결과를 확인할 수 있도록 합니다.

## 2023년 10월 7~8일(SW-AI 융합 스마트 메이커 대회, 1박2일 대회)

### 프로젝트 1: 캘린더 앱과 블루투스 통신
- 앱에서 날짜 값을 블루투스 통신으로 아두이노에 전송하고 LCD에 출력하는 아이디어를 구상했으나, 통신 문제로 포기.

### 프로젝트 2: 오늘의 운세
- 버튼을 누르면 무작위로 운세를 LCD에 출력.
- 버튼을 누르지 않은 상태에서는 인사말 출력.

### 대회 회고
- 밤새워 코딩하면서 결과물을 만들어보려는 첫 경험.
- 노력 대비 결과물이 미흡했지만, 배운 점이 많았음.
- 블루투스 문제로 인해 앱 구현 실패.
- 코드 이해의 중요성 및 기본기에 대한 중요성을 느낌.

## 2024-10-06
### 주제: 조건문, 반복문 복습
- if, else if, else, switch
  - if, else if를 사용하여 조건을 평가하고, else를 사용하여 모든 조건이 거짓일 때의 동작을 정의
  - switch문은 동일한 변수에 여러 값을 비교해야 할 때 유용
- for, while, do-while
  - for문은 반복 횟수가 정해져 있을 때 유용
  - while문은 조건이 참인 동안 반복
  - do-while은 최소 한 번은 실행되어야 할 때 사용

### 주제: 코딩 테스트 문제 풀이
#### 2884 알람 시계(조건문)
- 문제 설명: 현재 설정된 알람 시간에서 45분 일찍 설정하는 문제
- 접근 방법
  - 입력 받은 시간에서 45분 빼는 계산
  - 분이 0보다 작을 경우, 시간을 1시간 감소하고 분에 60을 더하기
  - 시간이 0보다 작아질 경우, 24시로 설정하여 전날로 돌아가기

#### 8393 합 (반복문)
- 문제 설명: 1부터 n까지 자연수를 모두 더하는 문제
- 접근 방법
  - 반복문을 사용하여 1부터 n까지의 수를 순회하며 합을 계산(반복문을 활용한 누적합)






