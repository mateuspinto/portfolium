<template>
  <div class="card">
    <h2 class="card-title">Latest Projects</h2>
    <div class="card-body">
      <ul class="list-group list-group-flush">

        <li class="list-group-item">
          <span class="title"><strong>MIPS Dual Core - Patterson and Hennessy design based - </strong> <span class="subtitle"> UBC, LESC</span></span>
          <br/><br/>
          <img src="/static/images/projects/mipspipeline.jpg" width="100%"/>
          <br/><br/>
          <p class="description">Full MIPS processor dual core with pipeline written in SystemVerilog based on the design from "Computer Organization and Design MIPS Edition - 5th Edition" of David Patterson John Hennessy. Simulation only.</p>
          <div class="pull-right">
            <a href="https://gitlab.com/mateuspinto/simplified-dualcore-mips" target="_blank" class="btn btn-warning"><i class="fa fa-gitlab"></i> VIEW ON GITLAB</a>
          </div>
        </li>

        <li class="list-group-item">
          <div class="row">
            <div class="col-md-4">
              <img src="/static/images/projects/mips.png" width="100%"/>
            </div>
            <div class="col-md-8">
              <span class="title"><strong>MIPS without pipeline - Patterson and Hennessy design based - </strong> <span class="subtitle">Federal University of Viçosa</span></span>
              <p class="description">A very simplified MIPS processor one cycled written in SystemVerilog based on the design from "Computer Organization and Design MIPS Edition - 5th Edition" of David Patterson John Hennessy. Includes implementation of code in Intel De2-155 FPGA.</p>
              <div class="pull-right">
                <a href="https://github.com/mateuspinto/FPGA_SystemVerilog_Non-Pipeline_MIPS_Processor-TP2-OC1-UFV" target="_blank" class="btn btn-warning"><i class="fa fa-github"></i> VIEW ON GITHUB</a>
              </div>
            </div>
          </div>
        </li>

        <li class="list-group-item">
          <div class="row">
            <div class="col-md-4">
              <img src="/static/images/projects/alma.jpg" width="100%"/>
            </div>
            <div class="col-md-8">
              <span class="title"><strong>ALMa - Mips Mounter and Linkeditor - </strong> <span class="subtitle"> Federal University of Viçosa</span></span>
              <p class="description">ALMa is an advanced linkeditor and MIPS assembber written in Python Object Oriented that can turn MIPS assembly code into binary, no matter if it has function calls or not. All currently MIPS assembly functions are supported.</p>
              <div class="pull-right">
                <a href="https://github.com/mateuspinto/ALMa_Mips_Mounter_and_Link_Editor-TP1-OC1-UFV" target="_blank" class="btn btn-warning"><i class="fa fa-github"></i> VIEW ON GITHUB</a>
              </div>
            </div>
          </div>
        </li>

        <li class="list-group-item">
          <div class="row">
            <div class="col-md-4">
              <img src="/static/images/projects/cache.jpg" width="100%"/>
            </div>
            <div class="col-md-8">
              <span class="title"><strong>Cache with writeback for MIPS - </strong> <span class="subtitle"> UBC, Lesc</span></span>
              <p class="description">Full cache implementation based on "Computer Organization and Design MIPS Edition - 5th Edition" of David Patterson John Hennessy for MIPS.</p>
             <div class="pull-right">
               <a href="https://gitlab.com/mateuspinto/simplified-cache-controller-for-mips" target="_blank" class="btn btn-warning"><i class="fa fa-gitlab"></i> VIEW ON GITLAB</a>
             </div>
            </div>
          </div>
        </li>

        <li class="list-group-item">
          <div class="row">
            <div class="col-md-4">
              <img src="/static/images/projects/kdmile2019.jpg" width="100%"/>
            </div>
            <div class="col-md-8">
              <span class="title"><strong> KDMile 2019 - Extracting the relationship between census data and mobile devices - </strong> <span class="subtitle"> NESPeD</span></span>
              <p class="description">In the recent years, we are facing an increasing in the number of mobile users and, consequently, on the amount of data collected from them and available to the industry. Therefore, companies are willing to use such data to discover insights that may help them on providing better and more personalized services. In this work, we explore mobile and census data of thousands of users in Brazil to understand how their local of residence is correlated to their smartphones.</p>
              <div class="pull-right">
                <a class="btn btn-danger pull-right" href="/static/pdf/KDMILE2019.pdf" target="_blank"><i class="fa fa-file-pdf-o"></i> Download PDF</a>
              </div>
            </div>
          </div>
        </li>

        <li class="list-group-item">
          <div class="row">
            <div class="col-md-4">
              <img src="/static/images/projects/sbrc2020.jpg" width="100%"/>
            </div>
            <div class="col-md-8">
              <span class="title"><strong>SBRC 2020 - Impact of the use of demographic information for the recommendation of mobile applications - </strong> <span class="subtitle"> NESPeD</span></span>
              <p class="description">In the recent years, we are facing a significative increase in the number of mobile devices and applications. Given the large number of available applications, users have difficult to select applications to install. On the other hand, applications’ providers have difficult to select users and target their advertisement to increase the convertion rate. A possible solution to mitigate these problems rely on using recommendation algorithms to recommend applications to users. In this work, we propose a solution to recommend applications based on the similarities of users and applications, as well as on the demographic information of the users’ region of residence. We evaluate our proposal on realdata from 7406 users, and the results reveal an improvement up to 14% when comparing to a traditional solution that does not rely on the demographic information. In addition, the potential conversion rate increases by up to 30 times when compared to samples of users taken randomly.</p>
              <div class="pull-right">
                <a class="btn btn-danger pull-right" href="/static/pdf/SBRC2020.pdf" target="_blank"><i class="fa fa-file-pdf-o"></i> Download PDF</a>
              </div>
            </div>
          </div>
        </li>

        <li class="list-group-item">
          <div class="row">
            <div class="col-md-4">
              <img src="/static/images/projects/jupyterhub.png" width="100%"/>
            </div>
            <div class="col-md-8">
              <span class="title"><strong>JupyterHub in Docker - </strong> <span class="subtitle"> Cinnecta</span></span>
              <p class="description">Full JupyterHub Docker image with all Anaconda Python3 base packages for multi-developer encoding in a cluster, with individual file environments and a shared folder among all, plus PySpark library.</p>
              <div class="pull-right">
                <a href="https://github.com/mateuspinto/JupyterHub_Configurado_Docker" target="_blank" class="btn btn-warning"><i class="fa fa-github"></i> VIEW ON GITHUB</a>
              </div>
            </div>
          </div>
        </li>

      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'projects',
  resource: 'Projects'
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
.list-group-item img {
  border: 1px solid rgba(0,0,0,.125);
}
@media only screen
and (min-device-width: 320px)
and (max-device-width: 480px) {
  .oss-tag {
    display: none;
  }
}
</style>
