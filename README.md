# DGIST-RT626

대구경북과학기술원 2021년 1학기 지능시스템설계 과목 HW1

> 사전 요구 사항  
> 아래는 이 코드를 실행하기 위해서 설치해야하는 Python 코드입니다. 코드 실행 환경은 Windows 10, Python 3.8 입니다.
---

이 프로젝트를 위한 Python 가상환경을 따로 생성하는 것을 추천합니다.
```powershell
pip install venv
```

venv 패키지가 설치되면 이 Git 레포지토리의 root 경로에서 다음과 같은 명령어를 통해서 Python 가상환경을 설치합니다.
```powershell
# python -m venv (가상환경이름)
python -m venv .RT626

```

위 명령어를 실행하면 `.RT626`이란 폴더가 생성되며 그 아래에 Script 폴더가 생성된다. Script 폴더 아래에는 가상환경을 실행할 수 있는 `activate`라는 실행 파일이 생성된다. 아래와 같은 명령어로 가상환경을 실행합니다.
```powershell
.\.RT626\Scripts\activate
```

가상환경이 실행되면 아래 사진과 같이 Shell 명령어 창 가장 앞에 가상환경 이름인 `.RT626`이 강조된다.  

![image](https://github.com/VanguardDream/DGIST-RT626/blob/master/readme/1.png?raw=true)


가상환경에서 아래의 명령어로 Python 패키지를 설치한다.
```powershell
pip install keras=2.3.1
pip install tensorflow=2.2.0
pip install jupyter
pip install ipykernel
pip install pillow
pip install matplotlib
```

위의 과정을 실행하면 ipynb의 모든 코드를 실행 할 수 있다.  