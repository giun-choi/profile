## warning: in the working copy of <파일명>, LF will be replaced by CRLF the next time Git touches it (<파일명>의 작업 복사본에서 LF는 다음에 Git가 터치할 때 CRLF로 대체됩니다)

https://docs.github.com/ko/get-started/getting-started-with-git/configuring-git-to-handle-line-endings

OS마다 사용되는 줄바꿈 문자열이 다르기 때문에 git에서 어떤 의미로 받아들여야 할지 몰라 에러 메시지가 나타난 것이다.
에러를 해결하지 않으면 줄바꿈 문자에 의해 커밋 내역이나 설정 파일들이 이상해질 수 있으니 통일시키는 것을 추천한다.

git config (--global) core.autocrlf true

CRLF 를 사용하므로 저장소에서 가져올 때 LF 를 CRLF 로 변경하고 저장소로 보낼 때는 CRLF 를 LF 로 변경하도록 설정한다.

## unable to auto-detect email address

git bash를 관리자 권한으로 실행한다.

git config --global user.email "이메일"
git config --global user.name "이름"

다음과 같이 차례대로 입력하여 설정한다.
