# Shell(셸) 설정

## 기본 셸을 zsh로 변경

### zsh

<http://theyearlyprophet.com/love-your-terminal.html>  
bash와 비슷하게 동작하는 셸로, 사용성이 좋다.

#### 설치

**Ubuntu**  
왼쪽 아래의 점9개 정사각형 버튼 누르고 `terminal`입력 후 실행되는 검은 창에서 입력

```
sudo apt-get install zsh curl git
curl -L http://install.ohmyz.sh | sh
# 아래의 `which zsh`의 `는 작은따옴표가 아닌, 1 왼쪽의 ~표시 키 (Backqoute)
chsh -s `which zsh`
```

**macOS**

```
brew install zsh zsh-completions
curl -L http://install.ohmyz.sh | sh
```

> **확인법**  
> echo $SHELL

**두 운영체제 모두, 작업 완료 후 터미널을 종료하고 새로시작**