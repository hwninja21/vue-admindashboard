<template>
    <nav class="navbar navbar-vertical fixed-left navbar-expand-md navbar-light bg-white sidebar-left" id="sidenav-main">
        <div class="container-fluid">

            <!--Toggler-->
            <navbar-toggle-button @click.native="showSidebar">
                
            </navbar-toggle-button>
            <router-link class="navbar-brand" to="/">
                <img :src="logo" class="navbar-brand-img" alt="...">
                <span style="color: white; font-size: 18px;"> Evolving Project  <b-icon class="search-icon" icon="search"></b-icon></span>
            </router-link>

             

            <!-- <slot name="mobile-right">
                <ul class="nav align-items-center d-md-none">
                    <base-dropdown class="nav-item" menu-on-right tag="li" title-tag="a">
                        <a slot="title-container" class="nav-link nav-link-icon" href="#" role="button"
                           aria-haspopup="true" aria-expanded="false">
                            <i class="ni ni-bell-55"></i>
                        </a>

                        <a class="dropdown-item" href="#">Action</a>
                        <a class="dropdown-item" href="#">Another action</a>
                        <div class="dropdown-divider"></div>
                        <a class="dropdown-item" href="#">Something else here</a>
                    </base-dropdown>
                    <base-dropdown class="nav-item" menu-on-right tag="li" title-tag="a">
                        <a slot="title-container" class="nav-link" href="#" role="button">
                            <div class="media align-items-center">
                              <span class="avatar avatar-sm rounded-circle">
                                <img alt="Image placeholder" src="img/theme/team-1.jpg">
                              </span>
                            </div>
                        </a>

                        <div class=" dropdown-header noti-title">
                            <h6 class="text-overflow m-0">Welcome!</h6>
                        </div>
                        <router-link to="/profile" class="dropdown-item">
                            <i class="ni ni-single-02"></i>
                            <span>My profile</span>
                        </router-link>
                        <router-link to="/profile" class="dropdown-item">
                            <i class="ni ni-settings-gear-65"></i>
                            <span>Settings</span>
                        </router-link>
                        <router-link to="/profile" class="dropdown-item">
                            <i class="ni ni-calendar-grid-58"></i>
                            <span>Activity</span>
                        </router-link>
                        <router-link to="/profile" class="dropdown-item">
                            <i class="ni ni-support-16"></i>
                            <span>Support</span>
                        </router-link>
                        <div class="dropdown-divider"></div>
                        <a href="#!" class="dropdown-item">
                            <i class="ni ni-user-run"></i>
                            <span>Logout</span>
                        </a>
                    </base-dropdown>
                </ul>
            </slot> -->
            <slot></slot>
            <div v-show="$sidebar.showSidebar" class="navbar-collapse collapse show" id="sidenav-collapse-main">

                
                <div class="navbar-collapse-header d-md-none">
                
                    <div class="row">
                    
                        <div class="col-6 collapse-brand">
                       
                            <router-link to="/">
                                <img :src="logo">
                            </router-link>
                        </div>
                        
                        <div class="col-6 collapse-close">
                            <navbar-toggle-button @click.native="closeSidebar"></navbar-toggle-button>
                        </div>
                         
                    </div>
                </div>


                
                

                <ul class="navbar-nav">
                <div class="col-12 sidebar-profile">
                  <img :src="profile" alt="profile" class="profile-img"/>
                  <span class="profile-text">Elena Cupisti LA MIA GILDA </span>
                  <b-icon class="three-dots" icon="three-dots"></b-icon>
                </div>

                <div class="row progress-count">
                   <div class="col-6">
                   <h4 class="progress-number">100</h4>
                   <p class="progress-text"><b>Scopi raggiunti</b></p>
                </div>
                <div class="col-6">
                   <h4 class="progress-number">5</h4>
                   <p class="progress-text"><b>Scopi in progress</b></p>
                </div>
                </div>

                <div class="col-12 sidebar-section">
                  <h6 class="navbar-heading text-muted sidebar-headings">DASHBOARD</h6>
                 
                  <ul class="navbar-nav mb-md-3">
                      <li class="nav-item">
                          <a class="nav-link sidebar-nav-link"
                            href="#">
                              Aree di influenza
                          </a>
                      </li>
                      <li class="nav-item">
                          <a class="nav-link sidebar-nav-link"
                            href="#">
                              Manuale
                          </a>
                      </li>
                      <li class="nav-item">
                          <a class="nav-link sidebar-nav-link"
                            href="#">
                              Notifiche <span class="sidebar-notification">3</span>
                          </a>
                      </li>
                  </ul>
                </div>
                 
                 <div class="col-12 sidebar-section"> 
                     <h6 class="navbar-heading text-muted sidebar-headings">IL MIO VIAGGIO</h6>
                    
                 </div>
                 <slot name="links">
                    </slot>
                    <div class="col-12">
                    <span class="sidebar-sub-headings">+ Aggiungi Scopo</span>
                    </div>
                </ul>
                <!--Heading-->
                <h6 class="navbar-heading text-muted sidebar-headings">GILDE DI CUI FAI PARTE</h6>
                <!--Navigation-->
                <ul class="navbar-nav mb-md-3">
                        <li class="nav-item">
                            <a class="nav-link sidebar-nav-link"
                              href="#">
                                GRAFICI <span class="sidebar-team-img"><img :src="img1"/> <img :src="img2"/> <img :src="img3"/></span>
                            </a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link sidebar-nav-link"
                              href="#">
                                SEO <span class="sidebar-team-img"><img :src="img2"/> <img :src="img3"/></span>
                            </a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link sidebar-nav-link"
                              href="#">
                                COMUNICAZIONE <span class="sidebar-team-img1"><img :src="img1"/> <img :src="img3"/></span>
                            </a>
                        </li>
                  </ul>

                  <div class="col-12">
                    <span class="sidebar-sub-headings">+ Aggiungi Gilda</span>
                    </div>
                  <!--Heading-->
                <h6 class="navbar-heading text-muted sidebar-headings">GILDE CHE HAI CREATO</h6>
                <!--Navigation-->
                <ul class="navbar-nav mb-md-3">
                        <li class="nav-item">
                            <a class="nav-link sidebar-nav-link"
                              href="#">
                                WEB MARKETING <span class="sidebar-team-img"><img :src="img1"/> <img :src="img2"/> <img :src="img3"/></span>
                            </a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link sidebar-nav-link"
                              href="#">
                                RUNNING <span class="sidebar-team-img"><img :src="img2"/> <img :src="img3"/></span>
                            </a>
                        </li>
                        
                  </ul>

                  <div class="col-12">
                    <span class="sidebar-sub-headings">+ Crea la tua Gilda</span>
                  </div>

                  <div class="col-12">
                    <span><span class="sidebar-para">Condividi I tuoi </span><span class="sidebar-second-para">traguardi con la community!</span></span>
                  </div>
            </div>
            </div>
    </nav>
</template>
<script>
  import NavbarToggleButton from '@/components/NavbarToggleButton'

  export default {
    name: 'sidebar',
    components: {
      NavbarToggleButton
    },
    props: {
      logo: {
        type: String,
        default: 'img/admin/newlogo_Tavola_disegno_1_copia.png',
        description: 'Sidebar app logo'
      },
      profile: {
        type: String,
        default: 'img/admin/Mask.png',
        description: 'Profile image'
      },
      img1: {
        type: String,
        default: 'img/admin/Oval_db.png',
        description: 'Profile image'
      },
      img2: {
        type: String,
        default: 'img/admin/Oval_dc.png',
        description: 'Profile image'
      },
      img3: {
        type: String,
        default: 'img/admin/Oval_dd.png',
        description: 'Profile image'
      },
      autoClose: {
        type: Boolean,
        default: true,
        description: 'Whether sidebar should autoclose on mobile when clicking an item'
      }
    },
    provide() {
      return {
        autoClose: this.autoClose
      };
    },
    methods: {
      closeSidebar() {
        this.$sidebar.displaySidebar(false)
      },
      showSidebar() {
        this.$sidebar.displaySidebar(true)
      }
    },
    beforeDestroy() {
      if (this.$sidebar.showSidebar) {
        this.$sidebar.showSidebar = false;
      }
    }
  };
</script>
