<template>
  <div>
    <h3>登入</h3>
    帳號:<input
      type="text"
      v-model="loginForm.loginName"
      placeholder="請輸入電話號碼"
    />
    <br /><br />
    密碼:
    <input
      type="password"
      v-model="loginForm.password"
      placeholder="請輸入密碼"
    />
    <br /><br />
    <button>登入</button>
    <a href="/#/register">
      <button>註冊</button>
    </a>
  </div>
</template>

<script>
export default {
  name: "Login", // eslint-disable-line
  data() {
    return {
      loginForm: {
        loginName: "",
        password: "",
      },
      responseResult: [],
    };
  },
  methods: {},
};
</script>
