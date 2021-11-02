# TikiTaka 
음성인터페이스 기반 일정관리 반응형 웹
<br><br><br>

## Tech Stack

**_Front End_**   
  * React.js   

**_Back End_**   
  * Node.js   

**_Database_**   
  * MySQL
<br><br><br>

## 프로젝트 소개
#### 기존 일정관리 서비스의 문제점 해결
    
    * 기존 일정관리 서비스는 텍스트 기반의 인터페이스로 입력 값 작성이 번거로움
      - NUI의 사용을 통해 음성 인터페이스로 자연스러운 대화형 상호작용 가능
      
    * 스마트폰 내부의 음성인식 API로 일정관리 기능을 호출 가능하지만 전체 어플에 대응하기 때문에 조작 불편
      - 일정관리만을 위한 음성인식을 적용해 간단한 과정으로 편리하게 일정 관리 가능
 <br>
<img width="840" alt="스크린샷 2021-06-10 오전 4 36 53" src="https://user-images.githubusercontent.com/59560592/121418042-81d5ee80-c9a5-11eb-8cc1-6da38c74fc2d.png">     
<br>
    
#### 프로젝트 개요
    * 음성인식 API를 통해 입력받은 입력값을 분석하고, 분석한 데이터에 대응하는 기능 수행
    
    * 음성합성 API로 결과를 출력하여 사용자에게 편리한 일정관리 서비스를 제공
    
    * Todo-List 형식의 일별 일정 관리 기능, 월별 주요 일정 관리 기능, 목표 달성률 관리 기능 제공
    
<br>
<img width="900" alt="스크린샷 2021-06-10 오후 2 18 46" src="https://user-images.githubusercontent.com/59560592/121469076-d2296c80-c9f6-11eb-9660-51a8dfb5190c.png">


<br><br>

#### 1. Todo-List 형식으로 일별 일정 관리
    - 음성인식을 통한 일정 등록, 삭제, 수정 및 완료 일정 체크하기 기능
    
    - 음성합성을 통한 일정 읽어주기 기능
 
<br>
<p>
<img width="300" src="https://user-images.githubusercontent.com/59560592/121467207-ac4e9880-c9f3-11eb-8472-90e9b3e41704.gif">&nbsp;&nbsp;&nbsp;&nbsp;
<img width="300" src="https://user-images.githubusercontent.com/59560592/121467228-b40e3d00-c9f3-11eb-96ab-eb63818a095b.gif">
</p>
<br><br>

#### 2. 월별 주요 일정 관리
    - 월별 일별 일정 확인, 해당 날짜의 일정으로 이동, 음성인식을 통한 일정 검색 기능

<br>
<img width="300" src="https://user-images.githubusercontent.com/59560592/121468033-1fa4da00-c9f5-11eb-9266-c61eab583162.gif">
<br><br>
 
#### 3. 목표 달성률 관리
    - 목표 지정 후 달성 기록 체크 기능

<br>
<img width="300" src="https://user-images.githubusercontent.com/59560592/121468194-5d096780-c9f5-11eb-9475-7184b8da67a1.gif">
<br><br>

#### 4. 반응형 웹 적용
    - Media Query와 Ant-Design 활용하여 화면 크기에 맞는 UI 제공
<br>
<img width="600" src="https://user-images.githubusercontent.com/59560592/121468430-bd000e00-c9f5-11eb-85b8-e498a303439d.gif">


<br><br><br><br><br>


