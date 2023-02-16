# Python-library-example  



# 중요 내용  

## 1장 텍스트 다루기  

정규표현식 re  


## 3장 다양한 데이터 다루기  

날짜 계산 datetime.date  
두 날짜의 차이 datetime.timedelta  


## 4장 수학과 숫자 다루기  

정확한 소수점 계산 decimal.Decimal  
임의 값 random  


## 5장 함수형 프로그래밍 다루기  

순열 itertools.permutations  
조합 itertools.combinations  
정렬 함수의 키 매개변수에 함수 전달 functools.cmp_to_key  
정렬 함수의 키 매개변수에 적용하여 다양한 기준으로 정렬 operator.itemgetter  


## 6장 파일과 디렉터리 다루기  

파일 경로를 객체로 pathlib
경로명과 파일명 제공 os.path
패턴(유닉스 셸이 사용하는 규칙)을 이용하여 파일 검색 glob
파일 복사, 이동 shutil


## 7장 데이터 저장하고 관리하기   

복합 자료형을 파일로 저장하고 읽기 pickle   
데이터 베이스 사용하기 sqlite3  


## 8장 데이터 압축하고 보관하기  

여러 개의 파일을 zip 형식으로 합치거나 해제 zipfile  


## 9장 다양한 형식의 파일 다루기  

CSV파일 읽고 쓰기 csv  


## 10장 암호문 다루기  

MD5, SHA256등의 알고리즘으로 문자열을 해싱(hashing)할 때 사용 hashlib  


## 11장 운영체제 다루기

문자열을 파일처럼 사용 io.StringIO  
디버깅용 로그 남기기 logging  


## 12장 동시에 실행하기 

병렬처리(스레드) threading
병렬처리(멀티 프로세싱) multiprocessing
시스템 명령어 실행 subprocess

###  threading VS multiprocessing 

CPU 하나에서 진행되는 작업은 process 라 하며, 하나의 process 는 여러개의 thread 를 가질 수 있습니다.  
한 process 가 여러 thread 를 실행하는 것을 Concurrent execution  
여러 process 를 동시에 실행시키는 것을 Parallel execution  
 multithreading 은 I/O intensive tasks에 사용  
 multiprocessing 은 CPU intensive tasks에 사용  
 
 
 ## 13장 네트워크와 프로세스 간 통신 다루기  
 
 async/await 구문을 사용하여 동시성 코드를 작성할 수 있게 해주는 모듈 asyncio  
 TCP 서버/클라이언트 프로그램을 작성할 때 사용하는 모듈 socket  