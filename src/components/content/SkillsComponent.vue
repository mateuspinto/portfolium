<template>
  <div class="card">
    <h2 class="card-title">Skills</h2>
    <div clasS="card-body">
      <div class="skill-container">
        <p class="label"><span class="skill">Maths</span> <span class="pull-right level">Master</span></p>
        <div class="progress">
          <div class="progress-bar progress-bar-striped bg-info" role="progressbar" style="width: 91%" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
        </div>
      </div>

      <div class="skill-container">
        <p class="label"><span class="skill">SystemVerilog</span> <span class="pull-right level">Master</span></p>
        <div class="progress">
          <div class="progress-bar progress-bar-striped bg-info" role="progressbar" style="width: 85%" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
        </div>
      </div>

      <div class="skill-container">
        <p class="label"><span class="skill">C++</span> <span class="pull-right level">Expert</span></p>
        <div class="progress">
          <div class="progress-bar progress-bar-striped bg-info" role="progressbar" style="width: 75%" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
        </div>
      </div>

      <div class="skill-container">
        <p class="label"><span class="skill">Python (ML stuff)</span> <span class="pull-right level">Expert</span></p>
        <div class="progress">
          <div class="progress-bar progress-bar-striped bg-info" role="progressbar" style="width: 70%" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
        </div>
      </div>

      <div class="skill-container">
        <p class="label"><span class="skill">Docker</span> <span class="pull-right level">Adept</span></p>
        <div class="progress">
          <div class="progress-bar progress-bar-striped bg-info" role="progressbar" style="width: 52%" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
        </div>
      </div>

      <div class="skill-container">
        <p class="label"><span class="skill">Express.js</span> <span class="pull-right level">Novice</span></p>
        <div class="progress">
          <div class="progress-bar progress-bar-striped bg-info" role="progressbar" style="width: 30%" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
        </div>
      </div>

      <div class="skill-container">
        <p class="label"><span class="skill">Vue.js (what this site was made of)</span> <span class="pull-right level">Novice</span></p>
        <div class="progress">
          <div class="progress-bar progress-bar-striped bg-info" role="progressbar" style="width: 22%" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
        </div>
      </div>

    </div>
  </div>
</template>

<script>
export default {
  name: 'skills',
  resource: 'Skills'
}
</script>

<style scoped>
.label {
  margin-bottom: 1px;
}

.level {
  font-size: 10pt;
  color: #909090;
}

.level2 {
  font-size: 8pt;
  color: #909090;
}

.skill {
  font-weight: bolder;
}

.skill-container {
  margin-bottom: 20px;
}
</style>
