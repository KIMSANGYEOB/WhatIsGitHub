# WhatIsGitHub
과연 깃헙이란 무엇인고?

## 디렉토리 구조


## SVN 워크 플로우는 다음과 같다.
- trunk디렉토리는 프로젝트의 최신 안정 버전을 나타냅니다.
- 능동 피쳐 작업은 아래의 하위 디렉토리에서 개발됩니다 branches.
- 기능이 완료되면 기능 디렉토리가 병합되고 trunk제거됩니다.
- SVN 프로젝트도 하나의 디렉토리에 저장됩니다.

## GIT 워크 플로우는 다음과 같다.
- Git 저장소는 모든 브랜치와 태그의 전체 히스토리를 .git 디렉토리에 저장합니다.
- 최신 안정 릴리스는 master지점 내에 있습니다.
- 활성 지형 작업은 별도의 지사에서 개발됩니다.
- 기능이 완료되면 지형지 물이 병합되고 master삭제됩니다.
- SVN과는 달리 Git을 사용하면 디렉토리 구조는 동일하게 유지되지만 파일 내용은 분기를 기반으로 변경됩니다.

## 보존 역사
SVN은 프로젝트의 히스토리가 절대로 변경되지 않는다고 가정하도록 구성됩니다. 하지만 깃허브는 이전 커밋 및 변경 사항을 수정할 수 있습니다 **git rebase**.

![](https://3.bp.blogspot.com/-TjoCwPzV880/WC7DfAR40TI/AAAAAAAAADw/Fx8fmm2vVmosDDOjfqx1lzstfvQ3IfSgQCLcB/s1600/gitStructure.png)