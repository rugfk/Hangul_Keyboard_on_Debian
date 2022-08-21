# 데비안에서 한글 키보드 설정하기

***

```
sudo apt install nabi im-config zenity -y
sudo apt update
im-config -n hangul
im-config
```

추가적으로 팝업창이 나옵니다 첫번째 화면에서  OK=>NO=>OK
순으로 진행해 주시면 됩니다
```
ls -a
sudo vi .xinputrc
```
```
export XIM=nabi
export XIM_ARGS=
export XIM_PROGRAM="nabi"
export XMODIFIERS="@im=nabi"
export GTK_IM_MODULE=xim
```
shift+space 누르시면 나비키보드 설치 후에 한글 영문 변경이 가능합니다.
