# Git

- Git 은 파일의 버전을 관리하는 툴

## Git 설치

- https://git-scm.com

![Image](https://github.com/user-attachments/assets/42742a69-2ba6-469b-956e-1137ff057e47)
![Image](https://github.com/user-attachments/assets/bffaebc0-b44c-4551-af96-e80c6a7f9d14)
![Image](https://github.com/user-attachments/assets/49d6cb2b-93d4-4b28-88fb-07f4822de5a0)

- `아래는 반드시 VSCode 설치하고 나서 진행하여야 함. (목록 확인 필요)`
  ![Image](https://github.com/user-attachments/assets/1ee7ca19-cef9-43bb-af0a-cc38444aece7)
- 나머지는 기본값으로 설치완료함.

## 

## Git 정보 확인 및 세팅
- Git 버전 확인
```bash
git --version
```

- 기본 브랜치명을 main으로 설정하기(초기설정으로 master 로 되어있음)
```bash
git config --global init.defaultBranch main
```

- Enter 키를 통일시킴(맥, 윈도우, 리눅스가 Enter키, 줄변경이 달리 처리됨)
```bash
git config --global core.autocrlf true
```

- Git 수정내역, commit 시 메세지 상세 남기기(VSCode로 작성하도록 세팅)
```bash
git config --global core.editor "code --wait"
```

- 사용자 설정(아이디, email)
```bash
git config --global user.name "sbk283"
git config --global user.email "sbkcoding@gmail.com"
```

```bash
git config --global user.name
git config --global user.email
```

# Github
- 회원가입(https://Github.com)
- 예제: til_git 저장소 생성 (생략)\

## Github 사용자 계정 보안 설정
- 초기 설정시 다음 내용을 필수로 확인한다. 
- `자격 증명 관리자` > 
- 깃허브 자격증

## Git 작업 및 GitHub 연결 작업 진행

### 1. 최초 프로젝트 관리를 git으로 설정