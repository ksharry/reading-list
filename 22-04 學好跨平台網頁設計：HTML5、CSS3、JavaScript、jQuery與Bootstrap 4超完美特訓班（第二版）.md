<table>
    <tr>
        <td>學好跨平台網頁設計：HTML5、CSS3、JavaScript、jQuery與Bootstrap 4超完美特訓班（第二版）</td>
    </tr>
</table>

## 個人筆記  https://www.books.com.tw/products/0010812394
## 書本資訊:
1. 作者： 鄧文淵, 文淵閣工作室  
2. 出版社：碁峰  
3. 出版日期：2019/01/28
4. 語言：繁體中文
5. 電子書價:302元
6. 範例下載:http://books.gotop.com.tw/download/ACL055700
7. BLOG:http://blog.e-happy.com.tw/tag/%E7%A8%8B%E5%BC%8F%E7%89%B9%E8%A8%93%E7%8F%AD/
8. FB:https://www.facebook.com/eHappyTT

#### 01 HTML基礎入門
HTML5除了簡化了HTML語法的結構，提供了許多功能標籤能夠直接控制音效、影片等多媒體檔案的播放，並且進一步加入控管地理位置的Geolocation API、繪圖的Canvas API、本地端的資料庫、離線的儲存機制 ⋯ 等讓人期待的功能，讓網頁的呈現與應用提升到另一個不同的層次。
1. HTML的出現
2. HTML5的歷史
3. HTML5的新功能
4. HTML5的編輯與瀏覽

#### 02 HTML結構與文字段落
HTML是一個很重要的語法，它能整合文字、圖片、聲音、動畫、影片等內容，藉由瀏覽器讓資訊能夠無遠弗屆，深入到每個角落。在這裡先介紹HTML的文字段落與超連結等標籤，扎實打好HTML的基礎。
1. HTML文件結構
   + 容器元素 h1
   + 單一元素 href="xxx"
2. 段落
   + p,br,h1,pre,blockquote,hr,
   + ol,ul,li
   + dl,dt,dd 
   + div,span(不換行)
   + <!--注釋-->
3. 文字格式
   + b,storng,i,em,u
   + sub,sup
4. HTML5的語意標籤
   + header,nav,article,selector,aside,footer
#### 03 超連結、圖片、音效與影片
超連結是HTML 中很重要的一個元素，藉由超連結能夠將不同的網站連繫在一起，也能連結到不同的網站，甚至是不同的資源。除了文字之外，圖片、音效與影片更是HTML 中很重要的內容。本章將要說明如何在網頁中加入圖片、音效與影片，並說明HTML5 新增的元素與功能，讓多媒體的資源豐富您的網頁與內容。
1. 路徑的表示方法
2. 超連結
    + 常用超連結
     > 
       <a href="http://www.e-happy.com.tw" target="_blank">文淵閣工作室</a>
    + 頁內超連結 
     > 
       <a href="#ch01">前往Ch01</a> 
       <h2 id="ch01">Ch01</h2> 
3. 圖片
    + 圖片超連結,圖片說明figure/ficaption
     > 
       <img src="images/HTML5.png" width="128" height="128" alt="HTML5 Logo">
4. 音效的使用
    + 音效超連結
     > 
       <source src="media/music.mp3" type="audio/mpeg">
5. 影片的使用
    + 影片超連結
     > 
       <source src="media/movie.mp4" type="video/mp4">
#### 04 表格與表單
表格是網頁中資料展示的重要利器，本章將分析表格中各個部位，並說明相關的標籤與屬性。表單是網站與瀏覽者互動的窗口，不同的資料需要不同的表單元件來傳送。本章除了介紹HTML中原有的表單元件的建置方式，並會進一步說明HTML5新增的表單元件與使用方式。
1. 表格
    + 表格
     > 
       <table border="1" width="80%" cellspacing="5" cellpadding="5">
       <td colspan="2">A</td>
2. 表單
    + 表單
     > 
       <p>帳號：<input type="text" name="username"></p>
       <p>密碼：<input type="password" name="passwd"></p>
       <p><input type="submit" value="登入"> <input type="reset" value="重置"></p>
       <input type="radio" name="gender" value="male">男
       <input type="checkbox" name="interest" value="Jog">慢跑
       <select name="season">
           <option name="spring">春天</option>
       <select name="season" size="4" multiple>
       <textarea name="poem" rows="5" cols="20">
       <fieldset>
           <legend>登入資訊</legend>
       <p>姓名：<input type="text" name="username" placeholder="請輸入姓名" required autofocus></p>
       <p>搜尋：<input type="search" name="search"></p>
       <p>信箱1：<input type="email" name="email"></p>
       <p>信箱2：<input type="text" name="email2" pattern="[a-z0-9._%+-]+@[a-z0-9.-]+\.[a-z]{2,4}$">
       <p>網址：<input type="url" name="url"></p>
       <p>電話：<input type="tel" name="tel"></p>
       <p>數字：<input type="number" name="number" min="1" max="21" step="3"></p>
       <p>日期：<input type="date" name="date"></p>
       <p>時間：<input type="time" name="time"></p>
       <p>程度：<input type="range" name="range"></p>
       <p>顏色：<input type="color" name="color"></p>
#### 05 CSS基礎入門
CSS(Cascading Style Sheets)樣式表在網頁設計中占了十分重要的地位，HTML是將網頁進行結構化的製作，而CSS可以依照這個結構進行美化，提升網頁載入的速度，有系統的打造網站的風格。CSS選擇器是套用樣式的基本功夫，除了一般的套用之外，還能使用屬性選擇器、虛擬類別選擇器、虛擬元素選擇器及組合選擇器，讓樣式的套用更靈活。
1. 認識 CSS
   + 改善網頁架構
   + 縮短製作時間
   + 提升頁面速度
   + 改善搜尋引擎排名
   + 跨平台與無障礙設計
2. CSS3的新功能
3. CSS的套用方式
   + 行類樣式 style="color:FF0000"
   + 內部樣式載入 <style> </style>
   + 外部樣式載入
     + 使用link元素
     + 使用@import
4. CSS基本語法
   + 選擇器
   + 宣告
   + 瀏覽器的前綴詞
5. CSS基本選擇器
   + 全域選擇器 *
   + 元素選擇器 h3
   + Class選擇器 .class
   + id選擇器 #id
6. CSS屬性選擇器
   + img[alt~="Logo"]
   + a[href^="http://"]{
   + img[src$=".png"]{
   + a[href*="e-happy"]{
7. CSS虛擬類別選擇器
   + a:link
   + a:hover
   + a:visited
   + a:active
   + td:nth-child(1)
   + tr:nth-child(2n+1)
   + tr:first-child
   + p::first-line
   + p:nth-of-type(3)
   + p:nth-child(3)
   + p:nth-of-type(3)
8. CSS虛擬元素選擇器
   + p::first-line
   + p::first-letter
   + ul::before
   + ul::after
9. 組合選擇器
   + 後代選擇器 ul li em {
   + 子選擇器 ul>li>em {
10. CSS選擇器的套用順序
   + 後來勝過先前
   + 全域>元素>class>id
   + !important優先

#### 06 顏色與文字設定
網頁中顏色的使用相當重要，除了能提高閱讀的舒適度，善用顏色的搭配能讓頁面的表現更加分。文字是網頁中最基礎但也最重要的內容，使用CSS 能快速的定義文字大小，粗細、字型、顏色 ... 等樣式，讓文字的呈現不再一成不變。
1. 顏色的設定
   + 使用RGB
   + 使用RGBA
   + 使用HSL
   + 使用HSLA
   + 使用顏色名稱設定
2. 文字大小、字型及相關的樣式設定
   + 文字大小
     + 絕對數值,16px
     + 相對數值,smaller,em,%
   + 文字粗細,font-weight:bold/100-900
   + 文字斜體,font-style:italic/oblique
   + 文字變體:font-variant:small-caps
   + 文字與背景顏色: color: black; background-color: white;
   + 文字大小寫,text-transform: uppercase/capitalize
   + 底線與刪除線text-decoration: underline/line-through/overline;
   + 文字樣式快速設定:font: italic small-caps bold 1.5em/2em '標楷體'
3. 字型設定
   + 字型:font-family: "微軟正黑體";
   + 加入GOOGLE字型:<link href="https://fonts.googleapis.com/css?family=Indie+Flower" rel="stylesheet">
   + 鑲入字形: @font-face {font-family: MyFont; src: url('GloriaHallelujah.ttf');}

#### 07 段落與表列設定
文字段落的樣式包括了行距、文字間距、對齊、縮排 ... 等，對於網頁資訊的呈現也相當重要。表列資料的呈現分為項目符號及編號，對於資料的表現十分重要。CSS 的設定能更完美的呈現表列資料。
1. 文字段落相關的樣式設定
   + 行高:style="line-height: 1em";
   + 文字間距:style="letter-spacing: 0.5em"
   + 文字對齊:style="text-align: left"
   + 垂直對齊:vertical-align: top
   + 上下標文字:style="vertical-align: sub/super;
   + 首行縮排:style="text-indent: 1em
2. 項目符號及編號的設定
   + 項目編號:list-style-type: circle/disc
   + 圖片項目:list-style-image: url(like.png)
   + 項目位置:list-style-position: outside
   + 項目快速設定:list-style: square inside;
3. 超連結的樣式設定
4. CSS3：文字陰影
   + 文字陰影:text-shadow: 1px 1px 3px
   + 多重文字陰影:光暈/內嵌/浮凸/立體

#### 08 背景與框線設計
在網頁中可以為元素設定背景，可以凸顯前景的內容。設定的方式十分多元，可以使用顏色、圖片，並能設定背景圖片的位置，背景圖片重複的方式，以及透明度，甚至使用漸層顏色。框線與背景設定的條件十分相似，只要是區塊的標籤元素都能設定框線。除了顏色、粗細，還能設定顯示的樣式，設定圓角，加上陰影。
1. 設定背景顏色及圖片 
   + background-color
   + background-image: url(bg-1.png)
   + style="background-image: url(bg-1.png);
   + background-repeat: no-repeat;
   + background-image: url(bg-1.png);background-repeat: no-repeat;background-position: top center;
   + background-image: url(bg-1.png);background-repeat: no-repeat;background-position: right top;background-attachment: fixed;"
2. 設定透明度
   + .opacity1 { opacity: 0.25}
3. 設定漸層
   + .linear1 { background: linear-gradient(to bottom, yellow, green);}
   + 重複性:background: repeating-linear-gradient(to right, yellow 30px, green 70px);
   + 放射性:background: radial-gradient(circle, red, yellow, green);
4. 框線的設定
   + style="border: dotted 5px #FF0000;
   + 上右下左:style="border-style: dotted solid dashed double; border-width: 1px 2px 3px 4px; border-color: black yellow red green;"
5. 表格框線
   + 框線重疊:border-collapse: collapse;
6. CSS3：圓角框線
   + style="border: solid 3px orange; border-radius: 20px;
   + 兩角style="border: solid 3px orange; border-radius: 60px 0px; 
7. CSS3：區塊陰影
   + box-shadow: 10px 10px 5px 5px gray;
           
#### 09 盒子模型與版面定位
在網頁的版面上可以說是一個個盒子所組成的，只要能熟悉盒子模型的結構，即可準確的規劃版面中每個區塊的尺寸以及與其他區塊之間的排列狀態。float屬性能將元素設置到所在容器的最左方或最右方成為浮動元素，跟在該元素後方的內容就接著流動到剩下來的位置中。position屬性能精確的定位區塊元素的位置，並依不同特性安排區塊元素的展示方法。CSS3的媒體查詢能根據不同媒體、不同的特性給予不同的CSS樣式設定。
1. 使用元素結構的重要觀念
   + 元素的區別
     + 區塊/行內
   + 容器的觀念
2. 認識盒子模型
   + 關於盒子模型
   + 內容顯示區域
     + 限制高度與寬度:max-width: 500px;
     + 溢出:overflow: hidden;
     + padding: 0px;
     + Div的邊界:margin: 5px;
     + 行內情況:display: inline;
     + 隱藏:visibility: hidden;
3. float的使用
   + float:float: left;
   + clear: both;
4. position的使用
   + position: relative;
   + position: absolute;
   + position: fixed;
5. 媒體查詢
   + 畫面變小變黑色@media screen and (min-width: 300px) and (max-width: 600px){
   + RWD:         @media screen and (min-width: 320px){

#### 10 變形、轉換與動畫
在CSS3中可以使用transform屬性來設定元素的變形效果，進行移動、縮放、旋轉、傾斜等變化。transition轉換效果是指元素由一種樣式轉換到另一種樣式的動作，可由播放時間、轉換屬性、轉換方法及延遲時間的屬性進行設定。animation動畫效果就是由播放的起點到終點設定多個關鍵影格，接著指定元素在每個關鍵影格中屬性有不同的變化所呈現的動畫。
1. 變形效果
   + transform: translate(20px, 10px)/rotate(45deg)/scale(1.5, 0.5)/skew(20deg, 30deg)
   + 預設位置:transform-origin: 0% 0%;
2. 轉換效果
   + transition-duration: 1s;transition-property: width;transition-timing-function: ease;transition-delay: 0s;
   + 綜合設定:transition: 1s width ease 0s;
   + 分段執行:transition: 1s width, 1s background-color 1s;
3. 動畫效果
   + 變顏色@keyframes myanimation;animation-name: myanimation;animation-duration: 2s;animation-timing-function: ease;animation-delay: 1s;
   + 變位置:animation-play-state: paused;
   + 變顏色+位置
#### 11 JavaScript語法與結構
JavaScript是一種腳本(Script)式的程式語言，其原始碼在客戶端執行之前不需經過編譯，而是將文字格式的字元代碼發送給瀏覽器再由瀏覽器解譯執行。所以JavaScript在撰寫、測試到除錯都很容易，只要在編輯之後儲存，就能在瀏覽器觀看結果。JavaScript因為瀏覽器的支援而能夠輕鬆跨越不同平台而大行其道，並隨著新的JavaScript引擎及框架技術的發展，利用事件驅動與非同步寫入讀出等特性，JavaScript竟然也逐漸被應用到開發伺服器端程式。
1. 認識JavaScript
   + 建立第一個JS
     + script標籤
     + 加入JS位置
   + JS語法規定
   + JS的保留字
2. 變數的使用
   + 變數與命名宣告
   + 設定變數值
3. 運算子
   + 加減乘除
   + 邏輯運算
4. 流程控制
   + 條件控制:if,switch
   + 迴圈控制:while,for

#### 12 JavaScript函式、陣列與物件
函式即是將程式碼中重複使用的部分單獨出來，在應用時只要呼叫即可使用，提高程式開發的效率。陣列可說是一群性質相同變數的集合，能大量降低變數宣告的數量，提高程式開發時的彈性。物件可以說是屬性與方法的組合，每個物件上都有它的特徵與功能，化為程式的屬性與方法。
1. 函式的使用
   + 函式的使用function myInformation(){
   + 函式的參數function showName(myName){
   + 函式的傳回值return dc * 1.8 + 32;
2. 陣列的使用
   + 建立一維陣列var student = ["David","Lily","Perry"];
   + 多維陣列document.write("<td>" + student[i][j] + "</td>");
3. 物件
   + 自訂物件function Person(name, age, weight, height){
4. Javascript與DOM
   + 認識DOM
   + 利用JS存取元素節點var findUrl = document.getElementById("myHomePage");alert(findUrl.innerHTML + " 的網址是 \n" +findUrl.href);
   + 取得圖片ALT var findImg = document.getElementsByTagName("img");        

#### 13 jQuery基礎入門
jQuery是目前最多人使用、開發維護及延伸應用的JavaScript函式庫，除了可以簡化開發者的程式語法，也能幫助使用者獲得更好的互動經驗，為網頁程式設計者省下了大量的開發時間，也為使用者互動帶來了便利，更帶來許多讓人驚豔的強大功能！
1. 認識jQuery
    + JQuery的基本架構
     > 
       <meta charset="UTF-8">
       <title>範例</title>
       <script src="http://code.jquery.com/jquery-3.2.0.min.js"></script>
       <script>
         $(document).ready(function(){
             alert("Hello, jQuery!");
        })
       </script>
2. jQuery選擇器
   + 基本選擇器$(document).ready(function(){
   + JQuery層級選擇器 div a or  div>a
   + JQuery篩選選擇器 $('tr:even'/tr:odd/tr:first).css('background-color','#FF9');
   + JQuery選擇器其他選取方式      

#### 14 jQuery的事件與特效
jQuery可以使用選擇器輕易的選取頁面上的內容，包含了CSS與DOM裡的結構，在選取後就能根據事件來進行互動，或是加上特效。jQuery的事件處理是互動程式很重要的一環，許多程式的執行必須依靠事件來觸發才能夠進行。jQuery提供了許多設定簡單，但效果驚人的特效。只要善用這些功能，就能讓您的頁面更加吸引人。
1. jQuery與CSS、DOM的處理
    + JQuery與CSS互動 <code>$('#box2').css/toggle('width', $('#box1').css('width'));</code>
    + JQuery與DOM互動 
     > 
       $('#box1').html/text('<>這是有HTML的文字</h3>');
       $('#sList').before('<>本書重點技術</h1>');
2. jQuery的事件
   + 事件的處裡:<code>$('#btn1').click(function(){;$('#btn1').bind('click',sayOK);if (event.target.id == 'btn2'){</code>
3. jQuery的特效
   + JQuery特效:<code>$('#box').show/hide/toggle/slideDown/fadeOut/fadeOTO(500)</code>

#### 15 jQuery Mobile入門
jQuery Mobile是一個行動裝置網頁介面的開發框架，不同於傳統網頁，它提供了許多工具讓您可以開發出如同行動裝置 App 應用程式的使用畫面。例如頁面的切換、智慧型手機的操作介面、觸控操作的使用... 等。jQuery Mobile的基底技術是jQuery，它能讓網頁的HTML標籤，藉由JavaScript、CSS的幫助呈現出如行動裝置一樣的頁面。
1. jQuery Mobile
   + 引入:script src="http://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.js"></script
   + viewport與data-role
     + viewport meta標籤，MOBILE使用
     + data-role 自訂資料屬性
   + 固定位置:div data-role="header" data-position="fixed"
   + 切換佈景主題:div data-role="page" id="page3" data-theme="c"
2. jQuery Mobile 超連結方式
   + 單黨多頁:div data-role="header" data-add-back-btn="true"
   + 頁面切換特效:a href="#page2" data-transition="fade">Fade

#### 16 jQuery Mobile常用元件
jQuery Mobile提供了許多常用元件，讓行動裝置的畫面與一般原生程式的操作更接近。其中包含了按鈕、群組按鈕、導覽列、檢視清單、版面格點、可摺疊內容區塊、可摺疊內容區塊組、對話方塊及側邊欄面板。只要能善用這些元件，即可快速製作出精美而實用的使用介面。
1. 按鈕、按鈕群組與導覽元件
   + 按鈕:a href="#" data-role="button">按鈕一</a>
   + 圖式:a href="#" data-role="button" data-icon="action">action</a>
   + 位置:a href="#" data-role="button" data-icon="star" data-iconpos="top">上方圖示</a>
   + 新增:a href="#" data-role="button" data-icon="plus">新增</a>
2. 清單元件
   + 清單篩選:ul data-role="listview" data-inset="true" data-filter="true">
   + 清單分組:li data-role="list-divider">A</li>
   + 氣泡計數:a href="#">Acura span class="ui-li-count">12</span></a
   + 加入縮圖:img src="images/phoebe.jpg">
3. 版面格點元件,區塊:class="u1-block-a">
4. 版面格點元件,摺疊:div data-role="collapsible" data-collapsed="true">
5. 對話方塊元件,對話框:a href="#page1" data-role="button" data-rel="dialog">訊息視窗1</a>
6. 側邊欄面板元件:div id="panelOverlay" data-role="panel" data-position="left" data-display="overlay" data-dismissible="false">

#### 17 jQuery Mobile互動
使用jQuery Mobile與使用者互動，就必須使用表單、事件與方法。jQuery Mobile表單能提供使用者輸入的資料介面，並檢視資料的正確性，再送到指定的程式進行處理。jQuery Mobile提供了頁面、觸控、捲動及方向切換等事件，幫助使用者與頁面的內容進行互動。jQuery Mobile提供了頁面切換及預載頁面的方法，幫助使用者在頁面之間切換並傳遞資料，或是以預載的方式增進頁面顯示效能。
1. jQueryMobile表單:
   + 表格input type="password" name="inputPass" id="inputPass"/>
   + 拉桿:input type="range" name="slider-fill" id="slider-fill" value="60" min="0" max="1000" step="50" data-highlight="true">
   + 開關:select name="slider" id="slider" data-role="slider">
   + 單選:input type="checkbox" name="checkbox-1" id="checkbox-1" checked="">
   + 下拉:select name="selectmenu" id="selectmenu">
   + 取值:var msg = '文字欄位：'+$("#iText").val()+"\n";
2. jQueryMobile事件
   + 頁面事件:$(document).on("pagecreate" , function(e){
   + 滑鼠事件:$(document).on("tap" , function(e){
   + 滾輪事件:$(document).on("scrollstart" , function(e){
   + 螢幕方向:$(window).on("orientationchange" , function(e){
   + 頁面預設:$.mobile.pageLoadErrorMessage = "喔，頁面無法載入喔!";
3. jQueryMobile方法
   + 頁面切換:$.mobile.changePage("#page2", {transition:"slidedown"});
   + 頁面傳送:$.mobile.changePage("fun_cp_get.php", {
   + 載入外部:$.mobile.loadPage("fun_loadpage2.htm");
             
#### 18 Bootstrap入門
Bootstrap是開發響應式網站的重要框架，以行動優先為設計方針，利用格線系統的觀念，擴充開發相關的CSS設定、元件應用與JavaScript 函式庫，讓它成為接軌現代網頁開發的重要技術之一。隨著原始碼的公開，優異的本質吸引許多開發者加入研發與維護，龐大的使用者為這個專案帶來了豐富的資源。學習者輕易就能在網路上查詢到相關的教學、技術與範例，獲得充足的幫助與支援。
1. 認識Bootstrap
2. Bootstrap的安裝與使用
   + 載入css:link rel="stylesheet" href="css/bootstrap.min.css">
   + 載入bs:script src="js/jquery-3.3.1.min.js">src="js/popper.min.js">src="js/bootstrap.min.js"</script>
3. Bootstrap的格線系統
   + bs的系統
     + 960格線系統
     + Blueprint
     + Golden Grid System
   + .col-螢幕大小類型-col比例:div class="col-12 col-sm-12 col-md-4">3/3</div>
   + flexbox:div class="row justify-content-start">
   + 垂直對齊:div class="row align-items-start">
   + 整題對其:div class="col align-self-center">
4. Bootstrap的文字段落
   + 標題、段落與文字
   + 對齊轉換類別
   + 清單
   + 程式碼區塊

#### 19 表格、表單、按鈕與圖片
Bootstrap針對網頁中的表格、表單、按鈕與圖片，設計了計多相關的CSS樣式，在套用後不僅美觀，風格一致，有許多設定還能讓套用的元件在響應式的網站中獲得更好的呈現。
19.1 Bootstrap的表格
19.2 Bootstrap的表單佈局
19.3 Bootstrap的表單元素
19.4 Bootstrap表單狀態樣式
19.5 Bootstrap的按鈕
19.6 Bootstrap的圖片

#### 20 Bootsrtap元件
Bootstrap提供了許多實用又美觀的元件，例如下拉式選單、按鈕、輸入群組、導覽標示、導覽列及其他導覽元件、警告訊息、進度條、清單群組及卡片，讓使用者可以快速加入在頁面上，為網站增添許多功能。
20.1 下拉式選單
20.2 按鈕群組
20.3 輸入群組
20.4 導覽標示
20.5 導覽列
20.6 其他導覽元件
20.7 超大螢幕效果
20.8 警告訊息及進度條
20.9 清單群組
20.10 卡片元件

#### 21 Bootstrap JS元件
Bootstrap提供了許多功能強大且效果極佳的JavaScript元件，其中包括了可切換內容標籤、互動視窗、提示訊息、彈跳提示訊息、折疊效果、手風琴效果及圖片輪播效果元件，能在最簡單的設定下為網頁加入許多實用的功能。
21.1 可切換內容標籤元件
21.2 互動視窗元件
21.3 提示訊息及彈跳提示訊息
21.4 折疊效果元件
21.5 手風琴效果元件
21.6 圖片輪播效果元件
