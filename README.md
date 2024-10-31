
pavan@PavanKalyan MINGW64 ~/OneDrive/Documents/Desktop/CSS/practice/MOCK-Interview-1/HTML/DL&DS
$ git init
Initialized empty Git repository in C:/Users/pavan/OneDrive/Documents/Desktop/CSS/practice/MOCK-Interview-1/HTML/DL&DS/.git/

pavan@PavanKalyan MINGW64 ~/OneDrive/Documents/Desktop/CSS/practice/MOCK-Interview-1/HTML/DL&DS (main)
$ git add .

pavan@PavanKalyan MINGW64 ~/OneDrive/Documents/Desktop/CSS/practice/MOCK-Interview-1/HTML/DL&DS (main)
$ git commit -m "DL and DS"
[main (root-commit) eca27ff] DL and DS
 1 file changed, 37 insertions(+)
 create mode 100644 index.html

pavan@PavanKalyan MINGW64 ~/OneDrive/Documents/Desktop/CSS/practice/MOCK-Interview-1/HTML/DL&DS (main)
$ git remote add origin https://github.com/pavanummagani1/DL-and-DS.git

pavan@PavanKalyan MINGW64 ~/OneDrive/Documents/Desktop/CSS/practice/MOCK-Interview-1/HTML/DL&DS (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 1.10 KiB | 1.10 MiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/pavanummagani1/DL-and-DS.git
 * [new branch]      main -> main

pavan@PavanKalyan MINGW64 ~/OneDrive/Documents/Desktop/CSS/practice/MOCK-Interview-1/HTML/DL&DS (main)
$ git diff
diff --git a/index.html b/index.html
index b002f99..f5f087f 100644
--- a/index.html
+++ b/index.html
@@ -32,6 +32,19 @@
             exercitationem cumque nostrum quas aspernatur delectus aut porro vel ex obcaecati quisquam illo cum? Magnam.
         </p>
     </details>
+
+    <details>
+        <summary>Hello Pavan</summary>
+        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Repudiandae architecto quis odit optio libero     
+            distinctio deserunt fugiat quam soluta, accusamus blanditiis, repellat doloribus eligendi quia mollitia    
+            itaque, voluptatum possimus adipisci.
+            Necessitatibus rerum ratione iusto quibusdam voluptas excepturi itaque asperiores vero molestiae assumenda 
+            sapiente ut dolorem, quis blanditiis perspiciatis quam doloremque corrupti? Dolorum quasi perspiciatis     
+            pariatur, maxime aliquam architecto ipsam nostrum.
+            Quis numquam laborum, eum accusamus et sint, impedit eligendi dignissimos veniam soluta, libero adipisci ad
+            exercitationem cumque nostrum quas aspernatur delectus aut porro vel ex obcaecati quisquam illo cum? Magnam.
+        </p>
+    </details>
 </body>

 </html>
\ No newline at end of file

pavan@PavanKalyan MINGW64 ~/OneDrive/Documents/Desktop/CSS/practice/MOCK-Interview-1/HTML/DL&DS (main)
$ git log
commit eca27ff579aa98c63a443e7519c9e80206a52191 (HEAD -> main, origin/main)
Author: PavanUmmagani07 <pavankalyanU@outlook.com>
Date:   Thu Oct 31 11:43:54 2024 +0530

    DL and DS

pavan@PavanKalyan MINGW64 ~/OneDrive/Documents/Desktop/CSS/practice/MOCK-Interview-1/HTML/DL&DS (main)
$ git add .

pavan@PavanKalyan MINGW64 ~/OneDrive/Documents/Desktop/CSS/practice/MOCK-Interview-1/HTML/DL&DS (main)
$ git commit -m "DL and DS"
[main a76e52f] DL and DS
 1 file changed, 13 insertions(+)

pavan@PavanKalyan MINGW64 ~/OneDrive/Documents/Desktop/CSS/practice/MOCK-Interview-1/HTML/DL&DS (main)
$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 284 bytes | 142.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/pavanummagani1/DL-and-DS.git
   eca27ff..a76e52f  main -> main

pavan@PavanKalyan MINGW64 ~/OneDrive/Documents/Desktop/CSS/practice/MOCK-Interview-1/HTML/DL&DS (main)
$ git log
commit a76e52fa7d3c9d1eb2bd34003b2c3faa8c43f560 (HEAD -> main, origin/main)
Author: PavanUmmagani07 <pavankalyanU@outlook.com>
Date:   Thu Oct 31 11:46:18 2024 +0530

    DL and DS

commit eca27ff579aa98c63a443e7519c9e80206a52191
Author: PavanUmmagani07 <pavankalyanU@outlook.com>
Date:   Thu Oct 31 11:43:54 2024 +0530

    DL and DS

pavan@PavanKalyan MINGW64 ~/OneDrive/Documents/Desktop/CSS/practice/MOCK-Interview-1/HTML/DL&DS (main)
$ git log --all
commit a76e52fa7d3c9d1eb2bd34003b2c3faa8c43f560 (HEAD -> main, origin/main)
Author: PavanUmmagani07 <pavankalyanU@outlook.com>
Date:   Thu Oct 31 11:46:18 2024 +0530

    DL and DS

commit eca27ff579aa98c63a443e7519c9e80206a52191
Author: PavanUmmagani07 <pavankalyanU@outlook.com>
Date:   Thu Oct 31 11:43:54 2024 +0530

    DL and DS

pavan@PavanKalyan MINGW64 ~/OneDrive/Documents/Desktop/CSS/practice/MOCK-Interview-1/HTML/DL&DS (main)
$ git checkout commitid a76e52fa7d3c9d1eb2bd34003b2c3faa8c43f560
error: pathspec 'commitid' did not match any file(s) known to git
error: pathspec 'a76e52fa7d3c9d1eb2bd34003b2c3faa8c43f560' did not match any file(s) known to git

pavan@PavanKalyan MINGW64 ~/OneDrive/Documents/Desktop/CSS/practice/MOCK-Interview-1/HTML/DL&DS (main)
$ git checkout a76e52fa7d3c9d1eb2bd34003b2c3faa8c43f560
Note: switching to 'a76e52fa7d3c9d1eb2bd34003b2c3faa8c43f560'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by switching back to a branch.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -c with the switch command. Example:

  git switch -c <new-branch-name>

Or undo this operation with:

  git switch -

Turn off this advice by setting config variable advice.detachedHead to false

HEAD is now at a76e52f DL and DS

pavan@PavanKalyan MINGW64 ~/OneDrive/Documents/Desktop/CSS/practice/MOCK-Interview-1/HTML/DL&DS ((a76e52f...))
$ git checkout-
git: 'checkout-' is not a git command. See 'git --help'.

The most similar command is
        checkout

pavan@PavanKalyan MINGW64 ~/OneDrive/Documents/Desktop/CSS/practice/MOCK-Interview-1/HTML/DL&DS ((a76e52f...))
$ git checkout -
Switched to branch 'main'

pavan@PavanKalyan MINGW64 ~/OneDrive/Documents/Desktop/CSS/practice/MOCK-Interview-1/HTML/DL&DS (main)
$ git branch
* main

pavan@PavanKalyan MINGW64 ~/OneDrive/Documents/Desktop/CSS/practice/MOCK-Interview-1/HTML/DL&DS (main)
$ git checkout -b newBranch
Switched to a new branch 'newBranch'

pavan@PavanKalyan MINGW64 ~/OneDrive/Documents/Desktop/CSS/practice/MOCK-Interview-1/HTML/DL&DS (newBranch)
$ git branch -M NEWBRANCH

pavan@PavanKalyan MINGW64 ~/OneDrive/Documents/Desktop/CSS/practice/MOCK-Interview-1/HTML/DL&DS (NEWBRANCH)
$ git branch -a
* NEWBRANCH
  main
  remotes/origin/main

pavan@PavanKalyan MINGW64 ~/OneDrive/Documents/Desktop/CSS/practice/MOCK-Interview-1/HTML/DL&DS (NEWBRANCH)
$ git add .

pavan@PavanKalyan MINGW64 ~/OneDrive/Documents/Desktop/CSS/practice/MOCK-Interview-1/HTML/DL&DS (NEWBRANCH)
$ git commit -m "NEWBRANCH"
[NEWBRANCH 68f7a76] NEWBRANCH
 1 file changed, 11 insertions(+)

pavan@PavanKalyan MINGW64 ~/OneDrive/Documents/Desktop/CSS/practice/MOCK-Interview-1/HTML/DL&DS (NEWBRANCH)
$ git checkout main
Switched to branch 'main'

pavan@PavanKalyan MINGW64 ~/OneDrive/Documents/Desktop/CSS/practice/MOCK-Interview-1/HTML/DL&DS (main)
$ git merge NEWBRANCH -m "MERGING"
Updating a76e52f..68f7a76
Fast-forward (no commit created; -m option ignored)
 index.html | 11 +++++++++++
 1 file changed, 11 insertions(+)

pavan@PavanKalyan MINGW64 ~/OneDrive/Documents/Desktop/CSS/practice/MOCK-Interview-1/HTML/DL&DS (main)
$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 304 bytes | 152.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/pavanummagani1/DL-and-DS.git
   a76e52f..68f7a76  main -> main

pavan@PavanKalyan MINGW64 ~/OneDrive/Documents/Desktop/CSS/practice/MOCK-Interview-1/HTML/DL&DS (main)
$ git log
commit 68f7a768abe258380001c52af92606068d51a16c (HEAD -> main, origin/main, NEWBRANCH)
Author: PavanUmmagani07 <pavankalyanU@outlook.com>
Date:   Thu Oct 31 11:56:29 2024 +0530

    NEWBRANCH

commit a76e52fa7d3c9d1eb2bd34003b2c3faa8c43f560
Author: PavanUmmagani07 <pavankalyanU@outlook.com>
Date:   Thu Oct 31 11:46:18 2024 +0530

    DL and DS

commit eca27ff579aa98c63a443e7519c9e80206a52191
Author: PavanUmmagani07 <pavankalyanU@outlook.com>
Date:   Thu Oct 31 11:43:54 2024 +0530

    DL and DS

pavan@PavanKalyan MINGW64 ~/OneDrive/Documents/Desktop/CSS/practice/MOCK-Interview-1/HTML/DL&DS (main)
$ git log --all
commit 68f7a768abe258380001c52af92606068d51a16c (HEAD -> main, origin/main, NEWBRANCH)
Author: PavanUmmagani07 <pavankalyanU@outlook.com>
Date:   Thu Oct 31 11:56:29 2024 +0530

    NEWBRANCH

commit a76e52fa7d3c9d1eb2bd34003b2c3faa8c43f560
Author: PavanUmmagani07 <pavankalyanU@outlook.com>
Date:   Thu Oct 31 11:46:18 2024 +0530

    DL and DS

commit eca27ff579aa98c63a443e7519c9e80206a52191
Author: PavanUmmagani07 <pavankalyanU@outlook.com>
Date:   Thu Oct 31 11:43:54 2024 +0530

    DL and DS

pavan@PavanKalyan MINGW64 ~/OneDrive/Documents/Desktop/CSS/practice/MOCK-Interview-1/HTML/DL&DS (main)
$

pavan@PavanKalyan MINGW64 ~/OneDrive/Documents/Desktop/CSS/practice/MOCK-Interview-1/HTML/DL&DS (main)
$ git diff a76e52fa7d3c9d1eb2bd34003b2c3faa8c43f560 eca27ff579aa98c63a443e7519c9e80206a52191
diff --git a/index.html b/index.html
index f5f087f..b002f99 100644
--- a/index.html
+++ b/index.html
@@ -32,19 +32,6 @@
             exercitationem cumque nostrum quas aspernatur delectus aut porro vel ex obcaecati quisquam illo cum? Magnam.
         </p>
     </details>
-
-    <details>
-        <summary>Hello Pavan</summary>
-        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Repudiandae architecto quis odit optio libero     
-            distinctio deserunt fugiat quam soluta, accusamus blanditiis, repellat doloribus eligendi quia mollitia    
-            itaque, voluptatum possimus adipisci.
-            Necessitatibus rerum ratione iusto quibusdam voluptas excepturi itaque asperiores vero molestiae assumenda
-            sapiente ut dolorem, quis blanditiis perspiciatis quam doloremque corrupti? Dolorum quasi perspiciatis     
-            pariatur, maxime aliquam architecto ipsam nostrum.
-            Quis numquam laborum, eum accusamus et sint, impedit eligendi dignissimos veniam soluta, libero adipisci ad
-            exercitationem cumque nostrum quas aspernatur delectus aut porro vel ex obcaecati quisquam illo cum? Magnam.
-        </p>
-    </details>
 </body>

 </html>
\ No newline at end of file

pavan@PavanKalyan MINGW64 ~/OneDrive/Documents/Desktop/CSS/practice/MOCK-Interview-1/HTML/DL&DS (main)
$

pavan@PavanKalyan MINGW64 ~/OneDrive/Documents/Desktop/CSS/practice/MOCK-Interview-1/HTML/DL&DS (main)
$
