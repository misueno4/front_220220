# front_220220

---

## git clone 처리방법
1. [github.com](https://github.com) 에서 계정 생성
2. `new repository`을 이용하여 새로운 저장소 생성
3. 사용할 폴더 위치에서 `git-bash`를 이용하여 
    ``` shell
    $ git clone [repository url]
    ```
4. 이후 새로운 문서를 생성, 기존문서 수정/삭제 후
5. 해당 data를 git에 올리기 위해
add , commit , push를 이용
    ``` shell
    $ git add [첨부할 data]
    $ git commit -m "[설명]"
    $ git push
    ```

---
## 과제 : git 생성부터, clone, (add, commit, push)*10번, repository 자체 삭제까지 - 5 회 이상 실행해보기