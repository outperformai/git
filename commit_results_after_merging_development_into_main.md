thebiglion@lenovo:~/git$ git log --oneline
23ca161 (HEAD -> main) Merge branch 'development'
6c6771b Created two files commit_results_of_development_after_merge.md, and commit_results_of_development_b4_merge.md after test_development.md file commit in development branch to distinguish between rebase and merge.
9ce802a (development) Created development branch and test_development.md file to check commit results before and after merge to depicts the diffrence between rebase and merge.
7029c6c Updated commits_in_test_after_rebase.md with rebase commit results.
cfefec7 Created two files commits_in_test_after_rebase.md, and commits_in_test_before_rebase.md after making commits in test branch for test_branch.md and now I am commiting these changes and will switch again to test and rebase test on main to see the test commit will 
be on top of main recent commit or not.
62a358a if you stage some changes and untracked file is present then you can directly commit them but if no changes to be commited and 
only the untracked files are present then you can not directly commit them then you need to stage at least one file first and then comm
it other, in this case only untracked file wont be commited.
ace000d Commiting changes directly without staging.
61c6088 Merge branch 'fix'
a9dcde9 (fix) When I modify same line of code in file on main branch, the merge conflicts is not raising, so I did it in fix.
1efd2e4 Merge branch 'fix'
d2a78ac Added actor.jpeg
e637870 Modified the existing word in demo.txt to raise merge conflict.
0de521d Merge branch 'feature'
a0b217a (feature) Added image
6fc2c19 Merge branch 'fix'
a7f0209 Added painter.jpeg
edd69f6 Created demo.py
a687105 Merge branch 'fix' I added new picture in images dir on branch fix.
043c1c3 Added image
3832709 Modified app.py to intentionally raise merge conflict.
2e5780b Merge branch 'fix'
920d2a1 Created diretory images and modified main.py in main branch to intentionally raise merge conflicts.
52ebcce Addes content to rebase.md and changed main.py.
68086a9 Created fix.md
9d25076 Created rebase.md to see the difference between rebase and merge commit history.
e01a9ad Created merge_check.md file.
bb4eaec I applied stashes and now going to commit changes for test.md, tree.md and blooper.md.
c86d571 After Staging blooper.md, tree.md, and test.md, I stashed them and afterwards I created fish.txt and stash it directly without 
staging it and then I staged it and commited the changes and I will check out to main branch to see the what newly added file will be t
here in main branch.
6802daf This is second commit after undoing second commit.
6a83f31 Created src dir, main.py and app.py.
(END)