---
date: 2021-05-24 17:13:08
comments: false
thumbnail: https://cdn.jsdelivr.net/gh/yagote/yagote.github.io@master/img/东京.jpg 
---
<div class = "text-center"><h1>碎碎念</h1></div><div class = "text-tips">

<!-- tips：github登录后按时间正序查看、可点赞加❤️、本插件[地址](https://github.com/removeif/gitalk)..<span id="busuanzi_container_page_pv">「<span id="busuanzi_value_page_pv">+99</span>次查看」</span></div> -->
tips：github登录后按时间正序查看、可点赞加❤️、本插件[地址](https://github.com/removeif/gitalk)..<span id="busuanzi_container_page_pv">「<span id="busuanzi_value_page_pv"></span>次查看」</span></div> <!--去掉了+99-->
<div id="comment-container1"><div class="text-tips">碎碎念加载中，请稍等...</div></div>
<link rel="stylesheet" href="https://cdnjs.loli.net/ajax/libs/gitalk/1.6.0/gitalk.css"/>
<script>
    $.getScript("/js/gitalk_self.min.js", function () {
        var gitalk = new Gitalk({
            clientID: '46a9f3481b46ea0129d8',
            clientSecret: '79c7c9cb847e141757d7864453bcbf89f0655b24',
            id: '666666',
            repo: 'issue_database',
            owner: 'yagote',
            admin: "yagote",
            createIssueManually: true,
            distractionFreeMode: false
        });
        gitalk.render('comment-container1');
    });
</script>