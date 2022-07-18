# 2022-HexSchool-Layout-Course-week1
2022 六角切版直播班 - 第一週

本週學習重點：

1. 網頁可分為容器與元素，外容器可用container
2. class 名稱順序，共用的 class 性質放自訂的 class 名稱後面，例如：div class="profile container"
3. 行距高度是由 line-height 所影響
4. 盡量不要寫死高度，可用padding去推
5. 推擠方向請盡量一致，以方便維護，例如 margin-bottom
6. 圖片可以設定 vertical-align:middle; 就不會有2-3px的空隙

-------------------------------------

下方提供關於作業細節的建議：

1. 「個人資料」區塊內可以將同一個項目的資料寫在同一個 li 內，整體可以使用兩個 li 標籤並搭配 br 標籤來將文字換行即可。

<ul>
  <li>
    陳久安 ..<br>
    1997- <br>
    應屆畢業生 ..
  </li>
  <li>
    UI 設計修行中 .. <br>
    獨立接案，內容涵蓋：<br>
    品牌 ..
  </li>
</ul>


2. 「聯絡方式」內資訊可以在 mail、phone、作品連結都使用 a 標籤包裹，透過連結的方式直接開啟信箱或是撥打電話，有助於增加使用者體驗，可以使用 Emmet 語法（a:mail、a:tel）來快速產生語法。

<ul>
  <li>Mail：<a href="mailto:xxxd@hexschool.com">xxxd@hexschool.com</a></li>
  <li>Phone：<a href="tel:+886-910123456">0910123456</a></li>
</ul>

3. a 標籤樣式建議添加   display: block; ，將其轉為區塊元素，這樣才會正確呈現。
<img src="https://s3-us-west-2.amazonaws.com/video-hexschool/teachable/DTRcKDQuyCd1qWB4dZLpCm08w14rdZIQongAKGo4lrCths39fM0ZnWohOqRshYBrrVThKbcsqjqIIMU8BJ0NtAhwYh5bR5N7sHUsdeOhpSmYs4J8ygkhaeo0TozJSa3K.">



