<template>
  <div>

    
    <!-- <base-header class="pb-6 pb-8 pt-5 pt-md-8 ">
      
      <b-row>
        <b-col xl="3" md="6">
          <stats-card title="Total traffic"
                      type="gradient-red"
                      sub-title="350,897"
                      icon="ni ni-active-40"
                      class="mb-4">

            <template slot="footer">
              <span class="text-success mr-2">3.48%</span>
              <span class="text-nowrap">Since last month</span>
            </template>
          </stats-card>
        </b-col>
        <b-col xl="3" md="6">
          <stats-card title="Total traffic"
                      type="gradient-orange"
                      sub-title="2,356"
                      icon="ni ni-chart-pie-35"
                      class="mb-4">

            <template slot="footer">
              <span class="text-success mr-2">12.18%</span>
              <span class="text-nowrap">Since last month</span>
            </template>
          </stats-card>
        </b-col>
        <b-col xl="3" md="6">
          <stats-card title="Sales"
                      type="gradient-green"
                      sub-title="924"
                      icon="ni ni-money-coins"
                      class="mb-4">

            <template slot="footer">
              <span class="text-danger mr-2">5.72%</span>
              <span class="text-nowrap">Since last month</span>
            </template>
          </stats-card>

        </b-col>
        <b-col xl="3" md="6">
          <stats-card title="Performance"
                      type="gradient-info"
                      sub-title="49,65%"
                      icon="ni ni-chart-bar-32"
                      class="mb-4">

            <template slot="footer">
              <span class="text-success mr-2">54.8%</span>
              <span class="text-nowrap">Since last month</span>
            </template>
          </stats-card>
        </b-col>
      </b-row>
    </base-header> -->

    <!--Charts-->
    <b-container fluid class="mt-7">
      <b-row>
        <b-col xl="8" class="mb-5 mb-xl-0">
        <b-alert show dismissible variant="danger">
          CONFERMA LA TUA MAIL, INIZIA IL TUO VIAGGIO! <b>&rArr;</b>
        </b-alert>
          <card header-classes="bg-transparent">
            <h1>Scopi raggiunti</h1>
            <b-row>
              <b-col cols="12" md="6">
                  <h1 class="dashboard-counter">100</h1>
              </b-col>
              <b-col cols="12" md="6">
                <svg class="Fill_1" viewBox="0 0 379.608 126.445">
                  <path id="Fill_1" d="M 130.2673034667969 0 C 108.9534912109375 0 101.4509887695312 17.44330215454102 94.19483947753906 34.31229782104492 C 86.62067413330078 51.92301559448242 79.46754455566406 92.75191497802734 57.81555557250977 92.75191497802734 C 37.70438003540039 92.75191497802734 21.30861854553223 78.01697540283203 10.39752101898193 95.91167449951172 C 2.321695804595947 109.1567993164062 0.1291743069887161 122.2323913574219 0.03959222510457039 122.7812652587891 C -0.2425913363695145 124.5147933959961 1.013797402381897 126.1381149291992 2.845751047134399 126.4051361083984 C 3.000280141830444 126.4284439086914 3.15704870223999 126.4432830810547 3.309338331222534 126.4453964233398 L 3.43251371383667 126.4453964233398 C 5.022595882415771 126.4199676513672 6.42455530166626 125.2989044189453 6.679864406585693 123.7497482299805 C 6.700020313262939 123.626838684082 8.814157485961914 111.157341003418 16.31441688537598 98.93156433105469 C 26.09006309509277 82.99502563476562 40.055908203125 98.93156433105469 57.81555557250977 98.93156433105469 C 83.98472595214844 98.93156433105469 92.71450042724609 54.6186637878418 100.4185562133789 36.71125411987305 C 107.4216384887695 20.42292594909668 113.4706649780273 6.355541706085205 130.2673034667969 6.355541706085205 C 148.4591827392578 6.355541706085205 152.6426696777344 18.19562530517578 157.48681640625 31.89850425720215 C 161.9054565429688 44.40614318847656 166.9153442382812 58.58584594726562 185.4633026123047 58.58584594726562 C 201.0237121582031 58.58584594726562 207.435546875 64.33953094482422 214.2213897705078 70.43228912353516 C 221.2177581787109 76.71365356445312 229.1457672119141 83.83211517333984 246.8785400390625 83.83211517333984 C 266.0894165039062 83.83211517333984 270.378173828125 70.30513763427734 273.8248291015625 59.43565368652344 C 277.5492248535156 47.69093322753906 280.45166015625 40.491943359375 292.6796264648438 40.491943359375 C 306.2109985351562 40.491943359375 310.3788146972656 51.43983459472656 315.19384765625 68.14141082763672 C 318.6808166503906 80.24003601074219 322.2887573242188 92.75191497802734 334.2927551269531 92.75191497802734 C 368.0517578125 92.75191497802734 372.7346496582031 122.427360534668 372.9183044433594 123.6840591430664 C 373.1422424316406 125.2798309326172 374.5867614746094 126.4432830810547 376.2440185546875 126.4432830810547 C 376.391845703125 126.4432830810547 376.5419006347656 126.4348068237305 376.689697265625 126.4157333374023 C 378.5306091308594 126.1868515014648 379.8228454589844 124.5868453979492 379.5787353515625 122.8469619750977 C 379.5272216796875 122.4824600219727 374.0067138671875 86.39425659179688 334.2927551269531 86.39425659179688 C 327.8831481933594 86.39425659179688 325.2494201660156 78.86466217041016 321.6751098632812 66.46722412109375 C 317.5229797363281 52.06288528442383 312.3540954589844 34.13640213012695 292.6796264648438 34.13640213012695 C 274.8326416015625 34.13640213012695 270.8775939941406 46.60589218139648 267.3905944824219 57.61100387573242 C 263.4848327636719 69.92579650878906 260.4031982421875 77.47445678710938 246.8785400390625 77.47445678710938 C 231.8242797851562 77.47445678710938 225.8110809326172 72.07256317138672 218.8415985107422 65.82086181640625 C 211.7466888427734 59.44836807250977 203.7044677734375 52.22606658935547 185.4633026123047 52.22606658935547 C 172.4134368896484 52.22606658935547 168.7540130615234 43.73434829711914 163.8561096191406 29.88312530517578 C 159.1530456542969 16.57018280029297 153.2966156005859 0 130.2673034667969 0 Z">
                  </path>
                </svg>
              </b-col>
            </b-row>
          </card>
           <br/>
          <b-row>
             <b-col cols="12" md="6">
             <card header-classes="bg-transparent" class="text-center" style="height: 300px;">
               <div>
                    <h1>Scopi in progress</h1>

                      <div id="Chart_d">
                        <svg class="Oval_d">
                          <ellipse id="Oval_d" rx="75" ry="75" cx="75" cy="75">
                          </ellipse>
                        </svg>
                        <svg class="Oval_ea" viewBox="0 0 150 150">
                          <path id="Oval_ea" d="M 55.59338760375977 147.4264678955078 C 15.59335803985596 136.7084808349609 -8.144436836242676 95.59342193603516 2.573538780212402 55.59338760375977 C 13.29151439666748 15.59335803985596 54.40658187866211 -8.144436836242676 94.40660858154297 2.573538780212402 C 134.4066467285156 13.29151439666748 158.1444396972656 54.40658187866211 147.4264678955078 94.40660858154297 C 136.7084808349609 134.4066467285156 95.59342193603516 158.1444396972656 55.59338760375977 147.4264678955078 Z">
                          </path>
                        </svg>
                        <div id="ID62">
                          <span>62%</span>
                        </div>
                      </div>
                 </div>
             </card>
                 
             </b-col>
             <b-col cols="12" md=6>
             <card header-classes="bg-transparent" class="text-center" style="height: 300px;">
                 <div>
                  <h1>Abiettivi realizzati</h1>
                  <div id="Chart">
                    <svg class="Oval_dy">
                      <ellipse id="Oval_dy" rx="75" ry="75" cx="75" cy="75">
                      </ellipse>
                    </svg>
                    <svg class="Oval_dz" viewBox="0 0 150 150">
                      <path id="Oval_dz" d="M 55.59338760375977 147.4264678955078 C 15.59335803985596 136.7084808349609 -8.144436836242676 95.59342193603516 2.573538780212402 55.59338760375977 C 13.29151439666748 15.59335803985596 54.40658187866211 -8.144436836242676 94.40660858154297 2.573538780212402 C 134.4066467285156 13.29151439666748 158.1444396972656 54.40658187866211 147.4264678955078 94.40660858154297 C 136.7084808349609 134.4066467285156 95.59342193603516 158.1444396972656 55.59338760375977 147.4264678955078 Z">
                      </path>
                    </svg>
                    <div id="ID47">
                      <span>47%</span>
                    </div>
                  </div>
                </div>
             </card>
             </b-col>
          </b-row>
          <br/>
          <b-row>
             <b-col>
                   <card header-classes="bg-transparent">
            <h1>Notifiche</h1>
            <b-alert show variant="secondary">
              <b-form-checkbox
                id="checkbox-1"
                v-model="status"
                name="checkbox-1"
                value="accepted"
                unchecked-value="not_accepted"
              >
                 <h4 class="alert-heading">Come avete fatto ad acquisire più follower di qualità?</h4>
              <p>
                <img :src="img5" alt="Image 5"/>
                <span class="notification-alert">WEB MARKETING</span>
              </p>
              </b-form-checkbox>
            </b-alert>

            <b-alert show variant="secondary">
              <b-form-checkbox
                id="checkbox-2"
                v-model="status"
                name="checkbox-2"
                value="accepted"
                unchecked-value="not_accepted"
              >
                 <h4 class="alert-heading">Tabella per aumentare capacità respiratoria disponibile!</h4>
              <p>
                <img :src="img6" alt="Image 6"/>
                <span class="notification-alert-two">RUNNING</span>
              </p>
              </b-form-checkbox>
            </b-alert>
          </card>
             </b-col>
          </b-row>
        </b-col>

        <b-col xl="4" class="mb-5 mb-xl-0">
          <card header-classes="bg-transparent">
            <b-row align-v="center" slot="header">
              <b-col>
                <h1 class="mb-0">Azioni/Attivita</h1>
                <h4 class="text-uppercase text-muted ls-1 mb-1">OGGI</h4>
              </b-col>
              
            </b-row>

            <b-row>
            <b-col cols="2">
            <div class="sidebar-check"><b-icon icon="check" aria-hidden="true"></b-icon></div>
            <span class="hr-line"></span>
            </b-col>
            <b-col cols="10">
                  <p><b>Darika Samak mark as done Listing on Product Hunt</b></p>
                  <p>8:40 PM</p>
              </b-col>
            </b-row>
            <b-row>
            <b-col cols="2">
            <div class="sidebar-chat"><b-icon icon="chat-left-fill" aria-hidden="true"></b-icon></div>
            </b-col>
            <b-col cols="10">
                  <p><b>Emilee Simchenko commented on Account for teams and personal in bottom style</b></p>
                  <p>7:32 PM</p>
              </b-col>
            </b-row>
            <b-row>
            <b-col cols="2">
            <div class="sidebar-download"><b-icon icon="download" aria-hidden="true"></b-icon></div>
            </b-col>
            <b-col cols="10">
                  <p><b>Darika Samak uploaded 4 files on An option to search in current projects or in all projects</b></p>
                  <p>6:02 PM</p>
                  <div class="notification-imgs">
                  <img :src="img4" alt="img1"/>
                  <img :src="img2" alt="img1"/>
                  <img :src="img3" alt="img1"/>
                  <img :src="img4" alt="img1"/>
                  </div>
              </b-col>
            </b-row>
            <h4 class="text-uppercase text-muted ls-1 mb-1">IERI</h4>
            <b-row>
            <b-col cols="2">
            <div class="sidebar-check"><b-icon icon="check" aria-hidden="true"></b-icon></div>
            <span class="hr-line"></span>
            </b-col>
            <b-col cols="10">
                  <p><b>Darika Samak mark as done Listing on Product Hunt</b></p>
                  <p>8:40 PM</p>
                  <div class="notification-imgs">
                  <img :src="img4" alt="img1"/>
                  <img :src="img2" alt="img1"/>
                  <img :src="img3" alt="img1"/>
                  <img :src="img4" alt="img1"/>
                  </div>
              </b-col>
            </b-row>
            <b-row>
            <b-col cols="2">
            <div class="sidebar-check"><b-icon icon="check" aria-hidden="true"></b-icon></div>
            
            </b-col>
            <b-col cols="10">
                  <p><b>Darika Samak mark as done Listing on Product Hunt</b></p>
                  <p>8:40 PM</p>
              </b-col>
            </b-row>
            <b-row>
            <b-col cols="2">
            <div class="sidebar-check"><b-icon icon="check" aria-hidden="true"></b-icon></div>
            </b-col>
            <b-col cols="10">
                  <p><b>Darika Samak mark as done Listing on Product Hunt</b></p>
                  <p>8:40 PM</p>
                  
              </b-col>
            </b-row>
          </card>
        </b-col>
      </b-row>
      <!-- End charts-->

      
    </b-container>

  </div>
</template>
<script>
  // Charts
  import * as chartConfigs from '@/components/Charts/config';
  import LineChart from '@/components/Charts/LineChart';
  import BarChart from '@/components/Charts/BarChart';

  // Components
  import BaseProgress from '@/components/BaseProgress';
  import StatsCard from '@/components/Cards/StatsCard';

  // Tables
  import SocialTrafficTable from './Dashboard/SocialTrafficTable';
  import PageVisitsTable from './Dashboard/PageVisitsTable';

  export default {
    components: {
      LineChart,
      BarChart,
      BaseProgress,
      StatsCard,
      PageVisitsTable,
      SocialTrafficTable
    },
    props: {
      img1:{
        type: String,
        default: 'img/admin/Image.png',
        description: 'Image 1'
      },
      img2:{
        type: String,
        default: 'img/admin/Image_bq.png',
        description: 'Image 2'
      },
      img3:{
        type: String,
        default: 'img/admin/Image_br.png',
        description: 'Image 3'
      },
      img4:{
        type: String,
        default: 'img/admin/Image_bs.png',
        description: 'Image 4'
      },
      img5: {
        type: String,
        default: 'img/admin/Pic.png',
        description: 'Image 5'
      },
      img6: {
        type: String,
        default: 'img/admin/Pic_dn.png',
        description: 'Image 6'
      }
    }
  };
</script>
<style>
.el-table .cell{
  padding-left: 0px;
  padding-right: 0px;
}
</style>
