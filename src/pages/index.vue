<template>
  <div class="container">
    <div style="height:60px;width:100%;background:#000;top:0px;position:absolute;">
      <a href="https://zowie.benq.com/en-us" target="_self" style="padding:5px 30px">
                         
                        <svg id="zowie_logo" width="120" height="60" viewBox="0 0 140.625 39.751">
                            <path fill="#D4003B" d="M39.704,33.709H14.245c-4.521,0-8.174-3.66-8.174-8.165c0-4.506,3.653-8.182,8.174-8.182h14.207
                            c1.689,0,3.062-1.367,3.062-3.063c0-1.68-1.373-3.055-3.062-3.055H14.245c-7.891,0-14.307,6.409-14.307,14.3
                            c0,7.882,6.416,14.306,14.307,14.306h25.459c1.688,0,3.055-1.381,3.055-3.07C42.759,35.084,41.392,33.709,39.704,33.709"></path>
                            <path fill="#D4003B" d="M28.467,0H3.001C1.304,0-0.062,1.39-0.062,3.063c0,1.695,1.366,3.07,3.063,3.07h25.466
                            c4.505,0,8.167,3.668,8.167,8.165c0,4.506-3.662,8.182-8.167,8.182H14.253c-1.689,0-3.055,1.375-3.055,3.063
                            c0,1.689,1.366,3.062,3.055,3.062h14.214c7.882,0,14.292-6.416,14.292-14.307C42.759,6.424,36.349,0,28.467,0"></path>
                            <path fill="#FFFFFF" d="M108.688,0v12.856c0,1.719-1.39,3.109-3.102,3.109h-2.578V0h-2.717v15.965h-2.594
                            c-1.705,0-3.093-1.39-3.093-3.109V0h-2.725v12.856c0,3.216,2.61,5.833,5.818,5.833h8.55c3.208,0,5.166-2.617,5.166-5.833V0H108.688z
                            "></path>
                            <path fill="#FFFFFF" d="M79.099,2.74c-3.659,0-6.638,2.978-6.638,6.631c0,3.662,2.979,6.632,6.638,6.632
                            c3.654,0,6.625-2.97,6.625-6.632C85.724,5.718,82.753,2.74,79.099,2.74 M79.099,18.743c-5.172,0-9.37-4.206-9.37-9.372
                            c0-5.157,4.198-9.371,9.37-9.371c5.166,0,9.357,4.214,9.357,9.371C88.456,14.537,84.265,18.743,79.099,18.743"></path>
                            <rect x="116.87" fill="#FFFFFF" width="2.724" height="18.713"></rect>
                            <path fill="#FFFFFF" d="M54.516,14.89c0-0.43,0.231-0.821,0.6-1.028l10.675-6.701l0.046-0.023c1.097-0.722,1.773-1.933,1.773-3.254
                            C67.61,1.751,65.86,0,63.726,0H51.8v2.725h11.926c0.645,0,1.167,0.514,1.167,1.159c0,0.391-0.2,0.745-0.514,0.967L53.795,11.49
                            c-1.229,0.822-1.995,1.988-1.995,3.4c0,2.126,1.734,3.869,3.875,3.869h11.828v-2.718H55.675
                            C55.038,16.041,54.516,15.52,54.516,14.89"></path>
                            <path fill="#FFFFFF" d="M129.411,2.771h11.252V0h-11.252c-2.564,0-4.659,2.095-4.659,4.667v9.371c0,2.571,2.08,4.651,4.651,4.651
                            h11.26v-2.771h-11.26c-1.043,0-1.881-0.837-1.881-1.873v-3.301h13.141v-2.77h-13.141V4.667
                            C127.522,3.623,128.375,2.771,129.411,2.771"></path>
                        </svg>         
                        </a>
    </div>
    <img src="@/assets/images/cover-banner-1920-315.jpg" @click="bannerClick(info)" style="width:100%;height:auto; margin-top:50px;">
    <div class="content">
      <h1 style="color:#B12741;font-size: 30px;line-height: 37px;padding:30px 0;">Set your preference and see the mice you might like.</h1>
      <p style="color:#fff;font-size: 18px;line-height: 22px;">Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium, iure.</p>
    </div>

    <div class="content">
      <ul class="ul-c" style="padding-top: 36px">
        <li style="font-size:16px;line-height:19px;margin:22px 0;">
                <div class="radio-beauty-container">
                 <p style="color:#fff;"><b style="font-weight: bold; font-size: 18px;line-height: 22px;"> Shape：</b>
                <label style="margin: 0 40px">
                    <input type="radio" name="shape" id="radioName1" hidden/>
                    <label for="radioName1" class="radio-beauty"></label>
                    <span class="radio-name">Ergonomic</span>
                </label>
                <label>
                    <input type="radio" name="shape" id="radioName2" hidden/>
                    <label for="radioName2" class="radio-beauty"></label>
                    <span class="radio-name">Ambidextrous</span>
                </label>
                </p>
                </div>
        </li>
        <li >
                <div class="radio-beauty-container">
                 <p style="color:#fff;"><b style="font-weight: bold; font-size: 18px;line-height: 22px;"> Coating：</b>
                <label style="margin: 0 40px">
                    <input type="radio" name="coating" id="radioName3" hidden/>
                    <label for="radioName3" class="radio-beauty"></label>
                    <span class="radio-name">Standard</span>
                </label>
                <label>
                    <input type="radio" name="coating" id="radioName4" hidden/>
                    <label for="radioName4" class="radio-beauty"></label>
                    <span class="radio-name">Glossy</span>
                </label>
                </p>
                </div>
        </li>
      </ul>
      <br>
      <div class="links">
        <a
          href=""
          target="_blank"
          class="button--mouse"
        >
          Search
        </a>
        <a
          href=""
          target="_blank"
          class="button--mouse"
        >
          Clear
        </a>
      </div>
    </div>
    <section>
    <div class="content2" style="background:#000;padding:50px 30px;margin-top:100px;margin-bottom:60px">
      <h1 style="color:#B12741;font-size: 30px;line-height: 37px;padding:30px 0;">Select 2 models to compare.</h1>
      <p style="color:#fff;font-size: 18px;line-height: 22px;">Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium, iure.</p>
      <p style="color:#fff;font-size: 18px;line-height: 22px;">Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium, iure.</p>
      <p style="color:#fff;font-size: 18px;line-height: 22px;">Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium, iure.</p>
      <p style="color:#fff;font-size: 18px;line-height: 22px;">Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium, iure.</p>
      <p style="color:#fff;font-size: 18px;line-height: 22px;">Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium, iure.</p>
      <p style="color:#fff;font-size: 18px;line-height: 22px;">Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium, iure.</p>
      <p style="color:#fff;font-size: 18px;line-height: 22px;">Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium, iure.</p>
    </div>
    </section>

    <section style="padding-top:60px; background:#fff">
    <div class="content">

      //Fred 請幫我塞這邊

    </div>
    </section>

  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'
import Es from '~/config/es.json'
import Eg from '~/config/eg.json'
import As from '~/config/as.json'
import Ag from '~/config/ag.json'

export default {
  components: {
    Logo
  },
  mounted() {
    console.log("Es,Eg,As,Ag: ", Es,Eg,As,Ag);
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  max-width: 1920px;
  /* display: flex; */
  justify-content: center;
  align-items: center;
  /* text-align: center; */
  background:#232323;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
.content {
  width: 1112px;
    /* display: flex; */
  justify-content: center;
  align-items: center;
  text-align: left;
  margin: auto;
}
.content2 {
  width: 1172px;
    /* display: flex; */
  justify-content: center;
  align-items: center;
  text-align: left;
  margin: auto;
}
.ul-c {
  line-height: 60px;
}
.li-c {
  font-style:normal;
  margin: 0 40px;
}
.radio-beauty-container {
  font-size: 19px;
}
.radio-beauty-container .radio-beauty:hover, .radio-beauty-container input[type="radio"]:checked + .radio-beauty {
  background-color: #fff;
  border: #CC0040 5px solid;
  background-clip: content-box;
}
.radio-beauty-container .radio-name {
  vertical-align: middle;
  font-size: 16px;
}
.radio-beauty-container .radio-beauty {
  width: 16px;
  height: 16px;
  box-sizing: border-box;
  display: inline-block;
  border: 1px solid #ccc;
  vertical-align: middle;
  margin: 0 6px 0 6px;
  border-radius: 50%;
}
.radio-beauty-container .radio-beauty:hover {
  /* box-shadow: 0 0 7px #CC0040; */
}
 li {list-style-type:none;}
</style>
