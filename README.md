# 项目临存projectTemp

```
<!doctype html>
<html lang="en">
<!--[if IE 9 ]>
<html  lang="en" class="ie9">
<![endif]-->
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0" />
    <meta name="format-detection" content="telephone=no">
    <meta charset="UTF-8">
    <title>驾驶仓</title>
    <!-- CSS -->
    <link rel="stylesheet" href="css/bootstrap.min.css">
    <link rel="stylesheet" href="css/animate.min.css">
    <link rel="stylesheet" href="css/font-awesome.min.css">
    <link rel="stylesheet" href="css/form.css">
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" href="css/icons.css">
    <link rel="stylesheet" href="css/generics.css">
    <link rel="stylesheet" href="css/bstable/bootstrap-table.css">
    <link rel="stylesheet" href="css/bstable/bootstrap-table-self.css">
</head>
<body>
<header id="header" class="media">
    <a href="" id="menu-toggle"></a>
    <a class="logo pull-left" href="index.html">
        <img src="images/logo.png" alt="logo">
    </a>
    <div class="media-body">
        <div class="media" id="top-menu">
            <div class="pull-left tm-icon">
                <a data-drawer="messages" class="drawer-toggle" href="">
                    <i class="sa-top-message"></i>
                    <span>时间回溯</span>
                </a>
            </div>
            <div class="pull-left tm-icon">
                <a data-drawer="notifications" class="drawer-toggle" href="">
                    <i class="sa-top-updates"></i>
                    <span>帮助</span>
                </a>
            </div>
            <div id="time" class="pull-right">
                <span id="hours"></span>
                :
                <span id="min"></span>
                :
                <span id="sec"></span>
            </div>
            <div class="media-body">
                <input type="text" class="main-search">
            </div>
        </div>
    </div>
</header>
<div class="clearfix"></div>
<section id="main" class="p-relative" role="main">
    <!-- Sidebar -->
    <aside id="sidebar">
        <!-- Side Menu -->
        <ul class="list-unstyled side-menu">
            <li>
                <a class="sa-side-home" href="index.html">
                    <span class="menu-item">首页</span>
                </a>
            </li>
        </ul>
    </aside>
    <!-- Content -->
    <section id="content" class="container">
        <!-- Messages Drawer时间回溯 -->
        <div id="messages" class="tile drawer animated">
            <div class="listview narrow">
                <div class="media">
                    <a href="">时间回溯</a>
                    <span class="drawer-close">&times;</span>
                </div>
                <div class="overflow" style="height: 254px">
                    <div class="media">
                        <div class="pull-left">
                            <img width="40" src="img/profile-pics/1.jpg" alt="">
                        </div>
                        <div class="media-body">
                            <small class="text-muted">Nadin Jackson - 2 Hours ago</small><br>
                            <a class="t-overflow" href="">Mauris consectetur urna nec tempor adipiscing. Proin sit amet nisi ligula. Sed eu adipiscing lectus</a>
                        </div>
                    </div>
                    <div class="media">
                        <div class="pull-left">
                            <img width="40" src="img/profile-pics/2.jpg" alt="">
                        </div>
                        <div class="media-body">
                            <small class="text-muted">David Villa - 5 Hours ago</small><br>
                            <a class="t-overflow" href="">Suspendisse in purus ut nibh placerat Cras pulvinar euismod nunc quis gravida. Suspendisse pharetra</a>
                        </div>
                    </div>
                    <div class="media">
                        <div class="pull-left">
                            <img width="40" src="img/profile-pics/3.jpg" alt="">
                        </div>
                        <div class="media-body">
                            <small class="text-muted">Harris worgon - On 15/12/2013</small><br>
                            <a class="t-overflow" href="">Maecenas venenatis enim condimentum ultrices fringilla. Nulla eget libero rhoncus, bibendum diam eleifend, vulputate mi. Fusce non nibh pulvinar, ornare turpis id</a>
                        </div>
                    </div>
                    <div class="media">
                        <div class="pull-left">
                            <img width="40" src="img/profile-pics/4.jpg" alt="">
                        </div>
                        <div class="media-body">
                            <small class="text-muted">Mitch Bradberry - On 14/12/2013</small><br>
                            <a class="t-overflow" href="">Phasellus interdum felis enim, eu bibendum ipsum tristique vitae. Phasellus feugiat massa orci, sed viverra felis aliquet quis. Curabitur vel blandit odio. Vestibulum sagittis quis sem sit amet tristique.</a>
                        </div>
                    </div>
                    <div class="media">
                        <div class="pull-left">
                            <img width="40" src="img/profile-pics/1.jpg" alt="">
                        </div>
                        <div class="media-body">
                            <small class="text-muted">Nadin Jackson - On 15/12/2013</small><br>
                            <a class="t-overflow" href="">Ipsum wintoo consectetur urna nec tempor adipiscing. Proin sit amet nisi ligula. Sed eu adipiscing lectus</a>
                        </div>
                    </div>
                    <div class="media">
                        <div class="pull-left">
                            <img width="40" src="img/profile-pics/2.jpg" alt="">
                        </div>
                        <div class="media-body">
                            <small class="text-muted">David Villa - On 16/12/2013</small><br>
                            <a class="t-overflow" href="">Suspendisse in purus ut nibh placerat Cras pulvinar euismod nunc quis gravida. Suspendisse pharetra</a>
                        </div>
                    </div>
                    <div class="media">
                        <div class="pull-left">
                            <img width="40" src="img/profile-pics/3.jpg" alt="">
                        </div>
                        <div class="media-body">
                            <small class="text-muted">Harris worgon - On 17/12/2013</small><br>
                            <a class="t-overflow" href="">Maecenas venenatis enim condimentum ultrices fringilla. Nulla eget libero rhoncus, bibendum diam eleifend, vulputate mi. Fusce non nibh pulvinar, ornare turpis id</a>
                        </div>
                    </div>
                    <div class="media">
                        <div class="pull-left">
                            <img width="40" src="img/profile-pics/4.jpg" alt="">
                        </div>
                        <div class="media-body">
                            <small class="text-muted">Mitch Bradberry - On 18/12/2013</small><br>
                            <a class="t-overflow" href="">Phasellus interdum felis enim, eu bibendum ipsum tristique vitae. Phasellus feugiat massa orci, sed viverra felis aliquet quis. Curabitur vel blandit odio. Vestibulum sagittis quis sem sit amet tristique.</a>
                        </div>
                    </div>
                    <div class="media">
                        <div class="pull-left">
                            <img width="40" src="img/profile-pics/5.jpg" alt="">
                        </div>
                        <div class="media-body">
                            <small class="text-muted">Wendy Mitchell - On 19/12/2013</small><br>
                            <a class="t-overflow" href="">Integer a eros dapibus, vehicula quam accumsan, tincidunt purus</a>
                        </div>
                    </div>
                </div>
                <div class="media text-center whiter l-100">
                    <a href=""><small>VIEW ALL</small></a>
                </div>
            </div>
        </div>
        <!-- Notification Drawer帮助 -->
        <div id="notifications" class="tile drawer animated">
            <div class="listview narrow">
                <div class="media">
                    <a href="">帮助</a>
                    <span class="drawer-close">&times;</span>
                </div>
                <div class="overflow" style="height: 254px">
                    <div class="media">
                        <div class="pull-left">
                            <img width="40" src="img/profile-pics/1.jpg" alt="">
                        </div>
                        <div class="media-body">
                            <small class="text-muted">Nadin Jackson - 2 Hours ago</small><br>
                            <a class="t-overflow" href="">Mauris consectetur urna nec tempor adipiscing. Proin sit amet nisi ligula. Sed eu adipiscing lectus</a>
                        </div>
                    </div>
                    <div class="media">
                        <div class="pull-left">
                            <img width="40" src="img/profile-pics/2.jpg" alt="">
                        </div>
                        <div class="media-body">
                            <small class="text-muted">David Villa - 5 Hours ago</small><br>
                            <a class="t-overflow" href="">Suspendisse in purus ut nibh placerat Cras pulvinar euismod nunc quis gravida. Suspendisse pharetra</a>
                        </div>
                    </div>
                    <div class="media">
                        <div class="pull-left">
                            <img width="40" src="img/profile-pics/3.jpg" alt="">
                        </div>
                        <div class="media-body">
                            <small class="text-muted">Harris worgon - On 15/12/2013</small><br>
                            <a class="t-overflow" href="">Maecenas venenatis enim condimentum ultrices fringilla. Nulla eget libero rhoncus, bibendum diam eleifend, vulputate mi. Fusce non nibh pulvinar, ornare turpis id</a>
                        </div>
                    </div>
                    <div class="media">
                        <div class="pull-left">
                            <img width="40" src="img/profile-pics/4.jpg" alt="">
                        </div>
                        <div class="media-body">
                            <small class="text-muted">Mitch Bradberry - On 14/12/2013</small><br>
                            <a class="t-overflow" href="">Phasellus interdum felis enim, eu bibendum ipsum tristique vitae. Phasellus feugiat massa orci, sed viverra felis aliquet quis. Curabitur vel blandit odio. Vestibulum sagittis quis sem sit amet tristique.</a>
                        </div>
                    </div>
                    <div class="media">
                        <div class="pull-left">
                            <img width="40" src="img/profile-pics/1.jpg" alt="">
                        </div>
                        <div class="media-body">
                            <small class="text-muted">Nadin Jackson - On 15/12/2013</small><br>
                            <a class="t-overflow" href="">Ipsum wintoo consectetur urna nec tempor adipiscing. Proin sit amet nisi ligula. Sed eu adipiscing lectus</a>
                        </div>
                    </div>
                    <div class="media">
                        <div class="pull-left">
                            <img width="40" src="img/profile-pics/2.jpg" alt="">
                        </div>
                        <div class="media-body">
                            <small class="text-muted">David Villa - On 16/12/2013</small><br>
                            <a class="t-overflow" href="">Suspendisse in purus ut nibh placerat Cras pulvinar euismod nunc quis gravida. Suspendisse pharetra</a>
                        </div>
                    </div>
                </div>
                <div class="media text-center whiter l-100">
                    <a href=""><small>VIEW ALL</small></a>
                </div>
            </div>
        </div>


        <!-- Breadcrumb -->
        <div class="block-area">
            <!--<h3 class="block-title">账号管理</h3>-->
            <div class="table-responsive overflow">
                <!--      <div id="btnAddRemove">
                          <button class="btn btn-default" id="addtable4Row">
                              <span>新增</span>
                              <span class="glyphicon glyphicon-plus"></span>
                          </button>
                          <div class="modal fade in" id="addtableRow-modal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true"  data-backdrop="static">
                              <div class="modal-dialog">
                                  <div class="modal-content" style="background: #000;">
                                      <div class="modal-header">
                                          <button type="button" class="close" data-dismiss="modal" aria-hidden="true">
                                              &times;
                                          </button>
                                          <h4 class="modal-title">
                                              增加行
                                          </h4>
                                      </div>
                                      <div class="modal-body">
                                          <div class="form-horizontal">
                                          </div>
                                      </div>
                                      <div class="modal-footer">
                                          <button type="button" class="btn btn-default" data-dismiss="modal">关闭
                                          </button>
                                          <button type="button" class="btn btn-primary footer-btn" id="btn-addtableRow">
                                              提交更改
                                          </button>
                                      </div>
                                  </div>
                              </div>
                          </div>
                          <div class="modal fade in" id="changetableRow-modal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true"  data-backdrop="static">
                              <div class="modal-dialog">
                                  <div class="modal-content" style="background: #000;">
                                      <div class="modal-header">
                                          <button type="button" class="close" data-dismiss="modal" aria-hidden="true">
                                              &times;
                                          </button>
                                          <h4 class="modal-title">
                                              更改行内容
                                          </h4>
                                      </div>
                                      <div class="modal-body">
                                          <div class="form-horizontal">
                                          </div>
                                      </div>
                                      <div class="modal-footer">
                                          <button type="button" class="btn btn-default" data-dismiss="modal">关闭
                                          </button>
                                          <button type="button" class="btn btn-primary footer-btn" id="btn-changetableRow">
                                              提交更改
                                          </button>
                                      </div>
                                  </div>
                              </div>
                          </div>
                          <div class="modal fade in" id="Confirm-modal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true"  data-backdrop="static">
                              <div class="modal-dialog">
                                  <div class="modal-content" style="background: #000;">
                                      <div class="modal-header">
                                          <button type="button" class="close" data-dismiss="modal" aria-hidden="true">
                                              &times;
                                          </button>
                                          <h4 class="modal-title">
                                              操作
                                          </h4>
                                      </div>
                                      <div class="modal-body">
                                          确定删除此行吗？
                                      </div>
                                      <div class="modal-footer">
                                          <button type="button" class="btn btn-default" data-dismiss="modal">关闭
                                          </button>
                                          <button type="button" class="btn btn-primary footer-btn" data-dismiss="modal" id="btn-ConfirmdelRow">
                                              提交更改
                                          </button>
                                      </div>
                                  </div>
                              </div>
                          </div>
                      </div>-->
                <table id="table7">
                </table>
            </div>
        </div>

    </section>
    <!-- Older IE Message -->
    <!--[if lt IE 9]>
    <div class="ie-block">
        <h1 class="Ops">抱歉！</h1>
        <p>您正在使用一个过时的Internet Explorer版本，升级到以下任何Web浏览器，以便访问该网站的最大功能。 </p>
        <ul class="browsers">
            <li>
                <a href="http://www.google.cn/intl/zh-CN/chrome/browser/desktop/index.html">
                    <img src="img/browsers/chrome.png" alt="">
                    <div>Google Chrome</div>
                </a>
            </li>
            <li>
                <a href="http://www.firefox.com.cn/">
                    <img src="img/browsers/firefox.png" alt="">
                    <div>Mozilla Firefox</div>
                </a>
            </li>
            <li>
                <a href="http://www.oupeng.com/download">
                    <img src="img/browsers/opera.png" alt="">
                    <div>Opera</div>
                </a>
            </li>
            <li>
                <a href="https://www.apple.com/cn/safari/">
                    <img src="img/browsers/safari.png" alt="">
                    <div>Safari</div>
                </a>
            </li>
            <li>
                <a href="https://support.microsoft.com/zh-cn/help/17621/internet-explorer-downloads">
                    <img src="img/browsers/ie.png" alt="">
                    <div>Internet Explorer(New)</div>
                </a>
            </li>
        </ul>
        <p>升级你的浏览器更安全和更快的网络体验。 <br/>感谢你的支持...</p>
    </div>
    <![endif]-->
</section>
</body>
</html>
<!-- jQuery -->
<script src="js/jquery.min.js"></script> <!-- jQuery Library -->
<!-- Bootstrap -->
<script src="js/bootstrap.min.js"></script>
<!-- Bootstrap-table -->
<script src="js/bstable/bootstrap-table.js"></script>
<script src="js/bstable/bootstrap-table-zh-CN.js"></script>
<script src="js/functions.js"></script>
<script src="js/changebgsave.js"></script>
<script>
    $(function(){
        $.ajax({
            url:"/serverManagement/getServerSideListColumn.do",
            type:"post",
            data:"",
            dataType:"json",
            success:function(data){
//                console.log(data);
//                console.log(data.length);
                var columnsArry = [];
                data.forEach(function(item){
                    var colObjet = {
//                        field:"name",
                        title:item.columnzh,
                        sortable:true
                    };
                    columnsArry.push(colObjet);
                });
//                console.log(columnsArry);
                $("#table7").bootstrapTable({
                    toggle:"table",
                    url:"/serverManagement/getServerSideListColumn.do",
                    toolbar:"#btnAddRemove",
                    height:"360",
                    pagination:true,
                    showColumns:true,
                    columns:columnsArry
                });
            }
        });



        $(window).load(function(){

//            console.log( $("#table7").parent());
//            console.log( $("#table7").parent().parent());
//            console.log( $("#table7").parent().parent().parent());
//            console.log( $("#table7").parent().parent().parent().prev());
//            var label = $("#table7").parent().parent().parent().prev().find("li[role='menuitem']");
//            console.log(label);
//            console.log(label.length);



//            console.log($("#table7").parent().hasClass("fixed-table-body"));
            setTimeout(function(){
                /*
                 $('button[aria-label="columns"]').trigger("click");
                 $('button[aria-label="columns"]').click();*/
//                console.log(  $('li[role="menuitem"]').find('input[type="checkbox"]').length);
                var textArry = [];
                for(var i =0;i<$('li[role="menuitem"]').find('input[type="checkbox"]').length;i++){
//                    $('li[role="menuitem"]').find('input[type="checkbox"]').eq(i).click();
                    textArry.push($.trim($('li[role="menuitem"]').find('input[type="checkbox"]').eq(i).parents().text()));
//                    console.log($.trim($('li[role="menuitem"]').find('input[type="checkbox"]').eq(i).parents().text()));
                }
//                console.log(textArry.length);
                $.ajax({
                    url:"/serverManagement/getServerSideUserListColumn.do",
                    type:"post",
                    data:"",
                    dataType:"json",
                    success:function(userdata){
//                        for(var i =0;i<$('li[role="menuitem"]').find('input[type="checkbox"]').length;i++){
//                            $('li[role="menuitem"]').find('input[type="checkbox"]').eq(i).attr("checked",false);
//                            $('li[role="menuitem"]').find('input[type="checkbox"]').eq(i).click();
//
//                        }
                        userdata.forEach(function(usertem){
//                            if($.trim($('li[role="menuitem"]').find('input[type="checkbox"]').eq(i).parents().text())==usertem.columnzh){
//                                $('li[role="menuitem"]').find('input[type="checkbox"]').eq(i).attr("checked","checked");
//                                $('li[role="menuitem"]').find('input[type="checkbox"]').eq(i).click();
//                            }else {
//                                    $('li[role="menuitem"]').find('input[type="checkbox"]').eq(i).attr("checked",false);
//                                    $('li[role="menuitem"]').find('input[type="checkbox"]').eq(i).click();
//                            }
                            textArry.forEach(function(textem,index){
                                if(usertem.columnzh==textem){
                                    textArry.splice(index,1);
                                }
                            })
                        });
//                        console.log(textArry);
                        for(var i =0;i<$('li[role="menuitem"]').find('input[type="checkbox"]').length;i++){
//                    $('li[role="menuitem"]').find('input[type="checkbox"]').eq(i).click();
                            for(var j=0;j<textArry.length;j++){
                                if($.trim($('li[role="menuitem"]').find('input[type="checkbox"]').eq(i).parents().text())==textArry[j]){
                                    $('li[role="menuitem"]').find('input[type="checkbox"]').eq(i).attr("checked",false);
                                    $('li[role="menuitem"]').find('input[type="checkbox"]').eq(i).click();
                                }
                            }
                        }
                    }
                });
            },100)
        });


        $(document).on('click','button[data-toggle="dropdown"]',function(){
//            $(this).click();
//            console.log($(this).parent().hasClass("open"));
//            if($(this).parent().hasClass("open")){
//                //如果这个CLASS存在则返回给后台
//                console.log($(this).siblings(".dropdown-menu").find('input[value="0"]').attr("checked"));
//            }else {
//                console.log(1);
//                $(this).siblings(".dropdown-menu").find('input[value="0"]').click();
//            }

            $(this).siblings(".dropdown-menu").find("input[type='checkbox']").click(function(){
//                console.log($(this).parent().parent().parent().find("input[type='checkbox']").length);
//                console.log($.trim($(this).parent().text()));
//                console.log($(this).attr("checked"));
                if($(this).attr("checked")){
                    $(this).attr("checked",false)
                }else {
                    $(this).attr("checked","checked")
                }
                var length = $(this).parent().parent().parent().find("input[type='checkbox']").length,
                        textArr = [];
                for(var i= 0;i<length;i++){
                    if($(this).parent().parent().parent().find("input[type='checkbox']").eq(i).attr("checked")){
                        textArr.push($.trim($(this).parent().parent().parent().find("input[type='checkbox']").eq(i).parent().text()));
                    }else {
//                        console.log($.trim($(this).parent().parent().parent().find("input[type='checkbox']").eq(i).parent().text()))
                    }
                }
//                console.log(textArr);



                var text = $.trim($(this).parent().text()),
                        idArry = [];
                $.ajax({
                    url:"/serverManagement/getServerSideListColumn.do",
                    type:"post",
                    data:"",
                    dataType:"json",
                    success:function(data){
                        data.forEach(function(item){
                            textArr.forEach(function(textem){
                                if(item.columnzh==textem){
                                    idArry.push(item.id);
                                }
                            });
                        });
//                        console.log(idArry);
                        $.ajax({
                            url:"/userConfigure/saveUserListColumn.do ",
                            type:"post",
                            data:{
                                columnIds:String(idArry)
                            },
                            dataType:"text",
                            success:function(data){
                                console.log(data);
                            }
                        })
                    }
                })
            })
        });




//        $('button[data-toggle="dropdown"]').on("click",function(){
//            console.log(1);
//        });
//        $('button[data-toggle="dropdown"]').click(function(){
//            console.log(1);
//            console.log($(this).parent().hasClass("open"));
//            if($(this).parent().hasClass("open")){
//                //如果这个CLASS存在则返回给后台
//                console.log($(this).siblings(".dropdown-menu").find('input[value="0"]').attr("checked"));
//            }else {
//                $(this).siblings(".dropdown-menu").find('input[value="0"]').click();
//            }
//        });

//        $("#table7").bootstrapTable("uncheckBy", {field:"name", values:["服务端编号","服务端名称","流量"]});
//        $("#table7").on("uncheckBy",function(params){
//            console.log(params);
//        });
//        $("#table7").bootstrapTable("getVisibleColumns",function(row){
//            console.log(row);
//        })
//        $("#table7").on("getVisibleColumns",function(row){
//            console.log(row);
//        });



//        $('button[aria-label="columns"]').on("click",function(){
//            console.log(1);
//            $("li[rol='menuitem']>label>input[type='checkbox']:eq(0)").click();
//        });






        /*****************左侧图标工具栏************************/
        $.ajax({
            url:"authorizeModuleController/getFindAll.do",
            type:"post",
            data:"",
            dataType:"json",
            success:function(data){
                data.forEach(function(item,index){
                    var className;
                    switch (item.namezh){
                        case "网络":
                            className = "sa-side-network";
                            break;
                        case "主机":
                            className = "sa-side-ip";
                            break;
                        case "自定义应用":
                            className = "sa-side-custom";
                            break;
                        case "WEB服务":
                            className = "sa-side-web";
                            break;
                        case "ORACLE服务":
                            className = "sa-side-oracle";
                            break;
                        case "MYSQL服务":
                            className = "sa-side-mysql";
                            break;
                        case "SQLSERVER服务":
                            className = "sa-side-sqlserver";
                            break;
                        case "URL交易":
                            className = "sa-side-url";
                            break;
                        case "报文交易":
                            className = "sa-side-baowenJy";
                            break;
                        case "观察点":
                            className = "sa-side-observationPoint";
                            break;
                        case "用户端":
                            className = "sa-side-userSide";
                            break;
                        case "服务端":
                            className = "sa-side-serverSide";
                            break;
                        default:
                            className = "sa-side-home";
                            break;
                    }
                    if(item.namezh=="观察点"||item.namezh=="服务端"||item.namezh=="用户端"){
                        if(item.namezh=="观察点"){
                            var ul = $( '<ul class="list-unstyled menu-item overflowYs">' +
                                    '</ul>');
                            $.ajax({
                                url:"watchpointController/getFindAll.do",
                                type:"post",
                                data:"",
                                dataType:"json",
                                success:function(data){
                                    data.forEach(function(item,index){
                                        $(ul).append('<li class="cursor" style="font-weight: 600;">'+item.name+'</li>')
                                    })
                                }
                            });
                            var li = $('<li class="dropdown">' +
                                    '<a class="'+className+'" href="'+className.split("-")[2]+'.html">'+
                                    '<span class="menu-item">'+item.namezh+ '管理与设置</span>'+
                                    '</a>'+
                                    '</li>');
                            $(li).append(ul);
                            $("#sidebar>ul").on("click",'.'+className+'+.overflowYs>.cursor',function(){
                                console.log($(this).text());
                                if($(this).text()){
                                    document.cookie ="tValue = "+$(this).text();
                                    location.href = "testTable2.html";
                                }
                            });
                        }else if(item.namezh=="服务端") {
                            var ul = $( '<ul class="list-unstyled menu-item overflowYs">' +
                                    '</ul>');
                            $.ajax({
                                url:"/serverManagement/getAllServerSide.do",
                                type:"post",
                                data:"",
                                dataType:"json",
                                success:function(data){
                                    data.forEach(function(item,index){
                                        $(ul).append('<li class="cursor" style="font-weight: 600;">'+item.name+'</li>')
                                    })
                                }
                            });
                            var li = $('<li class="dropdown">' +
                                    '<a class="'+className+'" href="'+className.split("-")[2]+'.html">'+
                                    '<span class="menu-item">'+item.namezh+ '管理与设置</span>'+
                                    '</a>'+
                                    '</li>');
                            $(li).append(ul);
                            $("#sidebar>ul").on("click",'.'+className+'+.overflowYs>.cursor',function(){
                                console.log("222success");
                            });
                        }else {
                            //用户端
                            var ul = $( '<ul class="list-unstyled menu-item overflowYs">' +
                                    '</ul>');
                            $.ajax({
                                url:"/client/getClient.do?moduleId=11",
                                type:"post",
                                data:"",
                                dataType:"json",
                                success:function(data){
                                    data.forEach(function(item,index){
                                        $(ul).append('<li class="cursor" style="font-weight: 600;">'+item.name+'</li>')
                                    })
                                }
                            });
                            var li = $('<li class="dropdown">' +
                                    '<a class="'+className+'" href="'+className.split("-")[2]+'.html">'+
                                    '<span class="menu-item">'+item.namezh+ '管理与设置</span>'+
                                    '</a>'+
                                    '</li>');
                            $(li).append(ul);
                            $("#sidebar>ul").on("click",'.'+className+'+.overflowYs>.cursor',function(){
                                console.log("222success");
                            });
                        }
                    }else {
                        var li = $('<li>' +
                                '<a class="'+className+'" href="#">'+
                                '<span class="menu-item">'+item.namezh+'</span>'+
                                '</a>'+
                                '</li>');
                    }
                    $("#sidebar .side-menu").append(li);
                })
            }
        })
    });
    //    $(function(){
    //        window.onload = function(){
    //            $(document).siblings(".dropdown-menu").find('input[value="1"]').click();
    //        }
    //    })
</script>
```

## 20170920 del code temp save

```
    $(function(){
        var columnsArry = [];
        $.ajax({
            url:"/watchpointController/getWatchpointListColumn.do",
            type:"post",
            async: false,
            data:"",
            dataType:"json",
            success:function(data){
                var allTitle = [];
                data.forEach(function(title){
                    var colObjet = {
                        title:title.columnzh,
                        sortable:true
                    };
                    allTitle.push(title.columnzh);
                    columnsArry.push(colObjet);
                });
                $.ajax({
                    url:"/watchpointController/getWatchpointUserListColumn.do",
                    type:"post",
                    async:false,
                    data:"",
                    dataType:"json",
                    success:function(udata){
                        var userTitle = [];
                        udata.forEach(function(title){
                            userTitle.push(title.columnzh)
                        });
                        for(var i=0;i<allTitle.length;i++){
                            for(var j=0;j<userTitle.length;j++){
                                if(allTitle[i]==userTitle[j]){
                                    allTitle.splice(i,1)
                                }
                            }
                        }
                        for(var i=0;i<columnsArry.length;i++){
                            for(var j=0;j<allTitle.length;j++){
                                if(columnsArry[i].title==allTitle[j]){
                                    columnsArry[i].visible=false;
                                }
                            }
                        }
                        $("#table7").bootstrapTable({
                            toggle:"table",
                            url:"/watchpointController/getWatchpointListColumn.do",
                            toolbar:"#btnAddRemove",
                            height:"360",
                            pagination:true,
                            showColumns:true,
                            columns:columnsArry
                        });
                    }
                });
            }
        });
        /*-------------用户操作列的消失隐藏--------------------------*/
        $(document).on('click','button[data-toggle="dropdown"]',function(){
            if($(this).attr("aria-label")=="columns"){
                $(this).siblings(".dropdown-menu").find("input[type='checkbox']").click(function(){
                    if($(this).attr("checked")){
                        $(this).attr("checked",false)
                    }else {
                        $(this).attr("checked",true)
                    }
                    var length = $(this).parent().parent().parent().find("input[type='checkbox']").length,
                            textArr = [];
                    for(var i= 0;i<length;i++){
                        if($(this).parent().parent().parent().find("input[type='checkbox']").eq(i).attr("checked")){
                            textArr.push($.trim($(this).parent().parent().parent().find("input[type='checkbox']").eq(i).parent().text()));
                        }
                    }
                    var idArry = [];
                    $.ajax({
                        url:"/watchpointController/getWatchpointListColumn.do",
                        type:"post",
                        data:"",
                        dataType:"json",
                        success:function(data){
                            data.forEach(function(item){
                                textArr.forEach(function(textem){
                                    if(item.columnzh==textem){
                                        idArry.push(item.id);
                                    }
                                });
                            });
                            $.ajax({
                                url:"/userConfigure/saveUserListColumn.do ",
                                type:"post",
                                data:{
                                    typeId:10,
                                    columnIds:String(idArry)
                                },
                                dataType:"text",
                                success:function(data){
                                    console.log(data);
                                }
                            })
                        }
                    })
                })
            }
        });
        /*****************左侧图标工具栏************************/
        $.ajax({
            url:"authorizeModuleController/getFindAll.do",
            type:"post",
            data:"",
            dataType:"json",
            success:function(data){
                data.forEach(function(item,index){
                    var className;
                    switch (item.namezh){
                        case "网络":
                            className = "sa-side-network";
                            break;
                        case "主机":
                            className = "sa-side-ip";
                            break;
                        case "自定义应用":
                            className = "sa-side-custom";
                            break;
                        case "WEB服务":
                            className = "sa-side-web";
                            break;
                        case "ORACLE服务":
                            className = "sa-side-oracle";
                            break;
                        case "MYSQL服务":
                            className = "sa-side-mysql";
                            break;
                        case "SQLSERVER服务":
                            className = "sa-side-sqlserver";
                            break;
                        case "URL交易":
                            className = "sa-side-url";
                            break;
                        case "报文交易":
                            className = "sa-side-baowenJy";
                            break;
                        case "观察点":
                            className = "sa-side-observationPoint";
                            break;
                        case "用户端":
                            className = "sa-side-userSide";
                            break;
                        case "服务端":
                            className = "sa-side-serverSide";
                            break;
                        default:
                            className = "sa-side-home";
                            break;
                    }
                    if(item.namezh=="观察点"||item.namezh=="服务端"||item.namezh=="用户端"){
                        if(item.namezh=="观察点"){
                            var ul = $( '<ul class="list-unstyled menu-item overflowYs">' +
                                    '</ul>');
                            $.ajax({
                                url:"watchpointController/getFindAll.do",
                                type:"post",
                                data:"",
                                dataType:"json",
                                success:function(data){
                                    data.forEach(function(item,index){
                                        $(ul).append('<li class="cursor" style="font-weight: 600;">'+item.name+'</li>')
                                    })
                                }
                            });
                            var li = $('<li class="dropdown">' +
                                    '<a class="'+className+'" href="'+className.split("-")[2]+'.html">'+
                                    '<span class="menu-item">'+item.namezh+ '管理与设置</span>'+
                                    '</a>'+
                                    '</li>');
                            $(li).append(ul);
                            $("#sidebar>ul").on("click",'.'+className+'+.overflowYs>.cursor',function(){
                                console.log($(this).text());
                                if($(this).text()){
                                    document.cookie ="tValue = "+$(this).text();
                                    location.href = "observationPointkpi.html";
                                }
                            });
                        }else if(item.namezh=="服务端") {
                            var ul = $( '<ul class="list-unstyled menu-item overflowYs">' +
                                    '</ul>');
                            $.ajax({
                                url:"/serverManagement/getAllServerSide.do",
                                type:"post",
                                data:"",
                                dataType:"json",
                                success:function(data){
                                    data.forEach(function(item,index){
                                        $(ul).append('<li class="cursor" style="font-weight: 600;">'+item.name+'</li>')
                                    })
                                }
                            });
                            var li = $('<li class="dropdown">' +
                                    '<a class="'+className+'" href="'+className.split("-")[2]+'.html">'+
                                    '<span class="menu-item">'+item.namezh+ '管理与设置</span>'+
                                    '</a>'+
                                    '</li>');
                            $(li).append(ul);
                            $("#sidebar>ul").on("click",'.'+className+'+.overflowYs>.cursor',function(){
                                console.log("222success");
                                console.log($(this).text());
                                if($(this).text()){
                                    document.cookie ="tValue = "+$(this).text();
                                    location.href = "serverSidekpi.html";
                                }
                            });
                        }else {
                            //用户端
                            var ul = $( '<ul class="list-unstyled menu-item overflowYs">' +
                                    '</ul>');
                            $.ajax({
                                url:"/client/getClient.do?moduleId=11",
                                type:"post",
                                data:"",
                                dataType:"json",
                                success:function(data){
                                    data.forEach(function(item,index){
                                        $(ul).append('<li class="cursor" style="font-weight: 600;">'+item.name+'</li>')
                                    })
                                }
                            });
                            var li = $('<li class="dropdown">' +
                                    '<a class="'+className+'" href="'+className.split("-")[2]+'.html">'+
                                    '<span class="menu-item">'+item.namezh+ '管理与设置</span>'+
                                    '</a>'+
                                    '</li>');
                            $(li).append(ul);
                            $("#sidebar>ul").on("click",'.'+className+'+.overflowYs>.cursor',function(){
                                document.cookie ="tValue = "+$(this).text();
                                location.href = "userSidekpi.html";
                            });
                        }
                    }else {
                        var li = $('<li>' +
                                '<a class="'+className+'" href="#">'+
                                '<span class="menu-item">'+item.namezh+'</span>'+
                                '</a>'+
                                '</li>');
                    }
                    $("#sidebar .side-menu").append(li);
                })
            }
        })
    });
```

###2017/09/22

```
  function temp(){
            $.ajax({
                url:"/watchpointController/getWatchpointUserListColumn.do",
                type:"post",
                data:"",
                dataType:"json",
                success:function(data){
                    var columnsArry = [];
                    data.forEach(function(title){
                        if(title.columnen!="id"){
                            var colObjet = {
                                field:title.columnen,
                                title:title.columnzh,
                                sortable:true,
                                visible:title.checked
                            };
                            columnsArry.push(colObjet);
                        }
                    });
                    $("#table7").bootstrapTable({
                        toggle:"table",
                        toolbar:"#guanchapoint",
                        height:"360",
                        pagination:true,
                        showColumns:true,
                        columns:columnsArry
                    });
                    $.ajax({
//                    url:"/commonController/getNpmListRrdData.do",
                        url:"json/ob.json",
                        type:"post",
                        data:{
                            moduleId:10
                        },
                        dataType:"json",
                        success:function(tdata){
                            $("#table7").bootstrapTable("load",tdata);
                        }
                    })
                }
            });
            /*-------------用户操作列的消失隐藏--------------------------*/
            $(document).on('click','button[data-toggle="dropdown"]',function(){
                if($(this).attr("aria-label")=="columns"){
                    $(this).siblings(".dropdown-menu").find("input[type='checkbox']").click(function(){
                        if($(this).attr("checked")){
                            $(this).attr("checked",false)
                        }else {
                            $(this).attr("checked",true)
                        }
                        var length = $(this).parent().parent().parent().find("input[type='checkbox']").length,
                                textArr = [];
                        for(var i= 0;i<length;i++){
                            if($(this).parent().parent().parent().find("input[type='checkbox']").eq(i).attr("checked")){
                                textArr.push($.trim($(this).parent().parent().parent().find("input[type='checkbox']").eq(i).parent().text()));
                            }
                        }
                        var idArry = [];
                        $.ajax({
                            url:"/watchpointController/getWatchpointUserListColumn.do",
                            type:"post",
                            data:"",
                            dataType:"json",
                            success:function(data){
                                data.forEach(function(item){
                                    textArr.forEach(function(textem){
                                        if(item.columnzh==textem){
                                            idArry.push(item.id);
                                        }
                                    });
                                });
                                $.ajax({
                                    url:"/watchpointController/updateUserListColumn.do",
                                    type:"post",
                                    data:{
                                        typeId:10,
                                        columnIds:String(idArry)
                                    },
                                    dataType:"text",
                                    success:function(data){
                                        console.log(data);
                                    }
                                })
                            }
                        })
                    })
                }
            });

            function modulkpi(userColumnurl,toolbartem,modolkpiurl,tableId,watchPointId,moduleId,starttime,endtime){
                $.ajax({
                    url:userColumnurl,
                    type:"post",
                    data:"",
                    dataType:"json",
                    success:function(data){
                        var columnsArry = [];
                        data.forEach(function(title){
                            if(title.columnen!="id"){
                                var colObjet = {
                                    field:title.columnen,
                                    title:title.columnzh,
                                    sortable:true,
                                    visible:title.checked
                                };
                                columnsArry.push(colObjet);
                            }
                        });
                        $(tableId).bootstrapTable({
                            toggle:"table",
                            toolbar:toolbartem,
                            height:"360",
                            pagination:true,
                            showColumns:true,
                            columns:columnsArry
                        });
                        $.ajax({
//                    url:"/commonController/getNpmListRrdData.do",
                            url:modolkpiurl,
                            type:"post",
                            data:{
                                "moduleId":moduleId,
                                "watchPointId":watchPointId,
                                "starttime":starttime,
                                "endtime":endtime
                            },
                            dataType:"json",
                            success:function(tdata){
                                $(tableId).bootstrapTable("load",tdata);
                            }
                        })
                    }
                });
            }
            function clickColumn(thisElm,userColumnurl,userColumnUpurl,moduleId){
                thisElm.siblings(".dropdown-menu").find("input[type='checkbox']").click(function(){
                    if($(this).attr("checked")){
                        $(this).attr("checked",false)
                    }else {
                        $(this).attr("checked",true)
                    }
                    var length = $(this).parent().parent().parent().find("input[type='checkbox']").length,
                            textArr = [];
                    for(var i= 0;i<length;i++){
                        if($(this).parent().parent().parent().find("input[type='checkbox']").eq(i).attr("checked")){
                            textArr.push($.trim($(this).parent().parent().parent().find("input[type='checkbox']").eq(i).parent().text()));
                        }
                    }
                    var idArry = [];
                    $.ajax({
                        url:userColumnurl,
                        type:"post",
                        data:"",
                        dataType:"json",
                        success:function(data){
                            console.log(data);
                            data.forEach(function(item){
                                textArr.forEach(function(textem){
                                    if(item.columnzh==textem){
                                        idArry.push(item.id);
                                    }
                                });
                            });
                            $.ajax({
                                url:userColumnUpurl,
                                type:"post",
                                data:{
                                    typeId:moduleId,
                                    columnIds:String(idArry)
                                },
                                dataType:"text",
                                success:function(data){
                                    console.log(data);
                                }
                            })
                        }
                    })
                })
            }
        }
        
```


## 临存变量
```
        function fn(rowId){
            if(!wpArry){
                var wpArry = [];
            }
            if(!wpArry.length&&!rowId){
                wpArry.push(1);
            }
            wpArry.splice(0,1,rowId);
          /*  if(!wpArry.length){
                var watchPointId = wpArry.push(rowId);
            }else {
            }*/
            console.log(wpArry);
        }
        fn(5);
        setTimeout(function(){
            fn(10);
        },1000)
```
