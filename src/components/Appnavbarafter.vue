<template>
<nav class="navbar navbar-inverse navbar-fixed-top">
    <div class="container">
    <!-- Brand and toggle get grouped for better mobile display -->
    <div class="navbar-header">
      <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1" aria-expanded="false">
      <span class="sr-only">Toggle navigation</span>
      <span class="icon-bar"></span>
      <span class="icon-bar"></span>
      <span class="icon-bar"></span>
      </button>
      <a class="navbar-brand" href="#HomeAccount">Reminder</a>
    </div>

    <!-- Collect the nav links, forms, and other content for toggling -->
    <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
      <ul class="nav navbar-nav">
      <li><a href="#Home">Home <span class="sr-only">(current)</span></a></li>
      <li><a href="#Profil">Profile</a></li>       
      <li><a href="#Timeline">Timeline</a></li>        
      </ul>
      <ul class="nav navbar-nav navbar-right">
      <li><a href="#Bantuan">Bantuan</a></li>
      <li class="dropdown">
        <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Account <span class="caret"></span></a>
        <ul class="dropdown-menu">
        <li><a href="#Setting">Setting</a></li>
        <li role="separator" class="divider"></li>
        <li><a href="#Logout">Logout</a></li>
        </ul>
      </li>
      </ul>
    </div><!-- /.navbar-collapse -->
    </div><!-- /.container-fluid -->
  </nav>
</template>
<script>
export default {
  name: 'appnavbarafter',
  props: [],
  data() {
    return {
      
    }
  }
}
</script>
