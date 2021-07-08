添加一個repo:   git remote add timer100 https://qiqi9643.github.io/timer100/
查看repo:  git remote

複製一個repo: 
  1. git clone --bare https://github.com/exampleuser/old-repository.git
  2. cd old-repository
  3. git push --mirror https://github.com/exampleuser/new-repository.git
  4. Remove the temporary local repository you created earlier.我使用salamander來姍，因為deltree沒作用


複製下載一個repo
  1.git clone https://github.com/qiqi9643/command，qiqi9643是username，command是repo名稱
