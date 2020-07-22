# Coding_tips

### 간단한 팁[코드/리눅스/github]

----

  - 특정 폴더 안에서 하위디렉토리의 특정 확장자 또는 파일을 지울 때

    - find ./ -name '파일/확장자' -exec rm -rf {} \;
    
----

  - github 로컬 repo 덮어쓰기
      
        $ git fetch origin
        $ git reset --hard origin/master
