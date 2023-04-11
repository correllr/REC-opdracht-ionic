<template>
  <ion-page>
    <toolbarHeader />
    <ion-content :fullscreen="true">
      

      <instellingen name="Tab 4 page" />
      
    </ion-content>
  </ion-page>
</template>

<script setup lang="ts">
import { IonPage, IonContent } from '@ionic/vue';
import instellingen from '@/components/instellingen.vue';
import toolbarHeader from '@/components/toolbarHeader.vue';
</script>
