<template>
  <div class="card">
    <div class="card-body info-box">
      <p><i class="fa fa-map-marker info-item"></i> Pará de Minas, MG</p>
      <p><i class="fa fa-envelope info-item"></i> <a href="mailto:mateus.p.silva@ufv.br">mateus.p.silva@ufv.br</a></p>
      <p><i class="fa fa-github-alt info-item"></i> <a href="https://github.com/mateuspinto">github.com/mateuspinto</a></p>
      <p><i class="fa fa-gitlab info-item"></i> <a href="https://gitlab.com/mateuspinto">gitlab.com/mateuspinto</a></p>
      <p><button type="button" class="btn btn-primary btn-lg btn-block"><i class="fa fa-file-pdf-o"></i> Download CV</button></p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'contact-info',
  resource: 'ContactInfo'
}
</script>

<style scoped>

  i.info-item {
    margin-right: 10px;
    color: #325d72;
  }

  .info-box p{
    font-size: 11pt;
  }

  .info-box > p > a {
    text-decoration: none;
    color: #353535;
  }

  .info-box a.btn {
    margin-top: -30px;
    color: #fff;
  }
</style>
