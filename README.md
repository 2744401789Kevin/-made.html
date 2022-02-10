# -made.html
...
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>2022 北京冬奥会</title>
    <style type="text/css">
        /*左边栏目的内容修饰*/
        #leftContentDiv {

            display: inline-block;
            margin-left: 6%;
        }

        span {
            font-size: 35px;
            color: rgb(44, 44, 207);
            font-weight: bold;
        }

        .leftDiv1 {
            position: relative;
            margin-top: 20px;
        }

        div.newsDiv1 .leftDiv1 .leftDiv2 {
            position: absolute;
            height: 74px;
            bottom: 3px;
            font-size: 20px;
            color: rgb(255, 255, 255);
            background-color: rgba(20, 20, 20, 0.5);
            width: 582px;
            line-height: 74px;
        }

        div.newsDiv1 .leftDiv1 .leftDiv2 .leftH1 {
            padding-left: 15px;
        }

        .leftDiv3 {
            display: inline-block;
            position: relative;
            margin: 5px 5px 0px 0px;
        }

        .leftDiv3 .fontDiv1 {
            position: absolute;
            height: 40px;
            bottom: 3px;
            font-size: 15px;
            color: rgb(255, 255, 255);
            background-color: rgba(20, 20, 20, 0.5);

        }

        .leftDiv4 {
            display: inline-block;
            position: relative;
        }

        .leftDiv4 .fontDiv2 {
            position: absolute;
            height: 40px;
            width: 286px;
            bottom: 3px;
            font-size: 15px;
            color: rgb(255, 255, 255);
            background-color: rgba(20, 20, 20, 0.5);
            line-height: 40px;
        }

        .leftDiv4 .leftH3 {
            padding-left: 15px;
        }

        #leftContentDiv a {
            text-decoration: none;
            color: aliceblue;
        }

        /*右边栏目的内容修饰*/
        #rightContentDiv {
            width: 582px;
            height: 582px;
            display: inline-block;
            position: relative;
            margin: 0;


        }

        #rightContentDiv a.right1 {
            padding-right: px;
            font-size: 20px;
            font-weight: bold;
            color: rgb(44, 44, 207);
            position: absolute;
            right: 10px;
            text-decoration: none;
        }

        #rightContentDiv li {
            list-style-type: none;
            position: relative;
        }

        #rightContentDiv li .rightLiDiv p {
            display: inline-block;
            position: absolute;
            top: 38px;
            left: 230px;
        }

        #rightContentDiv span {
            font-size: 18px;
            border: red solid 3px;
            border-radius: 60px 70px 80px 90px;
            background-color: coral;
            position: absolute;
            left: 249px;
            top: 0px;
        }

        #rightContentDiv li .rightLiDiv p a {
            text-decoration: none;
        }
    </style>

</head>

<body>
    <div class="newsDiv1">
        <div id="leftContentDiv">
            <span>新闻速递</span>
            <div class="leftDiv1">
                <a href="https://www.beijing2022.cn/wog.htm?cmsid=EYS2022020800632400"><img
                        src="./Olympic Games source/news1.jpg"></a>

                <div class="leftDiv2">
                    <a class="leftH1"
                        href="https://www.beijing2022.cn/wog.htm?cmsid=EYS2022020800632400">中国代表团在35个小项实现参赛“零的突破”</a>

                </div>

            </div>
            <div class="leftDiv3">
                <a href="https://www.beijing2022.cn/wog.htm?cmsid=EYS2022020900753000"><img
                        src="./Olympic Games source/news7.jpg">
                </a>
                <div class="fontDiv1">
                    <a class="leftH2"
                        href="https://www.beijing2022.cn/wog.htm?cmsid=EYS2022020900753000">西班牙单板滑雪运动员：自己设计雪板 梦想奥运金牌</a>
                </div>

            </div>
            <div class="leftDiv4">
                <a href="https://www.beijing2022.cn/wog.htm?cmsid=EYS2022020900754200"><img
                        src="./Olympic Games source/news8.jpg">
                </a>
                <div class="fontDiv2">
                    <a class="leftH3" href="https://www.beijing2022.cn/wog.htm?cmsid=EYS2022020900754200">圆梦北京
                        老将卡尔潸然落泪</a>
                </div>

            </div>

        </div>
        <div id="rightContentDiv">
            <a class="right1" href="https://www.beijing2022.cn/cn/presscentre/headlines.htm">去看更多 &gt;></a>
            <ul class="ulCls">
                <li>
                    <a href="https://www.beijing2022.cn/wog.htm?cmsid=EYS2022021000542400"> <img
                            src="./Olympic Games source/news2.jpg"></a>
                    <div class="rightLiDiv">
                        <span>焦点新闻</span>
                        <p><a
                                href="https://www.beijing2022.cn/wog.htm?cmsid=EYS2022021000542400">国际奥委会点赞“双奥场馆”：汇集奥运可持续的优点</a>
                        </p>
                    </div>
                </li>
                <li>
                    <a href="https://www.beijing2022.cn/wog.htm?cmsid=EYS2022020900755400"> <img
                            src="./Olympic Games source/news6.jpg"></a>
                    <div class="rightLiDiv">
                        <span>焦点新闻</span>
                        <p><a
                                href="https://www.beijing2022.cn/wog.htm?cmsid=EYS2022020900755400">如何防止运动员失误跌落悬崖？国家高山滑雪中心安装有“红色长城”</a>
                        </p>
                    </div>

                </li>
                <li>
                    <a href="https://www.beijing2022.cn/wog.htm?cmsid=20220210005418"> <img
                            src="./Olympic Games source/news5.jpg"></a>
                    <div class="rightLiDiv">
                        <span style="color: rgb(252, 253, 252);background-color: rgb(60, 131, 212);">官方发布</span>
                        <p><a href="https://www.beijing2022.cn/wog.htm?cmsid=20220210005418">2月9日冬奥新冠防疫情况</a></p>
                    </div>

                </li>

                <li>
                    <a href="https://www.beijing2022.cn/wog.htm?cmsid=20220209008060"><img
                            src="./Olympic Games source/news4.jpg"></a>
                    <div class="rightLiDiv">
                        <span>焦点新闻</span>
                        <p><a href="https://www.beijing2022.cn/wog.htm?cmsid=20220209008060">高山滑雪生命守护者：不动如山，迅疾似火</a></p>
                    </div>

                </li>


                </li>

            </ul>

        </div>

</body>

</html>
