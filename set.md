```html
<!doctype html>
<html>
    <head>
        <meta charset="utf-8">
        <title>خانه</title>
        <meta name="generator" content="WYSIWYG Web Builder 17 - https://www.wysiwygwebbuilder.com">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link href="/fontawesome/css/all.css" rel="stylesheet">
        <link href="/css/panisa.css" rel="stylesheet">
        <link href="/css/hover.css" rel="stylesheet">
        <script src="/js/jquery-3.6.0.min.js"></script>
        <script src="/js/wb.panel.min.js"></script>
        <script src="/js/jquery-ui.min.js"></script>
        <script src="/js/wb.parallax.min.js"></script>
        <script src="/js/util.min.js"></script>
        <script src="/js/carousel.min.js"></script>
        <script src="/js/wwb17.min.js"></script>
         <script> 
            $(document).ready(function() {
                $("#headerPanelMenu").panel({
                    animate: true,
                    animationDuration: 200,
                    animationEasing: 'linear',
                    dismissible: true,
                    display: 'overlay',
                    position: 'left',
                    toggle: true
                });
                $("#headerPanelMenu_markup ul li a").click(function(event) {
                    $.panel.hide($("#headerPanelMenu_panel"));
                });
                $('#wb_LayoutGrid5').parallax();
                $('#wb_carouselGrid').parallax();
                $("#Carousel1").bootstrapcarousel({
                    interval: 3000,
                    pause: false
                });
            });
        </script>
    </head>
    <body>
        <div id="wb_header">
            <div id="header">
                <div class="row">
                    <div class="col-1">
                        <div id="wb_headerPanelMenu" style="display:inline-block;width:50px;height:45px;z-index:0;">
                            <a href="#headerPanelMenu_markup" id="headerPanelMenu">
                                <span class="line"></span>
                                <span class="line"></span>
                                <span class="line"></span>
                            </a>
                            <div id="headerPanelMenu_markup">
                                <div id="headerPanelMenu-logo">
                                    <img alt="" src="https://github.com/panisa-cake/panisa-cake.github.io/raw/main/images/log-d-500px.png">
                                </div>
                                <ul role="menu">
                                    <li role="menuitem">
                                        <a href="#home" class="nav-link">
                                            <i class="fas fa-home fa-fw"></i>
                                            <span> خانه </span>
                                        </a>
                                    </li>
                                    <li role="menuitem">
                                        <a href="grouping" class="nav-link">
                                            <i class="fas fa-file-text fa-fw"></i>
                                            <span> دسته بندی ها </span>
                                        </a>
                                    </li>
                                    <li role="menuitem">
                                        <a href="#contact" class="nav-link">
                                            <i class="fas fa-phone-square fa-fw"></i>
                                            <span> تماس با ما </span>
                                        </a>
                                    </li>
                                    <li role="menuitem">
                                        <a href="#about" class="nav-link">
                                            <i class="fas fa-exclamation-circle fa-fw"></i>
                                            <span>درباره ما</span>
                                        </a>
                                    </li>
                                </ul>
                                <div id="headerPanelMenu-footer">© panisa-cake 2022</div>
                            </div>
                        </div>
                    </div>
                    <div class="col-2">
                        <div id="wb_headerBreadcrumb" style="display:inline-block;width:100%;z-index:1;vertical-align:top;">
                            <ul id="headerBreadcrumb">
                                <li>
                                    <a href="#home">خانه</a>
                                </li>
                                <li>
                                    <a href="#projects">دسته بندی ها</a>
                                </li>
                                <li>
                                    <a href="#contact">تماس با ما</a>
                                </li>
                            </ul>
                        </div>
                    </div>
                    <div class="col-3">
                        <input type="text" id="searchInput" style="display:none;width:185px;height:34px;z-index:2;" name="search" value="" spellcheck="false" placeholder="Search...">
                        <div id="wb_searchClose" style="display:none;width:33px;height:35px;text-align:center;z-index:3;">
                            <a href="#" onclick="ShowObjectWithEffect('searchInput', 0, 'slideright', 500);ShowObjectWithEffect('wb_searchClose', 0, 'fade', 1);ShowObjectWithEffect('wb_searchOpen', 1, 'fade', 1);return false;">
                                <div id="searchClose">
                                    <i class="fa fa-times"></i>
                                </div>
                            </a>
                        </div>
                        <div id="wb_searchOpen" style="display:inline-block;width:33px;height:35px;text-align:center;z-index:4;">
                            <a href="#" onclick="ShowObjectWithEffect('searchInput', 1, 'slideright', 500);ShowObjectWithEffect('wb_searchClose', 1, 'fade', 1);ShowObjectWithEffect('wb_searchOpen', 0, 'fade', 1);return false;">
                                <div id="searchOpen">
                                    <i class="fa fa-search"></i>
                                </div>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div id="wb_LayoutGrid5">
            <div id="LayoutGrid5-overlay"></div>
            <div id="LayoutGrid5">
                <div class="row">
                    <div class="col-1">
                        <div id="wb_Heading5" style="display:inline-block;width:100%;z-index:5;">
                            <h1 id="Heading5" class="hid-p">panisa cake</h1>
                        </div>
                        <div id="wb_Heading6" style="display:inline-block;width:100%;z-index:6;">
                            <h2 id="Heading6">انواع دسر و شیرنی های خوشمزه در پانیسا کیک</div>
                    </div>
                </div>
            </div>
        </div>
        <div id="wb_carouselGrid">
            <div id="carouselGrid">
                <div class="row">
                    <div class="col-1">
                        <div id="wb_Carousel1" style="">
                            <div id="Carousel1" class="carousel slide" data-ride="carousel">
                                <ol class="carousel-indicators">
                                    <li data-target="#Carousel1" data-slide-to="0" class="active"></li>
                                    <li data-target="#Carousel1" data-slide-to="1"></li>
                                    <li data-target="#Carousel1" data-slide-to="2"></li>
                                </ol>
                                <div class="carousel-inner">
                                    <div class="carousel-item frame-1 active">
                                        <div class="carousel-innerframe">
                                            <div id="wb_Text2" class="caption">
                                                <span style="color:#FFFFFF;font-family:Arial;font-size:21px;line-height:24px;">اسلاید 1</span>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="carousel-item frame-2">
                                        <div class="carousel-innerframe">
                                            <div id="wb_Text3" class="caption">
                                                <span style="color:#FFFFFF;font-family:Arial;font-size:21px;line-height:24px;">اسلاید 2</span>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="carousel-item frame-3">
                                        <div class="carousel-innerframe">
                                            <div id="wb_Text5" class="caption">
                                                <span style="color:#FFFFFF;font-family:Arial;font-size:21px;line-height:24px;">اسلاید 3</span>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <a class="carousel-item-left carousel-control" href="#Carousel1" role="button" data-slide="prev">
                                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                                    <span class="sr-only">Previous</span>
                                </a>
                                <a class="carousel-item-right carousel-control" href="#Carousel1" role="button" data-slide="next">
                                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                                    <span class="sr-only">Next</span>
                                </a>
                            </div>
                        </div>
                    </div>
                    <div class="col-2">
                        <div id="wb_text-1">
                            <span style="color:#FFFFFF;font-family:Arial;font-size:27px;line-height:32px;">عنوان</span>
                            <span style="color:#FFFFFF;font-family:Arial;font-size:13px;line-height:18px;">
                                <br>
                            </span>
                            <span style="color:#FFFFFF;font-family:Arial;font-size:16px;line-height:18px;">
                                متن زیر عنوان<br>
                            </span>
                            <span style="color:#FFFFFF;font-family:Arial;font-size:13px;line-height:16px;">
                                <br>
                                <br>
                                <br>
                                <br>
                                <br>
                                <br>
                                <br>
                                <br>
                                <br>
                            </span>
                        </div>
                        <input type="submit" id="Button1" name="" value="ادامه مطلب" style="display:inline-block;width:156px;height:37px;z-index:12;">
                    </div>
                </div>
            </div>
        </div>
        <div id="wb_BlockQuote">
            <div id="BlockQuote-overlay"></div>
            <div id="BlockQuote">
                <div class="row">
                    <div class="col-1">
                        <div id="wb_Text8" class="box-r">
                            <div class="box-1"> 
                                <h1></h1>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div id="wb_footer_top">
            <div id="footer_top">
                <div class="row">
                    <div class="col-1">
                        <div id="wb_Text1">
                            <span style="color:#FFFFFF;font-family:Arial;font-size:19px;">
                                <strong>اطاعات</strong>
                            </span>
                        </div>
                        <div id="wb_indexCssMenu1" style="display:inline-block;width:100%;z-index:18;">
                            <ul id="indexCssMenu1" role="menubar" class="nav">
                                <li role="menuitem" class="nav-item firstmain">
                                    <a class="nav-link" href="" target="_self">Lorem &nbsp;Ipsum</a>
                                </li>
                                <li role="menuitem" class="nav-item">
                                    <a class="nav-link" href="" target="_self">Dolor &nbsp;Sit &nbsp;Amet</a>
                                </li>
                                <li role="menuitem" class="nav-item">
                                    <a class="nav-link" href="" target="_self">Consectetur &nbsp;Adipiscing &nbsp;Elit</a>
                                </li>
                                <li role="menuitem" class="nav-item">
                                    <a class="nav-link" href="" target="_self">Integer &nbsp;Nec &nbsp;Odio</a>
                                </li>
                                <li role="menuitem" class="nav-item">
                                    <a class="nav-link" href="" target="_self">Praesent &nbsp;Libero</a>
                                </li>
                                <li role="menuitem" class="nav-item">
                                    <a class="nav-link" href="" target="_self">Sed &nbsp;Cursus</a>
                                </li>
                                <li role="menuitem" class="nav-item">
                                    <a class="nav-link" href="" target="_self">Ante &nbsp;Dapibus &nbsp;Diam</a>
                                </li>
                                <li role="menuitem" class="nav-item">
                                    <a class="nav-link" href="" target="_self">Nulla &nbsp;Quis &nbsp;Sem</a>
                                </li>
                                <li role="menuitem" class="nav-item">
                                    <a class="nav-link" href="" target="_self">Nibh &nbsp;Elementum &nbsp;Imperdiet</a>
                                </li>
                                <li role="menuitem" class="nav-item">
                                    <a class="nav-link" href="" target="_self">Duis &nbsp;Sagittis &nbsp;Ipsum</a>
                                </li>
                                <li role="menuitem" class="nav-item">
                                    <a class="nav-link" href="" target="_self">Praesent &nbsp;Mauris</a>
                                </li>
                                <li role="menuitem" class="nav-item">
                                    <a class="nav-link" href="" target="_self">Fusce &nbsp;Nec &nbsp;Tellus</a>
                                </li>
                            </ul>
                        </div>
                    </div>
                    <div class="col-2">
                        <div id="wb_Text6">
                            <span style="color:#FFFFFF;font-family:Arial;font-size:19px;">
                                <strong>لینک های مفید</strong>
                            </span>
                        </div>
                        <div id="wb_indexCssMenu2" style="display:inline-block;width:100%;z-index:20;">
                            <ul id="indexCssMenu2" role="menubar" class="nav">
                                <li role="menuitem" class="nav-item firstmain">
                                    <a class="nav-link" href="" target="_self">Augue &nbsp;semper &nbsp;porta</a>
                                </li>
                                <li role="menuitem" class="nav-item">
                                    <a class="nav-link" href="" target="_self">Mauris &nbsp;Massa</a>
                                </li>
                                <li role="menuitem" class="nav-item">
                                    <a class="nav-link" href="" target="_self">Vestibulum &nbsp;Lacinia</a>
                                </li>
                                <li role="menuitem" class="nav-item">
                                    <a class="nav-link" href="" target="_self">Arcu &nbsp;Eget &nbsp;Nulla</a>
                                </li>
                                <li role="menuitem" class="nav-item">
                                    <a class="nav-link" href="" target="_self">Class &nbsp;Aptent</a>
                                </li>
                                <li role="menuitem" class="nav-item">
                                    <a class="nav-link" href="" target="_self">Aaciti &nbsp;Sociosqu</a>
                                </li>
                            </ul>
                        </div>
                        <div id="wb_indexText1">
                            <span style="color:#FFFFFF;font-family:Arial;font-size:19px;">
                                <strong>بیشتر</strong>
                            </span>
                        </div>
                        <div id="wb_indexCssMenu3" style="display:inline-block;width:100%;z-index:22;">
                            <ul id="indexCssMenu3" role="menubar" class="nav">
                                <li role="menuitem" class="nav-item firstmain">
                                    <a class="nav-link" href="" target="_self">Litora &nbsp;Torquent</a>
                                </li>
                                <li role="menuitem" class="nav-item">
                                    <a class="nav-link" href="" target="_self">Conubia &nbsp;Nostra</a>
                                </li>
                                <li role="menuitem" class="nav-item">
                                    <a class="nav-link" href="" target="_self">Keptos &nbsp;Himenaeos</a>
                                </li>
                                <li role="menuitem" class="nav-item">
                                    <a class="nav-link" href="" target="_self">Curabitur &nbsp;Sodales</a>
                                </li>
                                <li role="menuitem" class="nav-item">
                                    <a class="nav-link" href="" target="_self">Ligula &nbsp;In &nbsp;Libero</a>
                                </li>
                            </ul>
                        </div>
                    </div>
                    <div class="col-3">
                        <div id="wb_Text4">
                            <span style="color:#FFFFFF;font-family:Arial;font-size:19px;">
                                <strong>ارتباط با ما از شبکه های اجتماعی</strong>
                            </span>
                        </div>
                        <div id="wb_FontAwesomeIcon1" style="display:inline-block;width:16px;height:16px;text-align:center;z-index:24;">
                            <a href="./index.html">
                                <div id="FontAwesomeIcon1">
                                    <i class="fab fa-facebook"></i>
                                </div>
                            </a>
                        </div>
                        <div id="wb_FontAwesomeIcon2" style="display:inline-block;width:16px;height:16px;text-align:center;z-index:25;">
                            <a href="./index.html">
                                <div id="FontAwesomeIcon2">
                                    <i class="fab fa-twitter"></i>
                                </div>
                            </a>
                        </div>
                        <div id="wb_FontAwesomeIcon3" style="display:inline-block;width:16px;height:16px;text-align:center;z-index:26;">
                            <a href="./index.html">
                                <div id="FontAwesomeIcon3">
                                    <i class="fab fa-pinterest"></i>
                                </div>
                            </a>
                        </div>
                        <div id="wb_FontAwesomeIcon4" style="display:inline-block;width:16px;height:16px;text-align:center;z-index:27;">
                            <a href="./index.html">
                                <div id="FontAwesomeIcon4">
                                    <i class="fab fa-instagram"></i>
                                </div>
                            </a>
                        </div>
                        <div id="wb_FontAwesomeIcon5" style="display:inline-block;width:16px;height:16px;text-align:center;z-index:28;">
                            <a href="./index.html">
                                <div id="FontAwesomeIcon5">
                                    <i class="fab fa-youtube"></i>
                                </div>
                            </a>
                        </div>
                        <div id="wb_indexText2">
                            <span style="color:#FFFFFF;font-family:Arial;font-size:19px;">
                                <strong>خبرنامه</strong>
                            </span>
                        </div>
                        <div id="wb_indexCssMenu4" style="display:inline-block;width:100%;z-index:30;">
                            <ul id="indexCssMenu4" role="menubar" class="nav">
                                <li role="menuitem" class="nav-item firstmain">
                                    <a class="nav-link" href="" target="_self">خرید اشتراک</a>
                                </li>
                            </ul>
                        </div>
                        <div id="wb_Text7">
                            <span style="color:#A6AEB1;font-family:Arial;font-size:13px;">
                                <strong>Copyright © panisa cake 2022. All right reserved. </strong>
                            </span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </body>
</html>
```
