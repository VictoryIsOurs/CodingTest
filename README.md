# Github으로 협업하기

1. 프로젝트 레포에서 `fork`를 해서 자신의 `Github`에 복사한다.

2. `fork`한 프로젝트를 자신의 로컬 저장소에 `clone`한다.

3. 협업할 프로젝트를 `upstream`으로 등록한다.

   ```
   $ git remote add upstream <url>
   $ git remote -v
   ```

4. 브랜치를 생성하고, 그 브랜치로 이동한다.

   ```
   $ git checkout -b 브랜치이름
   ```

   or

   ```
   $ git branch 브랜치이름
   $ git checkout 브랜치이름
   ```

5. 개발을 하고 이 브랜치에서 코드를 등록한다.

   ```
   $ git add *
   $ git commit -m "msg"
   $ git push origin 브랜치이름
   ```

6. `pull request`를 한다.

7. 작성한 `pull request`가 merge 되면, `master(or main)` 브랜치로 이동하여 `upstream`의 커밋 내역을 가져와서 동기화 시킨다.

   ```
   $ git checkout main
   $ git fetch upstream main
   $ git rebase upstream/main
   ```

   