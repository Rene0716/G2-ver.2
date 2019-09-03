# sixInOneProject
專題說明文件=>有問題麻煩發issues
# G2專題
---

## 時間進度流程
1.剩下客製化區域整合
客製化第一個合併到首頁

---

2.JS動態表現
每一頁js細項討論
要使用哪些library

---

3.資料庫json使用
預計會有兩個方式
1.php
2.localjson-server(推薦這

---

4.webpack引入
html => temp 不用（寫完架構除非後面有異動
圖片壓縮=>會
library js import=>會

---

5.git 分枝
使用分枝合作方式
不過會採取備份雙份的方式
會有說明文件

---



******update:************
1.prod_html:
  1.1 prod_prodset區塊加入slider動畫
  1.2 prod_champion區塊加入canvas動畫(煙火效果),原先<img src="img/prod/groupchampion_bg.png" alt="團購冠軍">圖換掉
  1.3 合計加入的link:
      style/slider.css
      style/owlcarousel.css
      style/owl.theme.default.css
      js/pop.js
      OwlCarousel2/2.0.0-beta.2.4/owl.carousel.min.js(CDN)
      owl.carousel.min.js(CDN)
      js/collect.js
      js/lightbox.js(9/2 updated)
  1.4 section第二段加入燈箱的板 (9/2 updated)
      
2.JS資料夾:
  加兩隻--
  2.1 collect.js(商品收藏-->換圖)
  2.2 pop.js(團購冠軍-->canvas煙火效果動畫-->canvas背景色待修正)---->9/2已完成
3.style/css資料夾:
  加兩隻--(控制slider動畫)
   3.1 owl-carousel.css,
      (更動部分:
       .owl-carousel .owl-nav .owl-prev,.owl-carousel .owl-nav .owl-next加入原先左右鍵的設定,
       .owl-carousel .owl-item img將width:100%取消)
   3.2 slider.css
   
4.sass/_show.css:
   4.1 .prod_prodset .slider 背景圖片位置大小更動
   4.2 .slider .slider_prev,.slider_next 位置大小更動 
   4.3 _show.scss 最下面加入燈箱
5.未完成部分:
    5.1 點收藏愛心--秀會員登入燈箱---->9/2已完成
    5.2 點加入購物車-秀已加入燈箱
    
    
    
    
    

