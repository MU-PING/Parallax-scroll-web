# Parallax-scroll
## 程式簡介
### 簡述
* 透過 HTML、CSS 實作 Parallax-Scrolling( 視差捲動 ) 的網頁背景

* 實作方法主要有兩種：
  * " transform: translate3d 或 transform: translateY "

  * " perspective 搭配 transform: translateZ scale "
  
* 兩種方法差別，此程式採用第二種方法實作：
  * 第一種方法以2D空間為基礎：滑鼠滾動時，不同圖層間會有不同的移動速度，達成3D的效果

  * 第二種方法以3D空間為基礎：建立真的3D空間，調整圖層間不同的深度，自然滾動時就會有視差
* 第一種作法較為常見，但必須搭配 JavaScript；第二種可單純使用 HTML、CSS 完成

### 範例圖
![image](https://user-images.githubusercontent.com/93152909/221433094-c981512f-51e0-43f7-a8fe-399d4c17c98e.gif)

## Parallax-Scrolling( 視差捲動 )
* 電腦圖學和網頁設計中使用的技術，原理是在 2D 場景中建立一個深度錯覺

* 作法：將背景分為多個圖層，前面圖層的移動速度較快；後面圖層的移動速度較慢，以此達成深度錯覺
