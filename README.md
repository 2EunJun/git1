# 1230-Git사용법


### 1. **사용자 이름과 이메일 설정**

Git에서 사용자 정보를 설정하는 명령어입니다.

```bash
$ git config --global user.name "사용자이름"
$ git config --global user.email "사용자이메일"
```

### 2. **GitHub에서 저장소 클론**

GitHub에 있는 저장소를 로컬로 복제하는 명령어입니다.

```bash
$ git clone https://github.com/2EunJun/git1.git
```

### 3. **사용자 이름과 이메일 설정 확인**

현재 설정된 사용자 정보를 확인할 수 있습니다.

```bash
$ git config user.name
$ git config user.email
```

### 4. **원격 저장소 추가**

로컬 저장소에 원격 저장소를 연결하는 명령어입니다.

```bash
$ git remote add origin 원격저장소주소
```

### 5. **작업 흐름: Pull, Add, Commit, Push**

원격 저장소와 동기화하고 변경사항을 커밋 후 푸시하는 작업 흐름입니다.

1. **원격 저장소 내용 가져오기(Pull)**
    
    ```bash
    $ git pull origin main
    ```
    
2. **변경 파일 스테이징(Add)**
    
    ```bash
    $ git add README.md
    ```
    
3. **변경사항 커밋(Commit)**
    
    ```bash
    $ git commit -m "Update README.md content"
    ```
    
4. **변경사항 원격 저장소로 푸시(Push)**
    
    ```bash
    $ git push origin main
    ```
    

### 6. **스페이스와 엔터 구분**

- **스페이스 두 번**: 문장 사이의 **줄바꿈(Enter)** 역할.
- **엔터 두 번**: 문단 사이에 **한 줄 공백**을 만듭니다.