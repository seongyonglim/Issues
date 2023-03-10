# VSCODE issue들

---

## 가상환경

---

### venv를 활용한 가상환경 만들기

```
$ py -3.7 -m venv py37_venv
```

이렇게 코드를 작성할 경우 python 3.7 버전의 가상환경이 py37_venv 라는 이름으로 만들어진다. (단, 파이썬 3.7 버전이 로컬에 설치 돼있어야 한다)

### venv 가상환경 켜기 / 나가기

```
$ py37_venv\Scripts\activate.bat
$ py37_venv\Scripts\deactivate.bat
```

### 현재 환경에 설치된 pip들 requirements.txt에 담기

```
$ pip freeze > requirements.txt
```

### requirements.txt 에 있는 모든 내용 삭제 (가상환경 초기화할 때 쓰임)

```
$ pip uninstall -r requirements.txt -y
```

### 주의 사항

간혹 위 명령어를 입력했을 때 가상환경에 안들어가질 때가 있다. 그럴 때 터미널이 Command Prompt 인지 확인하자

Select Default Profile << 여기서 기본 터미널 설정 가능하다.

---
