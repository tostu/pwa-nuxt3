<script setup lang="ts">
useHead({
  title: 'Nuxt Ionic',
})
</script>

<template>
  <ion-page>
    <ion-content>
      <ion-tabs>
        <ion-router-outlet />
        <ion-tab-bar slot="bottom">
          <ion-tab-button tab="tab1" href="/tabs/home">
            <ion-icon :icon="ioniconsHome" />
            <ion-label>Home</ion-label>
          </ion-tab-button>

          <ion-tab-button tab="tab2" href="/tabs/counter">
            <ion-icon :icon="ioniconsGameController" />
            <ion-label>Counter</ion-label>
          </ion-tab-button>

          <ion-tab-button tab="tab3" href="/tabs/settings">
            <ion-icon :icon="ioniconsCog" />
            <ion-label>Settings</ion-label>
          </ion-tab-button>

        </ion-tab-bar>
      </ion-tabs>
    </ion-content>
  </ion-page>
</template>