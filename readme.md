・スライドアニメーションはWeb Animations APIを使用

・centerMode = true;で先頭のスライドを中央表示（複数枚時）

・レスポンシブ対応
画面幅に応じて、スライドの表示枚数変更

let slidesToShow;
if (window.matchMedia("(max-width: 750px)").matches) {
  slidesToShow = 1;
} else if (window.matchMedia("(max-width: 960px)").matches) {
  slidesToShow = 2;
} else {
  slidesToShow = 3;
}

■GitHub Pages
https://buchi-18.github.io/slider_vanilla
