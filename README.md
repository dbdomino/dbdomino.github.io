# 재학의 github blog, 테마 : Affiliates

[Live Demo](https://wowthemesnet.github.io/affiliates-jekyll-theme/) | [Docs & Download](https://bootstrapstarter.com/template-affiliates-bootstrap-jekyll/) |  [Buy me a coffee](https://www.wowthemes.net/donate/)

![jekyll-affiliates-theme](https://bootstrapstarter.com/assets/img/themes/affiliates-jekyll.jpg)

-------

디렉토리 구조 
* /_data      : : 개발자 및 운영자, 기타 정보 폴더 (author.yml 수정이 필요)
* /_includes  : 재사용을 위한 기본 페이지 폴더
* /_layouts   : 포스트를 감싸기 위한 레이아웃 정의 폴더(페이지, 구성요소 등 UI변경 시 수정)
* /_posts     : 포스트를 저장하는 폴더
* /_sass      : CSS 조각파일 저장 폴더
* /_site      : Jekyll 빌드 생성 결과물 폴더(실제 GitPages에서 WEB으로 보여지는 산출물)
* /.github    :  GitHub 연동을 위한 상태정보가 담긴 폴더
* /.jekyll-cache ㅣ git블로그 캐시 저장소
* /assets     : 이미지, CSS 등을 저장 폴더
* /pages      : 정적인 페이지 보관소
-------
_config.yml : 가장 중요한 환경변수 설정 파일 ☆☆☆☆

.gitignore : github commit 금지 리스트 설정 파일

404.html : 404 Not Found Page(블로그에 없는 페이지 요청 시 등장하는 페이지)

favicon.ico : 블로그 접속 시 브라우저 주소창에 표시되는 대표 아이콘

gemfile : 필요한 레일 기반 라이브러리를 자동으로 설치하고 싶을 때 명시하는 설정 파일

gemfile.lock : Gemfile에 기록한 레일 기반 라이브러리를 설치 후 기록하는 파일(중복설치 방지)

home.html : 블로그 최초 접속 페이지

index.md

LICENSE.txt  테마 개발자의 라이센스 설명

README.md