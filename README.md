# [cosmos][4]
宇宙


# 面向谁？
首先面向我自己。   
其次面向所有需要边讨论边开发的程序员，    
以及为数不多的[lisp][3]爱好者。    
有志WEB开发寻找实习项目的人。      
特别面向所有[cosmos][4]项目的开发者。     
最后面向谁，是由所有[cosmos][4]开发者共同决定的。     



# 它是什么?
是一锅石头汤，连石头都还没有的石头汤。          
是一场骗局，骗君入局。     
是我编的一个准备讲十年故事。如果半途cosmos服务器遍地开花，到处部署，那我就不再讲下去了，也不用讲下去了。             
是一构建在WEB上浏览器端的多人 [REPL][1]运行时生态系统。     
是一种原理上不高深，技术上没壁垒，实现上没难度，运营上没秘密，具有图灵完备性的可供研讨的计算机网络架构。
是一种WEB应用模式。
其实它没有名字，勉强叫它cosmos，又与cosmos区块链重了名。     



# 为什么做它？
1.多年前受游戏《MineCraft》启发，此后一直认为程序所有的劳动都可以通过“打游戏”的方式实现。     
2.是我本人对REPL这一形式的偏（执热）爱，希望将其推广至一切处、一切人、一切事，以至于能够工作、生活、娱乐在其中。           
3.我想借助这个项目练习使用node.js，这是我的第一个node.js项目，练练手。
4.邀请一切老鸟以及菜鸟参与本项目。  


# 怎么用？
[Git][2]用户都知道，要开始着手做一件事，那就建一个仓库。     
与之类似，cosmos用户要开始着手做一件事，那就建个小宇宙。     
事情发启人决定小宇宙的名字，从而构成一个链接地址，并将地址发给所有参与者。      
参与者们就通过浏览器进了同一个小宇宙，就像进入个微信群似的。     
但，小宇宙是图灵完备的，就在小宇宙里构建这个小宇宙本身。      


# 如何用[cosmos][4]盈利
我个人的利润恐怕十年之内都指望不上。    
利润属于发明[cosmos][4]应用，探索[cosmos][4]应用领域，构造和推广[cosmos][4]生态的个人或组织。    


# 如何部署？   
假设读者对node.js有基本的了解：     
1.将server.js client.html复制到同一目录下。     
2.执行node server.js               

我从头就希望cosmos服务器是任何人都能轻松部署的服务器。甚至可以部署在树莓派上。

# todo:
## 找人做一个原型达成意思表示       done
## 找人做一个将将能跑的DEMO推上来   done
### 解决uri路由问题，在浏览器中输入x.x.x.x:2333/aaa/bbb/ccc/uuu将进入aaa/bbb/ccc宇宙，并作为其中的uuu用户。    done
#### 若输入的uri为空，则进入该服务器的默认“/”号宇宙，没有特定用户名。                  done
#### /aaa/bbb/ccc/与/aaa/bbb/ccc不同：前者是匿名用户进入aaa/bbb/ccc宇宙，后者是ccc进入aaa/bbb宇宙。 done
### 解决数据结构问题，使得同一宇宙里的人讲话才能听见,一个服务器可以维持多个宇宙。  done
## 
## 部署一台cosmos服务器             done         
## 设计一些简单用例                 cancel           
## 规定并实现一些最高法则            cancel        
### 增强“太初”编辑器                cancel        
### 优化会话机制                    pending          
一位资深产品经理说：“我看不到你传上来的代码，这个并不有利于交流”。需要解决这个问题。 pending        
### 改进后台规则                    cancel           
用户进入一个宇宙时，宇宙应该为其重新演化一遍宇宙史。                              
一台cosmos服务器所有的宇宙中有一个【元宇宙】，或叫【法宇宙】，或叫【初始宇宙】，或叫【宪宇宙】，      
用户进入任何一个宇宙前都会首先重演【初始宇宙】。      
设用户以/a/b/c/d敲入，并设【初始宇宙】名为INIT，那么下列宇宙挨个重演：INIT、a、a/b、a/b/c。       
运营商应对【初始宇宙】的访问规定认证机制。
## 讨论下一步动向                   doing


[1]: https://en.wikipedia.org/wiki/Read%E2%80%93eval%E2%80%93print_loop
[2]: https://en.wikipedia.org/wiki/Git
[3]:https://en.wikipedia.org/wiki/Lisp
[4]:https://github.com/zhangshenhua/cosmos


# 哲学
## 宇宙并不开口说自己是宇宙，只是它让人知道它是“宇宙”。     
