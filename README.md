# vim

## Settings

```
cd ~
git clone --depth=1 https://github.com/amix/vimrc.git ~/.vim_runtime
sh ~/.vim_runtime/install_awesome_vimrc.sh

## 아래 중 골라서 실행
cd ~/.vim_runtime
install_awesome_parameterized.sh 
install_awesome_vimrc.sh 
install_basic_vimrc.sh 
```


``` 
##  vim ~/.vim_runtime/my_configs.vim
:set paste 
:set encoding=utf-8 
:set cursorline 
:set langmap=ㅁa,ㅠb,ㅊc,ㅇd,ㄷe,ㄹf,ㅎg,ㅗh,ㅑi,ㅓj,ㅏk,ㅣl,ㅡm,ㅜn,ㅐo,ㅔp,ㅂq,ㄱr,ㄴs,ㅅt,ㅕu,ㅍv,ㅈw,ㅌx,ㅛy,ㅋz 
:set term=xterm-256color
:set number " line 표시를 해줍니다.
:set ai " auto indent
:set si " smart indent
:set cindent " c style indent
:set shiftwidth=2 " shift를 2칸으로 ( >, >>, <, << 등의 명령어)
:set tabstop=2 " tab을 2칸으로
:set ignorecase " 검색시 대소문자 구별하지않음
:set hlsearch " 검색시 하이라이트(색상 강조)
:set expandtab " tab 대신 띄어쓰기로
:set background=dark " 검정배경을 사용할 때, (이 색상에 맞춰 문법 하이라이트 색상이 달라집니다.)
:set nocompatible " 방향키로 이동가능
:set fileencodings=utf-8,euc-kr " 파일인코딩 형식 지정
:set bs=indent,eol,start " backspace 키 사용 가능
:set history=1000 " 명령어에 대한 히스토리를 1000개까지
:set ruler " 상태표시줄에 커서의 위치 표시
:set nobackup " 백업파일을 만들지 않음
:set title " 제목을 표시
:set showmatch " 매칭되는 괄호를 보여줌
:set nowrap " 자동 줄바꿈 하지 않음
:set wmnu " tab 자동완성시 가능한 목록을 보여줌
 
" intelij IdeaVimExtension plugin, ~/.ideavimrc 
" :set keep-english-in-normal 
```


