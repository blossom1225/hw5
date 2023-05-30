<template>
    <a href="https://www.facebook.com/"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQUU-WiQ3EAKyJ5HDoz3xtLg91-bayxSe8QViroNy_D&s=0" style="height: 100px" alt=""></a>
    <div id="bottom">
        <p1>
            中文(台灣)  English (US)  Tiếng Việt  Bahasa Indonesia  ภาษาไทย  日本語  Español  Português (Brasil)  Français (France)  Deutsch  Italiano
            <br>
            註冊  登入  Messenger  Facebook Lite  Watch  地標  遊戲  Marketplace  Meta Pay  Meta Store  Meta Quest  Instagram  Bulletin  募款活動
            <br>
            服務 投票資訊中心  《隱私政策》  隱私中心  社團  關於  刊登  廣告  建立粉絲專頁  開發人員  工作機會  CookieAd Choices  使用條款
            <br>
            使用說明  聯絡人上傳和非用戶  設定活動紀錄
            <br>
            Meta © 2023
        </p1>
    </div>
</template>

<script>
export default {
}
</script>

<style scoped>

div {
    margin: 0;
    padding: 0;
}

a {
    display: flex;
    justify-content: center;
    margin-top: 50px;
}
/* 忘記帳號的超連結顏色*/
a1 {
    color: #2894FF;
    text-decoration: none;
}
/*登入表格的位置*/
.Login {
    display: flex;
    height: calc(100vh - 155px);
    flex-wrap: wrap;
}
/*登陸表格的寬度、顏色、四角設為圓形使其更好看 */
#loginForm {
    width: 500px;
    margin: 4rem auto auto auto;
    padding: 40px 24px;
    background-color: #FFF;
    border-radius: 4px;
    box-sizing: border-box;
    box-shadow: 0 1px 4px rgba(0, 0, 0, 0.2);
}
/*標題圖片的位置及字體大小*/
#head {
    display: flex;
    margin: 0 auto 6px auto;
    justify-content: center;
    font-size: 30px;
}

::placeholder {
    color: #B3B3B3;
}

#password span {
    position: absolute;
    top: 5px;
    right: 1px;
    width: 50px;
    height: 50px;
    border-radius: 3px;
    display: flex;
    align-items: center;
    justify-content: center;
}

#password span i {
    color: rgba(76, 87, 102, 0.6);
    font-size: 25px;
}
/*"或"旁邊的分隔線*/
hr {
    height: 1px;
    border: none;
    background-color: #D9D9D0;
    flex: 1 1;
}

#bottom {
    margin: 0 0 0 0;
    justify-content: center;
    text-align: center;
    font-size: 12px;
    background-color: #F0F0F0;
}
/*文字的大小及顏色*/
p {
    margin-top: 15px;
    color: #464646;
}

p1 {
    margin-top: 15px;
    color: #8E8E8E;
}
</style>