Boyuan Shao

Activity 1:

<img width="655" alt="截屏2022-09-16 上午11 27 01" src="https://user-images.githubusercontent.com/59927679/190676621-2c22748c-1c3f-44fd-9609-c1f186b2ecf6.png">

Activity 2:

<img width="513" alt="截屏2022-09-16 上午11 40 12" src="https://user-images.githubusercontent.com/59927679/190677485-f2cf75c2-c04e-473c-b439-a495dd72c012.png">

Activity 3:

<img width="1449" alt="截屏2022-09-16 下午9 20 05" src="https://user-images.githubusercontent.com/59927679/190835018-f9b51665-d101-4382-bbd4-8a640d4b6d9c.png">


Activity 5:

The lab handout and TA's statement is contradicting for this activity. If our goal is to update "develop" branch (as TA Enmeng Liu said in Piazza), it is impossible to move c1, c2 after c4 using git rebase. If we want to achieve that, we would have to use something like git cherry pick. If we want c3->c4->c1->c2, we must update the branch "rebase". To do that, we have to first switch to branch "rebase", and run "git rebase develop", and then the branch "rebase" would have c3->c4->c1->c2. But I don't think this is what this activity intended to be.

<img width="624" alt="截屏2022-09-18 下午4 49 54" src="https://user-images.githubusercontent.com/59927679/190927633-6ca4607f-75b3-45ef-8288-7ffecb1907de.png">
