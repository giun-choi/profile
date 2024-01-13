## .prettierignore

.pretierignore를 사용하여 특정 파일 및 폴더를 완전히 무시(재포맷하지 않음)합니다.

파일의 일부를 무시하려면 "pretier-innore" 주석을 사용합니다.

## .prettierignore 참고

기본적으로 prettier는 버전 제어 시스템 디렉터리(".git", ".sl", ".svn" 및 ".hg") 및 node_modules( --with-node-modulesCLI 옵션이 지정되지 않은 경우) 파일을 무시합니다.

Prettier는 ".gitignore" 파일이 실행되는 동일한 디렉터리에 있는 경우 해당 파일에 지정된 규칙을 따릅니다.

## npx prettier . --check

파일이 이미 포맷되었는지 확인만 합니다.

## Option

singleAttributePerLine
<br />(HTML, Vue 및 JSX에서 한 줄에 단일 속성을 적용합니다.)

- false: 한 줄에 단일 속성을 적용하지 마세요.
- true: 한 줄에 단일 속성을 적용합니다.
