BLDEA-CSE@DESKTOP-P79E8O5 MINGW64 /d/exp9 (master)
$ GIT_PAGER=git log --author="Gunduraj211" --since="11-05-2024" --until="11-06-2024"
bash: log: command not found

BLDEA-CSE@DESKTOP-P79E8O5 MINGW64 /d/exp9 (master)
$ git log --author="Gunduraj211" --since="11-05-2024" --until="11-06-2024"
commit d2809586ef323584c6f33ca726a8d32310ab406b (HEAD -> master)
Author: Gunduraj211 <gundurajc@gmail.com>
Date:   Wed Nov 6 09:58:29 2024 +0530

    fourthcommit

commit 4135a9d40c27dbb25a6d729bb470707cc4a5a405
Author: Gunduraj211 <gundurajc@gmail.com>
Date:   Wed Nov 6 09:56:47 2024 +0530

    thirdcommit

commit 1407b7e25b4a1975a62584901a0738b4a6b49468
Author: Gunduraj211 <gundurajc@gmail.com>
Date:   Wed Nov 6 09:55:17 2024 +0530

    secondcommit

commit a2e659ae02fa90f353da0b8324b4232bc0e30881
Author: Gunduraj211 <gundurajc@gmail.com>
Date:   Wed Nov 6 09:53:00 2024 +0530

    firstcommit

BLDEA-CSE@DESKTOP-P79E8O5 MINGW64 /d/exp9 (master)
$ git log -n 4
commit d2809586ef323584c6f33ca726a8d32310ab406b (HEAD -> master)
Author: Gunduraj211 <gundurajc@gmail.com>
Date:   Wed Nov 6 09:58:29 2024 +0530

    fourthcommit

commit 4135a9d40c27dbb25a6d729bb470707cc4a5a405
Author: Gunduraj211 <gundurajc@gmail.com>
Date:   Wed Nov 6 09:56:47 2024 +0530

    thirdcommit

commit 1407b7e25b4a1975a62584901a0738b4a6b49468
Author: Gunduraj211 <gundurajc@gmail.com>
Date:   Wed Nov 6 09:55:17 2024 +0530

    secondcommit

commit a2e659ae02fa90f353da0b8324b4232bc0e30881
Author: Gunduraj211 <gundurajc@gmail.com>
Date:   Wed Nov 6 09:53:00 2024 +0530

    firstcommit

BLDEA-CSE@DESKTOP-P79E8O5 MINGW64 /d/exp9 (master)
$ git log -n 3
commit d2809586ef323584c6f33ca726a8d32310ab406b (HEAD -> master)
Author: Gunduraj211 <gundurajc@gmail.com>
Date:   Wed Nov 6 09:58:29 2024 +0530

    fourthcommit

commit 4135a9d40c27dbb25a6d729bb470707cc4a5a405
Author: Gunduraj211 <gundurajc@gmail.com>
Date:   Wed Nov 6 09:56:47 2024 +0530

    thirdcommit

commit 1407b7e25b4a1975a62584901a0738b4a6b49468
Author: Gunduraj211 <gundurajc@gmail.com>
Date:   Wed Nov 6 09:55:17 2024 +0530

    secondcommit

BLDEA-CSE@DESKTOP-P79E8O5 MINGW64 /d/exp9 (master)
$ git remote add origin https://github.com/swati166/exp12.git

BLDEA-CSE@DESKTOP-P79E8O5 MINGW64 /d/exp9 (master)
$ git push origin master
remote: Permission to swati166/exp12.git denied to Gunduraj211.
fatal: unable to access 'https://github.com/swati166/exp12.git/': The requested URL returned error: 403

