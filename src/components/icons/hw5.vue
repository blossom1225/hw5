<template>
    <div id="window">
        <h1>登入 facebook</h1>
        <div class="page-content">
            <div class="input-row">
                <input id="username" type="text" placeholder="電子郵件地址或手機號碼"/>
                <input id="password" type="password" placeholder="密碼"/>
            </div>
            <button id="submit">登入</button>
        </div>
    </div>
    <h1 id="forget">忘記密碼?</h1>
    <button id="create">建立新帳號</button>
</template>

<script>
export default {
    data() {
        return {
            username: '',
            password: '',
        };
    },
    methods: {
        login() {
            // 取得使用者輸入的帳號和密碼
            const username = this.username;
            const password = this.password;

            // 進行登入驗證，可以使用後端伺服器或其他方式
            // ...

            // 登入成功後，導向到YouTube網址
            window.location.href = 'https://youtu.be/_Bz8WA9TpsQ';
        },
    },
};
</script>

<style scoped>
body {
    background: url(1.png) no-repeat fixed center/cover;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
}

.input-row {
    margin-top: 20px;
}

#window {
    position: absolute;
    top: 40%;
    left: 50%;
    transform: translate(-50%, -50%);
    width: 300px;
    height: 280px;
    background-color: #ffffff;
    padding: 20px;
    border: 1px solid #D0D0D0;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
    z-index: 2;
    display: flex;
    flex-direction: column;
}

#username, #password {
    width: 100%;
    height: 40px;
    margin-bottom: 10px;
    border: 1px solid #D0D0D0;
}

#submit{
    width: 100%;
    height: 40px;
    border-radius: 5px;
    margin-bottom: 10px;
    border: none;
    background-color: #0066CC;
    color: #fff;
    font-size: 18px;
}

#forget{
    position: absolute;
    top: 47%;
    left: 47%;
    z-index: 3;
    font-size: 16px;
    color: #0066CC;
}

#create{
    position: absolute;
    top: 55%;
    left: 45%;
    width: 10%;
    height: 40px;
    z-index: 3;
    border-radius: 5px;
    margin-bottom: 10px;
    border: none;
    background-color: green;
    color: white;
    font-size: 18px;
}

h1{
    position: absolute;
    top: 0%;
    left: 35%;
    z-index: 2;
    font-size: 16px;
    color: gray;
    margin-bottom: 20px;
}

</style>