<!DOCTYPE html>
<!--標註網頁語系-->
<html lang="zh-TW">

<head>
    <!--告訴瀏覽器編碼-->
    <meta charset="UTF-8">
    <!--網頁簡短描述-->
    <meta name="description" content="">
    <!--提供網頁標頭的內容屬性資訊-->
    <!--什麼版本IE,就用什麼版本的標準模式：-->
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <!--針對移動網頁優化過的頁面的viewport meta標籤-->
    <!--讓網頁的寬度自動適應手機屏幕的寬度,在iOS9中要想起作用就加上"shrink-to-fit=no"-->
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Title -->
    <title>B.F Store</title>

    <!--<link> icon 是用來設定網頁 Favicon (favorites icon)，Favicon 就是會出現在瀏覽器頁籤或書籤 (我的最愛) 上面的小圖示。-->
    <!-- Favicon -->
    <link rel="icon" href="img/core-img/bf.png">

    <!-- Style CSS -->
    <!--告訴瀏覽器要導入一個外部名為style.css的樣式檔案-->
    <link rel="stylesheet" href="style.css">

</head>

<body>
    <header>
        <!-- Top Header Area -->
        <div class="top-header">
            <div class="container h-100">
                <!--row 要加上 h-100 才能作為內部區塊的高度比較基準-->
                <!--align-items-center交錯軸的對齊設定-->
                <div class="row h-100 align-items-center">
                    <!-- Breaking News Area -->
                    <div class="col-12 col-sm-8">
                        <div class="breaking-news-area">
                            <div id="breakingNewsTicker" class="ticker">
                                <ul>
                                    <li><a href="product.html">Do whatever your want!</a></li>
                                    <li><a href="product.html">Because you deserve!</a></li>
                                    <li><a href="product.html">Fearless!</a></li>
                                    <li><a href="product.html">Be Brave!</a></li>
                                    <li><a href="product.html">Wear your own style!</a></li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Logo Area -->
        <!--logo-area text-center文字置中-->
        <div class="logo-area text-center">
            <div class="container h-100">
                <!--align-items-center主軸和交叉軸置中-->
                <div class="row h-100 align-items-center">
                    <!--Column 的格數（最多到 12），col-12一列希望有 12 個相等-->
                    <div class="col-12">
                        <!--LOGO圖-->
                        <a href="index.html" class="original-logo"><img src="img/core-img/logo.png" alt=""></a>
                    </div>
                </div>
            </div>
        </div>

        <!-- Nav Area -->
        <div class="original-nav-area" id="stickyNav">
            <div class="classy-nav-container breakpoint-off">
                <div class="container">
                    <!-- Classy Menu -->
                    <!--justify-content-between均匀排列每個元素
                                   首個元素放置起點，末置元素放置於终点-->
                    <nav class="classy-navbar justify-content-between">
                        <div>
                        </div>
                        <!-- Menu --> 
                        <div class="classy-menu" id="rowNav">
                            <!-- Nav Start -->
                            <div class="classynav">
                                <ul>
                                    <li><a href="index.html">Home</a></li>
                                    <li><a href="about.html">About Us</a></li>
                                    <li><a href="product.html">Product</a>
                                    <li><a href="contact.html">Location</a></li>
                                </ul>

                                <!-- Search Form  -->
                                <!--enjoy-->
                                <div id="enjoy_img">
                                   <img src="img/bg-img/enjoy.jfif">
                                </div>
                            </div>
                        </div>
                    </nav>
                </div>
            </div>
        </div>
    </header>
    <!-- ##### Header Area End ##### -->
    <hr>

    <!-- ##### Hero Area Start ##### -->
    <!--圖片文字輪播效果-->
    <div class="hero-area">
        <!-- Hero Slides Area -->
        <div class="hero-slides owl-carousel">
            <!-- 圖片1 -->
            <div class="single-hero-slide bg-img" style="background-image: url(img/bg-img/c1.jpg);">
                <div class="container h-100">
                    <div class="row h-100 align-items-center">
                        <div class="col-12">
                            <div class="slide-content text-center">
                                <div class="post-tag">
                                    <!--圖片上小字-->
                                    <a href="product.html" data-animation="fadeInUp">lifestyle</a>
                                </div>
                                <!--圖片上大字-->
                                <h2 data-animation="fadeInUp" data-delay="250ms"><a href="product.html">Choose your
                                        life!</a></h2>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <!-- 圖片2 -->
            <div class="single-hero-slide bg-img" style="background-image: url(img/bg-img/c2.jpg);">
                <div class="container h-100">
                    <div class="row h-100 align-items-center">
                        <div class="col-12">
                            <div class="slide-content text-center">
                                <div class="post-tag">
                                    <a href="product.html" data-animation="fadeInUp">lifestyle</a>
                                </div>
                                <h2 data-animation="fadeInUp" data-delay="250ms"><a href="product.html">Choose your
                                        want!!</a></h2>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <!-- 圖片3 -->
            <div class="single-hero-slide bg-img" style="background-image: url(img/bg-img/c3.jpg);">
                <div class="container h-100">
                    <div class="row h-100 align-items-center">
                        <div class="col-12">
                            <div class="slide-content text-center">
                                <div class="post-tag">
                                    <a href="product.html" data-animation="fadeInUp">lifestyle</a>
                                </div>
                                <h2 data-animation="fadeInUp" data-delay="250ms"><a href="product.html">Choose your
                                        love!</a></h2>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <br>
    <br>
    <!-- ##### Hero Area End ##### -->

    <footer style="text-align: center;">
        <!-- Link back to Colorlib can't be removed. Template is licensed under CC BY 3.0. -->
        <p>Be Brave & Fearless
            <small>&copy;2020 B.F.Store. All Rights Reserved</small>
        </p>
        <!-- Link back to Colorlib can't be removed. Template is licensed under CC BY 3.0. -->
    </footer>
    <!-- ##### Footer Area End ##### -->

    <!-- jQuery (Necessary for All JavaScript Plugins) -->
    <!--載入jQuery-->
    <script src="js/jquery/jquery-2.2.4.min.js"></script>
    <!-- Popper js -->
    <script src="js/popper.min.js"></script>
    <!-- Bootstrap js -->
    <script src="js/bootstrap.min.js"></script>
    <!-- Plugins js -->
    <script src="js/plugins.js"></script>
    <!-- Active js -->
    <script src="js/active.js"></script>

</body>

</html>
