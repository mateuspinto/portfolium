<template>
  <div class="card">
    <h2 class="card-title">Work Experience</h2>
    <div class="card-body">
      <ul class="list-group list-group-flush">

        <li class="list-group-item">
          <span class="title"><strong>Computer Systems Engineering Researcher - </strong> <span class="subtitle"> UBC, LESC (Jan 2019 - Currently)</span></span>
          <p class="description">Working developing a vectorial processor as an accelerator using SystemVerilog and C++. Partnership between the Federal University of Viçosa of Brazil and the University of British Columbia of Canada.</p>
        </li>

        <li class="list-group-item">
          <span class="title"><strong>Intern Data Scientist - </strong> <span class="subtitle"> Cinnecta (Jan 2019 - Dec 2019)</span></span>
          <p class="description">Worked on multiple different projects for <strong>Cinnecta</strong> as data scientist, using different tecnologies like Tensorflow, Docker and Anaconda. I used
           a lot of databases, from binary data to geographic coordinates, showing them in graphics and/or in websites.
          </p>
        </li>

        <li class="list-group-item">
          <span class="title"><strong>Data Science and Machine Learning Researcher - </strong> <span class="subtitle"> NESPeD (Jan 2019 - Dec 2019)</span></span>
          <p class="description">Worked researching improvements in many different algorithms. That worked resulted in two articles: one for KDMile 2019 and the other for SBRC Spring 2019.</p>
        </li>

        <li class="list-group-item">
          <span class="title"><strong>Intern Data Science and Machine Learning Researcher - </strong> <span class="subtitle"> NESPeD (July 2018 - Dec 2018)</span></span>
          <p class="description">Worked researching improvements in many different algorithms. That worked resulted in a analysis of taxi moviment from New York (database from Kaggle).</p>
        </li>

      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'work-experience',
  resource: 'WorkExperience'
}
</script>

<style scoped>
.title {
  color: #325d72;
  font-weight: bolder;
  font-size: 15pt;
}
.subtitle {
  font-size: 13pt;
  color: #858585;
}
.description {
  color: #565656;
  margin-top:10px;
  text-align: justify;
}

</style>
