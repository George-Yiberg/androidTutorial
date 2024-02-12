# 1. introduction of androidTutorial

https://zhuanlan.zhihu.com/p/34584694

点击 New SSH key，你需要输入 Title 和 Key，但是你现在没有 key，往下看
打开 Git Bash
复制并运行 rm -rf ~/.ssh/* 把现有的 ssh key都删掉，这句命令行如果你多打一个空格，可能就要重装系统了，建议复制运行。
运行 ssh-keygen -t rsa -b 4096 -C "你的邮箱"，注意填写你的真实邮箱。
按回车三次


运行 cat ~/.ssh/id_rsa.pub，得到一串东西，完整的复制这串东西
    回到上面第 3 步的页面，在 Title 输入「我的第一个 key」
    在 Key 里粘贴刚刚你你复制的那串东西

​    

  回到 Git Bash
    运行 ssh -T git@github.com，你可能会看到这样的提示：


ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAACAQCbBnaUxKUG7qSXjZEyQUDgqJa9NfuPRXT5liFKHPNy6iEnGW8SnrJCmgYYZ3QaoRjTHzbS2Um8eIIOLhmnUsxU/LqfbxlCOgJ450RB9IlzvVwJCftwQYcplj7eDAy5qyDxdDr+hgIMyAmMFmPKu6DizqbQXXxX+ctFtLikm995Ul9+BP1QQtSRxnu1OD4VOjufq7w9b1PhrNLrDRaFKydBappYTsEk9AKd0nOxxsAcjHARjT3WIRgnMWdW+7Kc1LZvNcz6QvwjAATAdSOoEIpreFXMdsnOtH9GzV+YqI+zBYhIEIxYynz+/BiFK8HCQ1tw3Nni5gz2WYCX5+mzN6Hxqr3RCkApHktlsUR0RBdkTPt0feDlUu1jhZULyv1iUl7yKhzgI7kGj+ulW9kqgOIwz8rtdXTCsZKdmZYKQca1v7HGcQSwdYJI6vcA51hb2tiBgzPVIn6H4ACqGt4FWcjKQaUen3DfXBvrUHfCkexs4cIobTJr09cQCBBK4SzXmHQQqShC0VMAYpvbLlTefpeBN6sgx+iZRWy5xH9KmRvtsEMxNbkGm0EAZ31P7r+lESjfhJGCUWMab7R1jEo1JqYk1pV0e+gGsY1csrFWVhubpJDdGIoixvN2rcmO0kUhtJFGZbXOXT+IB85HvmqyhGHuqu6gK7EBry1X+SUWbSZAuQ== george.yiberg@gmail.com

git clone git@github.com:George-Yiberg/androidTutorial.git



复制ubuntu ~/.ssh/文件夹下的三个文件  至Windows 用户主目录的ssh目录下。  如果没有这个目录执行ssh-keygen之后就会有






# 2. four components

The ability to text, email, play games and much more are accomplished in Android applications through four top-level component classes: BroadcastReceiver, ContentProvider, Service, and Activity. 

# 2.1 activity







# 2.2 Service







# 2.3 ContentProvider





# 2.4 BroadcastReceiver





