### 一 项目初始化阶段：
 git init 初始化git仓库
 git add .  
 git commit -m "init project"     
 在github上创建仓库web_bigevent   
 将本地仓库与github上的仓库关联起来:     
 1、git remote add origin git@github.com:YCQDZ/web_bigevent.git   
 2、git branch -M main   
 3、git push -u origin main   
 4、创建login分支：git checkout -b login     
 5、查看分支：git branch     
 

### 二、登陆/注册功能
http://www.uimaker.com/layui/index.html   
1、layui中CSS内置基础类   
layui-main: 设置一个宽度为1140px的水平居中块   
2、表单的验证需要导入Lay-ui的js文件 layui.all.js   
3、https://jquery.cuishifeng.cn/jQuery.ajaxPrefilter.html   

git add . 将所有文件添加到暂存区   
git commit -m "完成了登录和注册功能的开发"   
git push -u origin login 将本地的login分支推送到远程仓库中，也命名为login分支   
将login分支合并到master分支   
   git checkout master   
   git merge login   
git push 推送到远程仓库    

在master分支下创建index分支: git checkout -b index 

### 三、 后台主页
lay-shrink      	     
空值（默认）不收缩兄弟菜单子菜单            
all 收缩全部兄弟菜单子菜单       
lay-this       
这个类名实现某项默认选中         
git status        
git branch       
git add .         
git commit -m "完成了主页功能的开发"      
git push -u origin index      

### 四、用户
git checkout -b user               
lay-filter这个属性可以快速为form表单赋值和取值        
git add .       
git commit -m "完成个人中心功能的开发"       
git push -u origin user          
git checkout main     
git merge user      
git push       
git checkout -b article     
