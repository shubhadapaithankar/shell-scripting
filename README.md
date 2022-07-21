# shell-scripting

Script for hosting the website.

![image](https://user-images.githubusercontent.com/99461999/180093479-9d578681-3adb-4c22-9839-ca5145ba4069.png)
![image](https://user-images.githubusercontent.com/99461999/180093602-5e413e28-c63a-421d-94b1-3af4253b834e.png)

## [root@scriptbox remote_websetup]# for host in `cat remotehosts` ; do ssh devops@$host hostname; done
web01
web02
## [root@scriptbox remote_websetup]# for host in `cat remotehosts` ; do ssh devops@$host sudo yum install git -y ; done
Loaded plugins: fastestmirror
Determining fastest mirrors
Resolving Dependencies
--> Running transaction check
---> Package git.x86_64 0:1.8.3.1-23.el7_8 will be installed
--> Processing Dependency: perl-Git = 1.8.3.1-23.el7_8 for package: git-1.8.3.1-23.el7_8.x86_64
--> Processing Dependency: perl(Term::ReadKey) for package: git-1.8.3.1-23.el7_8.x86_64
--> Processing Dependency: perl(Git) for package: git-1.8.3.1-23.el7_8.x86_64
--> Processing Dependency: perl(Error) for package: git-1.8.3.1-23.el7_8.x86_64
--> Running transaction check
---> Package perl-Error.noarch 1:0.17020-2.el7 will be installed
---> Package perl-Git.noarch 0:1.8.3.1-23.el7_8 will be installed
---> Package perl-TermReadKey.x86_64 0:2.30-20.el7 will be installed
--> Finished Dependency Resolution


