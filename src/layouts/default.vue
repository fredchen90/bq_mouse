<template>
  <div>
    <nuxt />
  </div>
</template>

<style>
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

.button--mouse {
  display: inline-block;
  /* border-radius: 4px; */
  border: 1px solid #CC0040;;
  color: #CC0040;;
  text-decoration: none;
  padding: 10px 30px;
  font-size: 20px;
  line-height: 23px;
  text-align: center;
  margin-right:30px;
  width:160px;
  /* height: 40px; */
}

.button--mouse:hover {
  color: #fff;
  background-color: #CC0040;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}
</style>
