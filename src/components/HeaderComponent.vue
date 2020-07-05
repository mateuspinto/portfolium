<template>
  <div class="hero-header">
    <div class="container-fluid">
      <div class="container">
        <div class="row">
          <div class="col-lg-12">
            <h1 class="hi">Hi, I'm Mateus Pinto!</h1>
            <p
              class="text-center"
            >I'm a Brazilian redhead computer scientist (currently graduating in Federal University of Viçosa). I mainly work with hardware description, embedded systems and backend development. I work with machine learning and data analysis as well. 🤘</p>
            <div class="text-center">
              <a href="mailto:mateus.p.silva@ufv.br" class="btn btn-primary">
                <i class="fa fa-envelope"></i> Contact Me
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "site-header",
  resource: "SiteHeader"
};
</script>

<style scoped>
.hero-header {
  width: 100%;
  height: 70vh;
  background-image: url("/static/images/header-bg.jpeg");
  background-repeat: no-repeat;
  background-size: cover;
  background-position-y: center;
  font-family: "Raleway", sans-serif;
}

.hero-header .container-fluid {
  background-color: rgba(22, 23, 32, 0.85);
  height: 100%;
  border-top: 1px solid #222222;
  display: flex;
  align-items: center;
}

.hero-header h1.hi {
  color: #dedede;
  padding: 10px;
  font-weight: bolder;
  text-align: center;
}

.hero-header p {
  color: #dedede;
  padding: 15px;
}

@media only screen and (min-device-width: 320px) and (max-device-width: 480px) and (-webkit-min-device-pixel-ratio: 2) {
  .hero-header {
    height: 100vh;
  }

  .hero-header h1.hi {
    text-align: left;
  }

  .corner-ribbon.top-right {
    top: 40px;
    right: -50px;
  }
}

@media only screen and (min-device-width: 320px) and (max-device-width: 800px) and (-webkit-min-device-pixel-ratio: 2) and (orientation: landscape) {
  .hero-header {
    height: 100vh;
  }

  .hero-header h1.hi {
    text-align: left;
  }

  .corner-ribbon.top-right {
    top: 40px;
    right: -50px;
  }
}

.corner-ribbon {
  width: 300px;
  background: #e43;
  position: absolute;
  top: 60px;
  left: -40px;
  text-align: center;
  line-height: 50px;
  letter-spacing: 1px;
  color: #f0f0f0;
  transform: rotate(-45deg);
  -webkit-transform: rotate(-45deg);
  font-weight: 700;
  z-index: 2000;
}

.corner-ribbon.sticky {
  position: fixed;
}

.corner-ribbon.top-right {
  top: 60px;
  right: -70px;
  left: auto;
  transform: rotate(45deg);
  -webkit-transform: rotate(45deg);
}
</style>
