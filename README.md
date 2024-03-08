<!DOCTYPE html>
<html lang="ja">
    <head>
        <meta chareset="utf-8">
        <title>WCB Cafe - CONTACT</title>
        <meta name="description" content="ブレンドコーヒーとヘルシーなオーガニックフードを提供するカフェ">
        <meta name="viewport" content="width=device-width, initial-scale=1">

        <meta property="og:url" content="http://example.com/index.html">
        <meta property="og:type" content="website">
        <meta property="og:title" content="WCB Cafe Home">
        <meta property="og:description" content="おしゃれなカフェで癒されてみませんか？無添加の食材で体の中からリフレッシュ。">
        <meta property="og:image" content="http://example.com/images/ogp.jpg">
         
    <!--CSS-->
       <link rel="stylesheet"href="https://unpkg.com/ress/dist/ress.min.css">
       <link href="https://fonts.googleapis.com/css?family=philosopher" rel="stylesheet">
       <link href="css/style.css" rel="stylesheet"> 
       <link rel="icon" type="image/png" href="images/favicon.png">    
    </head>

    <body>
      <div id="contact" class="big-bg"> 
        <header class="page-header wrapper">
            <h1><a href="index.html"><img class="logo" src="images/logo.svg" alt="WCBカフェホーム"></a></h1>
            <nav>
                <ul class="main-nav">
                    <li><a herf="news.html">News</a></li>
                    <li><a herf="menu.html">Menu</a></li>
                    <li><a herf="contact.html">Contact</a></li>
                </ul>
            </nav>        
        </header>
    
       <div class="wrapper">
        <h2 class="page-title">Contact</h2>
        <form action="#">
            <div>
                <label for="name">お名前</label>
                <input type="text" id="name" name="your-name">
            </div>

            <div>
                <label for="email">メールアドレス</label>
                <input type="email" id="email" name="your-email"> 
            </div>

            <div>
                <label for="mwssage">メッセージ</label>
                <textarea id="message" name="your-message"></textarea> 
            </div>

            <input type="submit" class="button" value="送信">
        </form>
       </div><!--"#contact"-->

       <section id="location">
        <div class="wrapper">
            <div class="location-info">
                <h3 class="sub-title">カフェ　東駅前店</h3>
                <p>
                    住所：東京都〇〇区<br>
                    〇〇〇〇 000-22-1<br>
                    〇〇〇<br>
                    電話：03-1111-1111<br>
                    営業時間：10:00~20:00<br>
                    休日：水曜
                </p>
            </div><!--/.location-info-->
            <div class="location-map">
                <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3241.4467042446454!2d139.73432710987726!3d35.66600133069865!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x60188b835eb8d1e9%3A0x2b7a60ac15c8822a!2z44CSMTA2LTAwMzIg5p2x5Lqs6YO95riv5Yy65YWt5pys5pyo77yS5LiB55uu77yU4oiS77yV!5e0!3m2!1sja!2sjp!4v1709643662072!5m2!1sja!2sjp" width="800" height="400" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
            </div><!--/.locaton-map-->
        </div><!--/.wrapper-->
       </section><!--#location-->
      
       <section id="sns">
        <div class="wrapper">
            <div class="sns-box">
                <h3 class="sub-title">Facebook</h3>
                <iframe src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Ffacebook&tabs=timeline&width=340&height=315&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=false&appId" width="340" height="315" style="border:none;overflow:hidden" scrolling="no" frameborder="0" allowfullscreen="true" allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"></iframe>
            </div>

            <div class="sns-box">
                <h3 class="sub-title">Twitter</h3>
                <a class="twitter-timeline" data-height="315" href="https://twitter.com/hikari?ref_src=twsrc%5Etfw">Tweets by hikari</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
            </div>

            <div class="sns-box">
                <h3 class="sub-title">Youtube</h3>
                <iframe width="560" height="315" src="https://www.youtube.com/embed/lkreUKtKPys?si=yCBmqSCqIs1__2Vw&amp;start=23" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
            </div>
        </div><!--/.wrapper-->
       </section><!--/#sns-->
           

        
        <footer>
            <div class="wrapper">
                <p><small>&copy; 2019 Manabox</small></p>
            </div>
        </footer>
    </body>
</html>
