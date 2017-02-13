1.git clone  https://github.com/xxx/xxx.git  
  
2.xxxx@Lenovo-PC MINGW64 /e/git12  
$ ls  
mvc/  
  
3.xxx@Lenovo-PC MINGW64 /e/git12  
$ cd mvc/  
  
4.xxx@Lenovo-PC MINGW64 /e/git12/mvc (master)  
$ git branch -a                                      //查看你的所有分支  
  
* master  
  remotes/origin/HEAD -> origin/master                  
  remotes/origin/branch1                             //branch1 和branch2 两个分支  
  remotes/origin/branch2  
  
5.fushanshan@Lenovo-PC MINGW64 /e/git12/mvc (branch1)    //把branch1的东西克隆下来  
$ git checkout -b branch1 origin/branch1
