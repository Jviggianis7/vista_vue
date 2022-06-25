
<template>
<div id="componente">
  <link rel="stylesheet" href="assets/font-awesome/css/font-awesome.min.css">
  <div class="row">
    <div class="col-sm-6 col-sm-offset-3 social-login">
      <h3>{{msg}}</h3>
      <div class="social-login-buttons">
        <a class="btn btn-link-2" href="https://web.facebook.com/" target="_bla">
          <i class="fa fa-facebook" aria-hidden="true"></i> Facebook
        </a>
        <a class="btn btn-link-2" href="https://twitter.com/?lang=es" target="_bla">
          <i class="fa fa-twitter"></i> Twitter
        </a>
        <a class="btn btn-link-2" href="https://myaccount.google.com/intro/profile" target="_bla">
          <i class="fa fa-google-plus"></i> Google Plus
        </a>
      </div>
    </div>
  </div>
</div>
</template>

<script>
export default {
    name: "miComponente3",
    setup() {
        return{
             msg: "...or login with:",
        }
        
    },
}
</script>
