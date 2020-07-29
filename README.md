# Girls-Frontline
少女前线Live2D模型
让模型在网页上显示，只需加上这段代码就可以可以让小姐姐在你的网页上显示了
更多详情请访问：https://kaiyu.xyz/


<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>凯裕学习室</title>
</head>

<body>

<script src="https://eqcn.ajz.miesnfu.com/wp-content/plugins/wp-3d-pony/live2dw/lib/L2Dwidget.min.js"></script>
<script>
    L2Dwidget.init({
        "model": {
　　　　　　　//jsonpath控制显示模型
            jsonPath:"destroy/model.json" },//模型位置
        "display": {
            "position": "right", //模型居左居右位置//Left是左边//right是右边
            "width": 250,  //宽度
            "height": 480, //高度
            "hOffset": -10,  //水平
            "vOffset": -70,  //垂直
        },
        "mobile": {
            "show": true,
        },
        "react": {
            "opacityDefault": 1,//不透明度，可调
            "opacityOnHover": 0.2
        }
    });
</script>   

</body>
</html>
