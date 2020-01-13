<template>
 <div class="container-fluid footer">
    <div class="container col-md-12">
      <div class="text-center">
        Copyright &copy; 2020 - Mateus Pinto da Silva
        <span class="footer-links">
          <a class="fa fa-envelope" href="mailto:mateus.p.silva@ufv.br" target="_blank"></a> &nbsp;
          <a class="fa fa-github" href="https://github.com/mateuspinto" target="_blank"></a> &nbsp;
          <a class="fa fa-gitlab" aria-hidden="true" href="https://gitlab.com/mateuspinto" target="_blank"></a> &nbsp;
        </span>
      </div>
    </div>
 </div>
</template>

<script>
export default {
  name: 'site-footer',
  resource: 'SiteFooter'
}
</script>

<style scoped>
  .footer {
    background-color: #383838;
    height: 50px;
    margin-top: 20px;
    color: #DEDEDE;
    font-family: 'Raleway', sans-serif;
    line-height: 50px;
    font-size: 10pt;
  }

  .footer-links {
    margin-left: 10px;
  }

  .footer-links a{
    color: #f4f4f4;
    font-size: 16pt;
  }

  .footer-links a:hover{
    text-decoration: none;
    color: #ffffff;
  }

  @media only screen
  and (min-device-width: 320px)
  and (max-device-width: 480px)
  and (-webkit-min-device-pixel-ratio: 2) {
    .footer-links .twitter-icon {
      display: none;
    }
  }

</style>
