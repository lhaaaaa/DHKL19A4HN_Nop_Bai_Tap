ADMIN@LAPTOP-D5IKGNEJ MINGW64 ~

$ git clone https://github.com/TranTienDat-25174600189-19A4/25174600189\_Tran\_Tien\_Dat\_bai\_tap.git

fatal: destination path '25174600189\_Tran\_Tien\_Dat\_bai\_tap' already exists and is not an empty directory.



ADMIN@LAPTOP-D5IKGNEJ MINGW64 ~

$ cd 25174600189\_Tran\_Tien\_Dat\_bai\_tap



ADMIN@LAPTOP-D5IKGNEJ MINGW64 ~/25174600189\_Tran\_Tien\_Dat\_bai\_tap (main)

$ git add README.md

git commit -m "Cập nhật nội dung README.md với văn bản Lorem Ipsum"

Author identity unknown



\*\*\* Please tell me who you are.



Run



&nbsp; git config --global user.email "you@example.com"

&nbsp; git config --global user.name "Your Name"



to set your account's default identity.

Omit --global to set the identity only in this repository.



fatal: unable to auto-detect email address (got 'ADMIN@LAPTOP-D5IKGNEJ.(none)')



ADMIN@LAPTOP-D5IKGNEJ MINGW64 ~/25174600189\_Tran\_Tien\_Dat\_bai\_tap (main)

$ git push origin main

info: please complete authentication in your browser...





ADMIN@LAPTOP-D5IKGNEJ MINGW64 ~/25174600189\_Tran\_Tien\_Dat\_bai\_tap (main)

$ git add README.md

git commit -m "Cập nhật nội dung README.md"

git push origin main

Author identity unknown



\*\*\* Please tell me who you are.



Run



&nbsp; git config --global user.email "you@example.com"

&nbsp; git config --global user.name "Your Name"



to set your account's default identity.

Omit --global to set the identity only in this repository.



fatal: unable to auto-detect email address (got 'ADMIN@LAPTOP-D5IKGNEJ.(none)')

info: please complete authentication in your browser...

To https://github.com/TranTienDat-25174600189-19A4/25174600189\_Tran\_Tien\_Dat\_bai\_tap.git

&nbsp;! \[rejected]        main -> main (fetch first)

error: failed to push some refs to 'https://github.com/TranTienDat-25174600189-19A4/25174600189\_Tran\_Tien\_Dat\_bai\_tap.git'

hint: Updates were rejected because the remote contains work that you do not

hint: have locally. This is usually caused by another repository pushing to

hint: the same ref. If you want to integrate the remote changes, use

hint: 'git pull' before pushing again.

hint: See the 'Note about fast-forwards' in 'git push --help' for details.



ADMIN@LAPTOP-D5IKGNEJ MINGW64 ~/25174600189\_Tran\_Tien\_Dat\_bai\_tap (main)

$ # Tạo và làm việc trên branch\_1

git checkout main

git checkout -b branch\_1

echo "Lorem ipsum dolor sit amet, consectetur adipiscing elit." > text\_branch\_1.txt

git add text\_branch\_1.txt

git commit -m "Thêm text\_branch\_1.txt"

git push origin branch\_1



\# branch\_2

git checkout main

git checkout -b branch\_2

echo "Praesent ullamcorper orci eu erat placerat sodales." > text\_branch\_2.txt

git add text\_branch\_2.txt

git commit -m "Thêm text\_branch\_2.txt"

git push origin branch\_2



\# branch\_3

git checkout main

git checkout -b branch\_3

echo "Integer sit amet nisi aliquam, tempor libero quis, cursus erat." > text\_branch\_3.txt

git add text\_branch\_3.txt

git commit -m "Thêm text\_branch\_3.txt"

git push origin branch\_4\_branch\_4.txt" non ante." > text\_branch\_4.txt

Already on 'main'

Your branch is up to date with 'origin/main'.

Switched to a new branch 'branch\_1'

warning: in the working copy of 'text\_branch\_1.txt', LF will be replaced by CRLF the next time Git touches it

Author identity unknown



\*\*\* Please tell me who you are.



Run



&nbsp; git config --global user.email "you@example.com"

&nbsp; git config --global user.name "Your Name"



to set your account's default identity.

Omit --global to set the identity only in this repository.



fatal: unable to auto-detect email address (got 'ADMIN@LAPTOP-D5IKGNEJ.(none)')

Enumerating objects: 3, done.

Counting objects: 100% (3/3), done.

Delta compression using up to 16 threads

Compressing objects: 100% (2/2), done.

Writing objects: 100% (3/3), 957 bytes | 957.00 KiB/s, done.

Total 3 (delta 0), reused 3 (delta 0), pack-reused 0 (from 0)

remote:

remote: Create a pull request for 'branch\_1' on GitHub by visiting:

remote:      https://github.com/TranTienDat-25174600189-19A4/25174600189\_Tran\_Tien\_Dat\_bai\_tap/pull/new/branch\_1

remote:

To https://github.com/TranTienDat-25174600189-19A4/25174600189\_Tran\_Tien\_Dat\_bai\_tap.git

&nbsp;\* \[new branch]      branch\_1 -> branch\_1

A       text\_branch\_1.txt

Switched to branch 'main'

Your branch is up to date with 'origin/main'.

Switched to a new branch 'branch\_2'

warning: in the working copy of 'text\_branch\_2.txt', LF will be replaced by CRLF the next time Git touches it

Author identity unknown



\*\*\* Please tell me who you are.



Run



&nbsp; git config --global user.email "you@example.com"

&nbsp; git config --global user.name "Your Name"



to set your account's default identity.

Omit --global to set the identity only in this repository.



fatal: unable to auto-detect email address (got 'ADMIN@LAPTOP-D5IKGNEJ.(none)')

Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)

remote:

remote: Create a pull request for 'branch\_2' on GitHub by visiting:

remote:      https://github.com/TranTienDat-25174600189-19A4/25174600189\_Tran\_Tien\_Dat\_bai\_tap/pull/new/branch\_2

remote:

To https://github.com/TranTienDat-25174600189-19A4/25174600189\_Tran\_Tien\_Dat\_bai\_tap.git

&nbsp;\* \[new branch]      branch\_2 -> branch\_2

A       text\_branch\_1.txt

A       text\_branch\_2.txt

Switched to branch 'main'

Your branch is up to date with 'origin/main'.

Switched to a new branch 'branch\_3'

warning: in the working copy of 'text\_branch\_3.txt', LF will be replaced by CRLF the next time Git touches it

Author identity unknown



\*\*\* Please tell me who you are.



Run



&nbsp; git config --global user.email "you@example.com"

&nbsp; git config --global user.name "Your Name"



to set your account's default identity.

Omit --global to set the identity only in this repository.



fatal: unable to auto-detect email address (got 'ADMIN@LAPTOP-D5IKGNEJ.(none)')

Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)

remote:

remote: Create a pull request for 'branch\_3' on GitHub by visiting:

remote:      https://github.com/TranTienDat-25174600189-19A4/25174600189\_Tran\_Tien\_Dat\_bai\_tap/pull/new/branch\_3

remote:

To https://github.com/TranTienDat-25174600189-19A4/25174600189\_Tran\_Tien\_Dat\_bai\_tap.git

&nbsp;\* \[new branch]      branch\_3 -> branch\_3

A       text\_branch\_1.txt

A       text\_branch\_2.txt

A       text\_branch\_3.txt

Switched to branch 'main'

Your branch is up to date with 'origin/main'.

Switched to a new branch 'branch\_4'

warning: in the working copy of 'text\_branch\_4.txt', LF will be replaced by CRLF the next time Git touches it

Author identity unknown



\*\*\* Please tell me who you are.



Run



&nbsp; git config --global user.email "you@example.com"

&nbsp; git config --global user.name "Your Name"



to set your account's default identity.

Omit --global to set the identity only in this repository.



fatal: unable to auto-detect email address (got 'ADMIN@LAPTOP-D5IKGNEJ.(none)')

Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)

remote:

remote: Create a pull request for 'branch\_4' on GitHub by visiting:

remote:      https://github.com/TranTienDat-25174600189-19A4/25174600189\_Tran\_Tien\_Dat\_bai\_tap/pull/new/branch\_4

remote:

To https://github.com/TranTienDat-25174600189-19A4/25174600189\_Tran\_Tien\_Dat\_bai\_tap.git

&nbsp;\* \[new branch]      branch\_4 -> branch\_4



ADMIN@LAPTOP-D5IKGNEJ MINGW64 ~/25174600189\_Tran\_Tien\_Dat\_bai\_tap (branch\_4)

$ git branch -d branch\_4     # Xóa branch\_4 trên local

git branch --list          # Liệt kê các nhánh local

git fetch                 # Cập nhật remote

git branch -r             # Liệt kê nhánh trên remote (GitHub)

error: cannot delete branch 'branch\_4' used by worktree at 'C:/Users/ADMIN/25174600189\_Tran\_Tien\_Dat\_bai\_tap'

&nbsp; branch\_1

&nbsp; branch\_2

&nbsp; branch\_3

\* branch\_4

&nbsp; main

remote: Enumerating objects: 5, done.

remote: Counting objects: 100% (5/5), done.

remote: Compressing objects: 100% (2/2), done.

remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)

Unpacking objects: 100% (3/3), 1.32 KiB | 226.00 KiB/s, done.

From https://github.com/TranTienDat-25174600189-19A4/25174600189\_Tran\_Tien\_Dat\_bai\_tap

&nbsp;  19217c4..8074b8e  main       -> origin/main

&nbsp; origin/HEAD -> origin/main

&nbsp; origin/branch\_1

&nbsp; origin/branch\_2

&nbsp; origin/branch\_3

&nbsp; origin/branch\_4

&nbsp; origin/main



ADMIN@LAPTOP-D5IKGNEJ MINGW64 ~/25174600189\_Tran\_Tien\_Dat\_bai\_tap (branch\_4)

$ git checkout main

git pull origin main

A       text\_branch\_1.txt

A       text\_branch\_2.txt

A       text\_branch\_3.txt

A       text\_branch\_4.txt

Switched to branch 'main'

Your branch is behind 'origin/main' by 1 commit, and can be fast-forwarded.

&nbsp; (use "git pull" to update your local branch)

From https://github.com/TranTienDat-25174600189-19A4/25174600189\_Tran\_Tien\_Dat\_bai\_tap

&nbsp;\* branch            main       -> FETCH\_HEAD

Updating 19217c4..8074b8e

Fast-forward

&nbsp;README.md | 9 +++++++++

&nbsp;1 file changed, 9 insertions(+)



ADMIN@LAPTOP-D5IKGNEJ MINGW64 ~/25174600189\_Tran\_Tien\_Dat\_bai\_tap (main)

$ git checkout main

mkdir main\_folder

touch main\_folder/main\_txt\_1.txt main\_folder/main\_txt\_2.txt main\_folder/main\_txt\_3.txt



git add main\_folder/

git commit -m "Thêm thư mục main\_folder và 3 file text"

git push origin main

A       text\_branch\_1.txt

A       text\_branch\_2.txt

A       text\_branch\_3.txt

A       text\_branch\_4.txt

Already on 'main'

Your branch is up to date with 'origin/main'.

Author identity unknown



\*\*\* Please tell me who you are.



Run



&nbsp; git config --global user.email "you@example.com"

&nbsp; git config --global user.name "Your Name"



to set your account's default identity.

Omit --global to set the identity only in this repository.



fatal: unable to auto-detect email address (got 'ADMIN@LAPTOP-D5IKGNEJ.(none)')

Everything up-to-date



ADMIN@LAPTOP-D5IKGNEJ MINGW64 ~/25174600189\_Tran\_Tien\_Dat\_bai\_tap (main)

$ git checkout branch\_1

git pull origin main



git checkout branch\_2

git pull origin main



git checkout branch\_3

git pull origin main



git checkout branch\_4

git pull origin main

A       main\_folder/main\_txt\_1.txt

A       main\_folder/main\_txt\_2.txt

A       main\_folder/main\_txt\_3.txt

A       text\_branch\_1.txt

A       text\_branch\_2.txt

A       text\_branch\_3.txt

A       text\_branch\_4.txt

Switched to branch 'branch\_1'

From https://github.com/TranTienDat-25174600189-19A4/25174600189\_Tran\_Tien\_Dat\_bai\_tap

&nbsp;\* branch            main       -> FETCH\_HEAD

Updating 19217c4..8074b8e

Fast-forward

&nbsp;README.md | 9 +++++++++

&nbsp;1 file changed, 9 insertions(+)

A       main\_folder/main\_txt\_1.txt

A       main\_folder/main\_txt\_2.txt

A       main\_folder/main\_txt\_3.txt

A       text\_branch\_1.txt

A       text\_branch\_2.txt

A       text\_branch\_3.txt

A       text\_branch\_4.txt

Switched to branch 'branch\_2'

From https://github.com/TranTienDat-25174600189-19A4/25174600189\_Tran\_Tien\_Dat\_bai\_tap

&nbsp;\* branch            main       -> FETCH\_HEAD

Updating 19217c4..8074b8e

Fast-forward

&nbsp;README.md | 9 +++++++++

&nbsp;1 file changed, 9 insertions(+)

A       main\_folder/main\_txt\_1.txt

A       main\_folder/main\_txt\_2.txt

A       main\_folder/main\_txt\_3.txt

A       text\_branch\_1.txt

A       text\_branch\_2.txt

A       text\_branch\_3.txt

A       text\_branch\_4.txt

Switched to branch 'branch\_3'

From https://github.com/TranTienDat-25174600189-19A4/25174600189\_Tran\_Tien\_Dat\_bai\_tap

&nbsp;\* branch            main       -> FETCH\_HEAD

Updating 19217c4..8074b8e

Fast-forward

&nbsp;README.md | 9 +++++++++

&nbsp;1 file changed, 9 insertions(+)

A       main\_folder/main\_txt\_1.txt

A       main\_folder/main\_txt\_2.txt

A       main\_folder/main\_txt\_3.txt

A       text\_branch\_1.txt

A       text\_branch\_2.txt

A       text\_branch\_3.txt

A       text\_branch\_4.txt

Switched to branch 'branch\_4'

From https://github.com/TranTienDat-25174600189-19A4/25174600189\_Tran\_Tien\_Dat\_bai\_tap

&nbsp;\* branch            main       -> FETCH\_HEAD

Updating 19217c4..8074b8e

Fast-forward

&nbsp;README.md | 9 +++++++++

&nbsp;1 file changed, 9 insertions(+)



ADMIN@LAPTOP-D5IKGNEJ MINGW64 ~/25174600189\_Tran\_Tien\_Dat\_bai\_tap (branch\_4)

$ git checkout branch\_1

git checkout -b branch\_5



echo "Etiam malesuada felis nulla, ac porta dui sollicitudin eget. Mauris hendrerit non

metus eget pellentesque. Etiam ornare ante at pretium hendrerit. Proin molestie

accumsan sapien, ac finibus libero lobortis quis. Praesent ac commodo eros. Nullam

malesuada vel dui nec feugiat. Cras justo ipsum, scelerisque et elit vitae, porttitor

tristique turpis. Nam ut hendrerit est. Nulla sed tincidunt nibh. Class aptent taciti

sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Quisque vitae

egestas lacus. Phasellus turpis ante, euismod quis pellentesque et, pharetra id ligula.

Vestibulum mattis sem ac ligula auctor viverra. Phasellus dignissim mollis leo, vitae

tristique enim." > text\_branch\_1.txt



git add text\_branch\_1.txt

git commit -m "Cập nhật text\_branch\_1.txt trên branch\_5"

git push origin branch\_5

A       main\_folder/main\_txt\_1.txt

A       main\_folder/main\_txt\_2.txt

A       main\_folder/main\_txt\_3.txt

A       text\_branch\_1.txt

A       text\_branch\_2.txt

A       text\_branch\_3.txt

A       text\_branch\_4.txt

Switched to branch 'branch\_1'

Switched to a new branch 'branch\_5'

warning: in the working copy of 'text\_branch\_1.txt', LF will be replaced by CRLF the next time Git touches it

Author identity unknown



\*\*\* Please tell me who you are.



Run



&nbsp; git config --global user.email "you@example.com"

&nbsp; git config --global user.name "Your Name"



to set your account's default identity.

Omit --global to set the identity only in this repository.



fatal: unable to auto-detect email address (got 'ADMIN@LAPTOP-D5IKGNEJ.(none)')

Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)

remote:

remote: Create a pull request for 'branch\_5' on GitHub by visiting:

remote:      https://github.com/TranTienDat-25174600189-19A4/25174600189\_Tran\_Tien\_Dat\_bai\_tap/pull/new/branch\_5

remote:

To https://github.com/TranTienDat-25174600189-19A4/25174600189\_Tran\_Tien\_Dat\_bai\_tap.git

&nbsp;\* \[new branch]      branch\_5 -> branch\_5



ADMIN@LAPTOP-D5IKGNEJ MINGW64 ~/25174600189\_Tran\_Tien\_Dat\_bai\_tap (branch\_5)

$ git branch -d branch\_5

git push origin --delete branch\_5

error: cannot delete branch 'branch\_5' used by worktree at 'C:/Users/ADMIN/25174600189\_Tran\_Tien\_Dat\_bai\_tap'

To https://github.com/TranTienDat-25174600189-19A4/25174600189\_Tran\_Tien\_Dat\_bai\_tap.git

&nbsp;- \[deleted]         branch\_5



ADMIN@LAPTOP-D5IKGNEJ MINGW64 ~/25174600189\_Tran\_Tien\_Dat\_bai\_tap (branch\_5)

$ git branch -d branch\_2

git branch -d branch\_3

git branch -d branch\_4



git push origin --delete branch\_2

git push origin --delete branch\_3

git push origin --delete branch\_4



git checkout branch\_1

git pull origin main

git push origin branch\_1

Deleted branch branch\_2 (was 8074b8e).

Deleted branch branch\_3 (was 8074b8e).

Deleted branch branch\_4 (was 8074b8e).

To https://github.com/TranTienDat-25174600189-19A4/25174600189\_Tran\_Tien\_Dat\_bai\_tap.git

&nbsp;- \[deleted]         branch\_2

To https://github.com/TranTienDat-25174600189-19A4/25174600189\_Tran\_Tien\_Dat\_bai\_tap.git

&nbsp;- \[deleted]         branch\_3

To https://github.com/TranTienDat-25174600189-19A4/25174600189\_Tran\_Tien\_Dat\_bai\_tap.git

&nbsp;- \[deleted]         branch\_4

A       main\_folder/main\_txt\_1.txt

A       main\_folder/main\_txt\_2.txt

A       main\_folder/main\_txt\_3.txt

A       text\_branch\_1.txt

A       text\_branch\_2.txt

A       text\_branch\_3.txt

A       text\_branch\_4.txt

Switched to branch 'branch\_1'

From https://github.com/TranTienDat-25174600189-19A4/25174600189\_Tran\_Tien\_Dat\_bai\_tap

&nbsp;\* branch            main       -> FETCH\_HEAD

Already up to date.

Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)

To https://github.com/TranTienDat-25174600189-19A4/25174600189\_Tran\_Tien\_Dat\_bai\_tap.git

&nbsp;  19217c4..8074b8e  branch\_1 -> branch\_1





