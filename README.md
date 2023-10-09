# git - 형상관리 툴(버전관리)

### git 설치
* git-scm.com
![image](https://github.com/somi9954/git_exam2/assets/137499604/72cd3252-15b4-420f-b3e9-ea31f19650af)
![image](https://github.com/somi9954/git_exam2/assets/137499604/58af1d03-0d72-4ee0-ba11-1bd928c8ad1d)
![image](https://github.com/somi9954/git_exam2/assets/137499604/cde211ff-e5eb-4fe0-9b4c-c56be82bc5b3)
![image](https://github.com/somi9954/git_exam2/assets/137499604/c55ec2c2-a282-4386-9cf2-1f287219fb4c)
![image](https://github.com/somi9954/git_exam2/assets/137499604/a24b4964-02a1-4cbc-8ab9-b90c691427ec)
![image](https://github.com/somi9954/git_exam2/assets/137499604/1a998c5a-0eb3-4f28-911b-e6b04b7ec411)
![image](https://github.com/somi9954/git_exam2/assets/137499604/afcd1546-4196-4c3d-b9b2-6e7ea29c5529)
![image](https://github.com/somi9954/git_exam2/assets/137499604/9477a7fb-7757-4f37-b232-0f3b51819d5e)
![image](https://github.com/somi9954/git_exam2/assets/137499604/f818224a-3af3-42e3-b9d1-c799e8078aba)
![image](https://github.com/somi9954/git_exam2/assets/137499604/663a9104-e22e-43af-8bf5-cedc688eeeba)
![image](https://github.com/somi9954/git_exam2/assets/137499604/b13404d3-bc22-42d2-b18c-1e56f13dd55b)
![image](https://github.com/somi9954/git_exam2/assets/137499604/215f0ce1-8caf-474e-bb7c-d20d0cf27f4e)
![image](https://github.com/somi9954/git_exam2/assets/137499604/a78c137b-3201-47d4-8ac9-a3836ee687df)
![image](https://github.com/somi9954/git_exam2/assets/137499604/dddc0f1a-5388-4a48-91ea-1ce1ff7a3411)
![image](https://github.com/somi9954/git_exam2/assets/137499604/ec9ac509-eb06-4e7f-8e72-193bbde11b83)
![image](https://github.com/somi9954/git_exam2/assets/137499604/e335ca7e-8e3e-4f8d-b67f-91ed0a61bf41)


### 로컬 레포지토리(로컬 저장소)
* 형상(버전)을 관리, 저장할수 있는 공간
  
```JAVA
 git init
```
![image](https://github.com/somi9954/git_exam2/assets/137499604/e5a3739c-aeff-4078-a2d5-23413d3c0db6)

* / .git 폴더 생성  
![image](https://github.com/somi9954/git_exam2/assets/137499604/58a66731-83d5-403c-8ee9-83bb21f5397d)
		
참고)</br>
cd : 디렉토리 변경 </br>
dir : 현재 디렉토리의 파일 목록, 디렉토리 목록</br>
/ p -> 페이지 단위, / w -> 가로로 넓게</br>
cls : 화면 지우기 
		
		
### 계정 연결
* 원격 레포지토리 : 깃허브, 깃랩, 비트버킷...
```JAVA	
	git config --global  user.name "somi9954"
	git config --global user.email "jolh999@gmail.com"
```
![image](https://github.com/somi9954/git_exam2/assets/137499604/fcbbb7bc-a0ca-493d-9ac6-ad8127aa4186)

### 형상관리 - 스냅 샷 
* 스테이지 단계 </br>
	git add 반영할 파일명 또는 경로 </br>
  git add . : (모든 변경된 파일)
	```JAVA
	git add .
	```
 ![image](https://github.com/somi9954/git_exam2/assets/137499604/e44662a1-2b44-4545-ab3b-c69d1f33966e)

* 스냅샷 단계
	* 스테이지 단계에 있는 변경된 파일 또는 추가된 파일 -> 시점을 기록 
	* 커밋 단계 
	```JAVA
	git commit -m "작업 내용 메모"
	```

 * 커밋 로그
	 * git log  : 커밋한 시점별 기록
    ```Java
    	git log
    ```
 ![image](https://github.com/somi9954/git_exam2/assets/137499604/98128800-a803-4693-8a4c-68e5b35fa90b)
```java
	git log --oneline // 간단하게 로그 요약으로 보여줌
```
![image](https://github.com/somi9954/git_exam2/assets/137499604/50944f73-abfc-4e72-a423-9196dc1526f8)

* 버전 관리</br>
	* git checkout 커밋 ID
	![image](https://github.com/somi9954/git_exam2/assets/137499604/e5ce9427-6585-4867-a577-a33b82472ee5)
![image](https://github.com/somi9954/git_exam2/assets/137499604/214660c4-02ac-4401-8766-0b863c49181b)


	* git checkout - : 이전 커밋 시점으로 복구 
![image](https://github.com/somi9954/git_exam2/assets/137499604/1784dd99-845a-4067-9734-64fed8f3e972)
![image](https://github.com/somi9954/git_exam2/assets/137499604/902bafb2-2ca1-4f95-8db9-bb98cd250fa5)


* 브랜치 관리
	git branch 브랜치명 
		-> 현재 브랜치 기준 -> 새로운 브랜치
		-> 주문, 회원, 장바구니
	![image](https://github.com/somi9954/git_exam2/assets/137499604/23bfa63a-1bc8-44c9-8402-8fa06c30f85a)

	git branch -m 브랜치명 : 현재 브랜치의 명을 변경 
				   -M : 강제 변경 
				   
	git branch -d 브랜치명 : 브랜치 삭제 
	               -D : 강제 삭제 
	![image](https://github.com/somi9954/git_exam2/assets/137499604/9d1f061e-1f8c-4c27-a38a-58edbaf93c48)

	참고)</br>
		git branch : 브랜치 목록 
* 브랜치 변경
	git checkout 브랜치명
	
* 소스 합치기
	git merge 병합할 브랜치 
	- 현재 브랜치에 병합할 브랜치의 소스가 통합
	
	- 테스트가 반드시 수행 
	- 테스트 브랜치 생성하고 병합하고 -> 테스트 진행 -> master 브랜치에 병합
![image](https://github.com/somi9954/git_exam2/assets/137499604/bb0de17f-2b15-4270-a310-6ef87f570444)
![image](https://github.com/somi9954/git_exam2/assets/137499604/be49f1bf-eccd-4a47-aedf-ed8a42777b8f)

	
### 원격 레포지토리 
* 로컬 레포지토리 -> 원격 레포지토리 상태 반영(push)  -> 다른 로컬 레포지토리에서 동기화(pull)
```JAVA
	git remote add origin 원격 레포지토리 주소
```
 ![image](https://github.com/somi9954/git_exam2/assets/137499604/e89f79db-8e8e-4b77-8337-9063a33b5c8a)

참고)</br>
		git remote set-url origin 수정할 원격 레포지토리 주소
	
	
* 로컬 레포지토리 상태 -> 원격 레포지토리 상태로 반영
  ```JAVA
	git push origin 원격 레포지토리 브랜치명
	```
  ![image](https://github.com/somi9954/git_exam2/assets/137499604/5526ac5f-cb9b-4cf7-adb1-8f7106390395)

* 원격 레포지토리 상태 -> 로컬 레포지토리 상태 반영
  ```JAVA
  git pull origin 원격 레포지토리 브랜치명 - 동기화
	```
![image](https://github.com/somi9954/git_exam2/assets/137499604/c2b8e746-d140-4d81-94e3-2c17621478b4)
![image](https://github.com/somi9954/git_exam2/assets/137499604/a316caf0-4d83-4e02-b186-82ab7dfec77f)
* master밖에 없을 경우 checkout을 하여 mypage가 생기도록 한다.
![image](https://github.com/somi9954/git_exam2/assets/137499604/85d4c977-05f3-44c9-8e1c-a0232dfcd633)

* git clone 원격 레포지토리 주소
   ```JAVA
		-> git init + git remote add ... + git pull origin ...
	```
![image](https://github.com/somi9954/git_exam2/assets/137499604/36db40bd-ac61-4d4e-9a7d-b9242d0e61ed)

* 충돌이 날 경우
  ![image](https://github.com/somi9954/git_exam2/assets/137499604/5400d380-2e8b-412c-8c38-6c58955a379f)
![image](https://github.com/somi9954/git_exam2/assets/137499604/02ba19aa-fdfa-4ae1-a0b1-230134772f2e)
  * 충돌 위치를 확인하여 팀원과 상의 후 지울걸 확인한다.
   ![image](https://github.com/somi9954/git_exam2/assets/137499604/ab6c951c-383a-4cdc-974e-ca1a0a02cb2f)
  * 다시 수정후 스테이지 단계를 다시 작업한다.
		![image](https://github.com/somi9954/git_exam2/assets/137499604/21ef5ba6-37fa-4077-bf71-a8b9dcdaefd5)

* .gitignore 원격 레포지토리 반영 제외
	
* 태그 - 버전별 / 릴리즈(배포)
 * git tag -> 현재 태그 목록 
 * git tag -a 태그 : 태그 등록</br>
		  -l "태그명 패턴"
 * ESC -> :  -> wq 엔터
