# GIT

گیت یک بستر مناسب جهت پیش برد هر پروژه ای است که همزمان چندین نفر میتوانند روی یک پروژه در برنچ های مختلف کار کنند بدون اینکه برنچ مستر به مشکل بخورد. همین طور تمام تغییرات را ثبت میکند و میتوان به همه نسخه های گذشته به راحتی دسترسی داشت. 

* ### Create Repository

  ````shell
  >mkdir project
  >cd project
  project>git init
  >git status
  ````

  

* ### Commit

  ```shell
  >git status
  >git add <filename>
  >git commit -m ' '
  >git log
  ```

  

* ### Restore last change

  ```shell
  >git diff HEAD
  >git diff --staged
  >git reset <filename>
  >git checkout <filename>
  ```

  

* ### branch

  ```shell
  >git branch
  >git branch <newbranch>
  >git checkout <newbranch>
  >git marge <newbranch>
  ```

  

* ### Pull Push

  ```shell
  >git clone <URL>
  >cd <namerepo>
  >git push master origin
  >git pull origin master
  ```

  