<template>
  <div id="componente">
    <div class="top-content">
      <div class="inner-bg">
        <div class="container">
          <div class="row">
            <div class="col-sm-8 col-sm-offset-2 text">
              <h1><strong>{{ msg }}</strong> Login Form</h1>
              <div class="description">
                <p>
                  This is a free responsive login form made with Bootstrap. Download
                  it on
                  <a href="http://azmind.com"><strong>AZMIND</strong></a>, customize and use it as you like!
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'miComponente1',
  data() {
    return {
      msg: 'Bootstrap',
    }

  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
@import "../assets/css/style.css";
</style>

