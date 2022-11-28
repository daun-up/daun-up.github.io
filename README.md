# 유레카 프로젝트
CATbook is a CATegory-centric Jekyll theme for bloggers. There is a switch button to toggle between dark mode and light mode. This theme is originally inspired from [Book](https://github.com/kkninjae/book).


[![LICENSE](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE) ![GENERATOR](https://img.shields.io/badge/made_with-jekyll-blue.svg) ![VERSION](https://img.shields.io/badge/current_version-1.0-green.svg)

**Demo:** https://starry99.github.io/catbook/

## blog_one < Git, Github, and Markdown >
- 유레카 프로젝트 수업 시간에 Git 과 Git hub, Markdown 에 대해 배우고 나의 Git Blog 를 만들고자 했다.


## blog_two < My very first blog >
- Ruby 기반 정적 웹사이트 생성기인 Jekyll 을 사용하였다.
- Github Repo를 Webpage로 만드는 활동을 하기로 했다. Git hub 에서 <username>.github.io 이름의 Repo 를 생성한다.
- 로컬 저장소와 원격 저장소를 연결한다.
- 

```sh
$ git clone <repo_name><path>
```
- git status 로 현재 상태를 확인하고 git add 로 변경 파일을 추가한다.
- git commit -m "message" 를 통해 변경사항을 계속해서 commit 해준다.
- git push 로 로컬 저장소의 내용으 원격 저장소에 반영한다. 

## blog_three < Add theme on blog >
- jekyll 을 설치 하고 jekyll serve 를 실행한 후 localhost:4000 를 접속하면 내 웹페이지의 현황을 볼 수 있다.
- git blog 테마를 git hub 에서 fork 해와서 내 로컬 저장소로 git clone 하여 테마를 적용하는 방법을 선택했다.

## blog_four < Customize my blog >
- disqus 를 이용하여 댓글 기능을 구현했다. 
  
## assignment
- 특강에 다루어졌던 내용 중 Markdown 을 선택하여 그 정의와 문법에 대한 post 를 작성했다.
- 기본 테마 이외의 'catbook' 테마를 적용했다.
- Google Analytics 을 추가했다. 

## 문제 해결 
- git clone 하는 과정에서 여러 가지를 시도하던 중 blog 가 여러 개 만들어져 저장 경로가 이상하게 설정되었다. 현재 내가 있는 디렉터리도 헷갈리게 되어서 git blog 설정이 엉키는 상황이 발생하였다. 이미 폴더가 존재한다는 메세지가 떠서 모두 찾아내 하나하나 삭제하고 다시 repo 를 만들어서 다른 이름으로 git clone 하였다.
- vs code 에서 post 를 업로드하고 저장하지 않아 git blog 에 반영되지 않았다. 로컬 저장소의 내용은 변경했는데 웹페이지에 반영이 되지 않아 push 과정을 계속해서 시도했으나 이미 모두 push 되었다는 메세지만 떠서 당황했다. vscode 에서 저장하지 않았다는 표시를 발견하고 clrl+s 하자 모두 반영되었다.

- jekyll serve 했을 때 웹 페이지가 정상적으로 반영되었고 commit도 되었어도 https://daun-up.github.io/ 에서는 웹 페이지를 build 하는 데에 시간이 걸린다. 

## License

[MIT License](https://opensource.org/licenses/MIT)
