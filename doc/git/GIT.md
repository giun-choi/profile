[git 문서 링크](https://git-scm.com/docs/git)

## git pull

원격 저장소의 데이터를 로컬 저장소에 최신화합니다.

## git status

로컬 작업 공간의 상태를 확인합니다.

gitignore의 등록된 폴더 및 파일은 제외된 상태로 확인 됩니다.

## git diff

수정된 파일의 내용을 확인합니다.

## git config (--global) core.autocrlf true

CRLF 를 사용하므로 저장소에서 가져올 때 LF 를 CRLF 로 변경하고 저장소로 보낼 때는 CRLF 를 LF 로 변경하도록 설정한다.

## git add .

모든 작업 사항을 스테이지에 추가합니다.

## git add <파일명>

모든 파일을 스테이지에 올리고 싶지 않은 경우에는 파일명으로 스테이지에 추가하시기 바랍니다.

## git commit -m "<커밋 메세지>"

커밋(commit)합니다.
-m 옵션은 커밋 메시지를 남길 때 사용하는 옵션입니다.

## git push

로컬 저장소에 있는 커밋(commit)을 원격 저장소로 올립니다.
