<template>
  <div>
    <h3>註冊</h3>
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
    <button>確認</button>
    <a href="/#/login">
      <button>返回</button>
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
