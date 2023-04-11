<template>
  <ion-page>
    <toolbarHeader />
    <ion-content :fullscreen="true">
      <knowledgebase name="Tab 3 page" />
    </ion-content>
  </ion-page>
</template>

<script setup lang="ts">
import { IonPage, IonContent } from '@ionic/vue';
import knowledgebase from '@/components/knowledgebase.vue';
import toolbarHeader from '@/components/toolbarHeader.vue';
</script>
