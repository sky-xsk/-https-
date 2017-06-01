# -https-
解决百度分享不支持https的问题
#第一步
首先,https://github.com/sky-xsk/-https-
我的github上，把这个文件下载或者克隆下来，这个步骤就不做过多解释！（有用的话给个star）
#第二步
解压压缩文件，把里面的static文件夹，放置到你网站的根目录下面，记住一定是根目录；
根目录是啥？这里解释一下，打开你的浏览器，打开百度主页，在搜索框里输入：“根目录是什么？”，看到一个合理的解释即可！（开个玩笑）
#第三步
window._bd_share_config={“common”:{“bdSnsKey”:{},”bdText”:””,”bdMini”:”2”,”bdMiniList”:false,”bdPic”:””,”bdStyle”:”0”,”bdSize”:”16”},”slide”:{“type”:”slide”,”bdImg”:”5”,”bdPos”:”left”,”bdTop”:”178.5”}};with(document)0[(getElementsByTagName(‘head’)[0]||body).appendChild(createElement(‘script’)).src=’https://sky-xsk.github.io/static/api/js/share.js?v=89860593.js?cdnversion='+~(-new Date()/36e5)];
看到这个，把src后面的网址改成如上面的代码，注意在src=’https://sky-xsk.github.io/static/api/js/share.js?v=89860593.js?cdnversion='+~(-new Date()/36e5)]里面，https://sky-xsk.github.io改成自己网址即可；
这里是我改好的，你按照这个修改该即可！
#注意
这里提两个主要点：
1.放置的路径一定是你网站的根目录；
2.修改的src一定是你自己的网址；
