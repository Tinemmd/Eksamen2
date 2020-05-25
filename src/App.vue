<template>
  <div id="app">
    <div id="nav">
      <div id="navigation">
        <router-link to="/">Home</router-link>
        <router-link to="/washhands">Guidelines</router-link>
        <router-link to="/covid">Covid-19</router-link>
      </div>
    </div>
    <router-view/>
  </div>
</template>

<style lang="scss">

$color-primary: #AF182E;
$color-secondary: #000000;
$font-primary: 'Futura';
$font-secondary: 'Open Sans Condensed', sans-serif,;

@mixin flexCenter($direction) {
  display:flex;
  justify-content: center;
  align-items: center;
  flex-direction: $direction;
}

#app {
  text-align: center;
}

#nav {
  display: flex;
  align-items: flex-end;
  padding-left: 100px;
  height: 100px;
  width: 100%;

  a {
    font-weight: medium;
    color: $color-secondary;
    text-decoration: none;
    font-family: $font-primary;
    font-size: 22px;

    &.router-link-exact-active {
      color: $color-primary;
    }
  }
}

#navigation {
  width: 40%;
  display: flex;
  justify-content: space-between;
}
</style>
