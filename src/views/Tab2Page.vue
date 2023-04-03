<template>
  <ion-page>
    <toolbarHeader />
    <ion-content :fullscreen="true">
      
      <uitgevoerd name="Tab 2 page" />
      
    </ion-content>
  </ion-page>
</template>

<script setup lang="ts">
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';
import uitgevoerd from '@/components/Uitgevoerd.vue';
import toolbarHeader from '@/components/toolbarHeader.vue';
</script>
