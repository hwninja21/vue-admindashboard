<template>
<b-container class="admin-header">
       <b-row>
         <b-col cols="12" md="6">
              <div class="header-section-one">
              <h1>Ciao Elena</h1>
              <button class="profile-setting"><span class="setting-button"><b-icon icon="gear-fill" aria-hidden="true"></b-icon></span> Impostazioni del profilo</button>
              </div>
         </b-col>
         <b-col cols="12" md="6">
           <div class="header-btn-group">
               <button class="header-btn-one">EVOLVING DICE</button>
               <button class="header-btn-two">PROPULSORI DELLA STORL</button>
           </div>
         </b-col>
       </b-row>
    </b-container>
</template>
<script>
import { CollapseTransition } from 'vue2-transitions';
import { BaseNav, Modal } from '@/components';

export default {
  components: {
    CollapseTransition,
    BaseNav,
    Modal
  },
  props: {
    type: {
      type: String,
      default: 'default', // default|light
      description: 'Look of the dashboard navbar. Default (Green) or light (gray)'
    }
  },
  computed: {
    routeName() {
      const { name } = this.$route;
      return this.capitalizeFirstLetter(name);
    }
  },
  data() {
    return {
      activeNotifications: false,
      showMenu: false,
      searchModalVisible: false,
      searchQuery: ''
    };
  },
  methods: {
    capitalizeFirstLetter(string) {
      return string.charAt(0).toUpperCase() + string.slice(1);
    },
    toggleNotificationDropDown() {
      this.activeNotifications = !this.activeNotifications;
    },
    closeDropDown() {
      this.activeNotifications = false;
    }
  }
};
</script>
