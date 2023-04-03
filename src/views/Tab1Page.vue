<template>
  <ion-page>
    <toolbarHeader />
    <ion-content :fullscreen="true">
      

      <toegewezen />

    </ion-content>
  </ion-page>
</template>

<script setup lang="ts">
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';
import toegewezen from '@/components/Toegewezen.vue';
import toolbarHeader from '@/components/toolbarHeader.vue';
</script>
