# 유레카 프로젝트
CATbook is a CATegory-centric Jekyll theme for bloggers. There is a switch button to toggle between dark mode and light mode. This theme is originally inspired from [Book](https://github.com/kkninjae/book).


[![LICENSE](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE) ![GENERATOR](https://img.shields.io/badge/made_with-jekyll-blue.svg) ![VERSION](https://img.shields.io/badge/current_version-1.0-green.svg)

**Demo:** https://starry99.github.io/catbook/

## blog_one
- 유레카 프로젝트 수업 시간에 Git 과 Git hub, Markdown 에 대해 배우고 나의 Git Blog 를 만들고자 했다.


## blog_two
- Ruby 기반 정적 웹사이트 생성기인 Jekyll 을 사용하였다.
- Github Repo를 Webpage로 만드는 활동을 하기로 했다. Git hub 에서 <username>.github.io 이름의 Repo 를 생성한다.
- 로컬 저장소와 원격 저장소를 연결한다.

```sh
$ git clone <repo_name><path>
```
- git status 로 현재 상태를 확인하고 git add 로 변경 파일을 추가한다.
- git push 로 로컬 저장소의 내용으 원격 저장소에 반영한다. git commit -m "message" 를 통해 변경사항을 계속해서 commit 해준다.

## blog_three
- jekyll 을 설치 하고 jekyll serve 를 실행한 후 localhost:4000 를 접속하면 내 웹페이지의 현황을 볼 수 있다.
- git blog 테마를 git hub 에서 fork 해와서 내 로컬 저장소로 git clone 하여 테마를 적용하는 방법을 선택했다.

## 문제 해결 
- git clone 하는 과정에서 여러 가지를 시도하던 중 blog 가 여러 개 만들어져 저장 경로가 이상하게 설정되었다. 이미 폴더가 존재한다는 메세지가 떠서 모두 찾아내 하나하나 삭제하고 다시 repo 를 만들어서 다른 이름으로 git clone 하였다.
- vs code 에서 post 를 업로드하고 저장하지 않아 git blog 에 반영되지 않았다. 터무니 없는 실수였다

## License

[MIT License](https://opensource.org/licenses/MIT)
