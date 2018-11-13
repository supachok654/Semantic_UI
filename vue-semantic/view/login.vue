<template>
  <sui-grid
    :columns="7"
    relaxed="very"
    stackable
    vertical-align="middle"
  >
    <sui-grid-column></sui-grid-column>
    <sui-grid-column></sui-grid-column>
    <sui-grid-column></sui-grid-column>
    <sui-grid-column text-align="center" class="aligned basic">
      <div class="ui form">
        <div class="field">
          <label>Username</label>
          <div class="ui left icon input">
            <input
              type="text"
              placeholder="Username"
              autocomplete="off"
              :style="`background-image: url(${image});`"
              class="center aligned basic segment"
            >
            <i class="user icon"></i>
          </div>
        </div>
        <div class="field">
          <label>Password</label>
          <div class="ui left icon input">
            <input
              type="password"
              placeholder="Password"
              autocomplete="off"
              :style="`background-image: url(${image});`"
            >
            <i class="lock icon"></i>
          </div>
        </div>
        <div class="ui orange submit button">Login</div>
        <div class="ui orange labeled icon button">
          <i class="signup icon"></i>
          Sign Up
        </div>
      </div>
    </sui-grid-column>
  </sui-grid>
</template>

<script>
export default {
  name: 'VVLogin',
  data() {
  },
};
</script>

<style scoped>
body{
    margin: 0;
    padding: 0;
    overflow-x: hidden;
    min-width: 320px;
    background: #f6f7eb;
    font-family: Lato,'Helvetica Neue',Arial,Helvetica,sans-serif;
    font-size: 14px;
    line-height: 1.4285em;
    color: rgba(0,0,0,.87);
    font-smoothing: antialiased;
}
</style>

