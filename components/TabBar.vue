<template>
    <ion-page>
      <ion-tabs>
        <ion-router-outlet></ion-router-outlet>
        <ion-tab-bar slot="bottom">
          <ion-tab-button tab="home" href="/home">
            <ion-icon :icon="ioniconsHome" />
            <ion-label>Listen now</ion-label>
          </ion-tab-button>
  
          <ion-tab-button tab="radio" href="/radio">
            <ion-icon :icon="ioniconsRadio"></ion-icon>
            <ion-label>Radio</ion-label>
          </ion-tab-button>
  
          <ion-tab-button tab="library" href="/library">
            <ion-icon :icon="ioniconsImage"></ion-icon>
            <ion-label>Library</ion-label>
          </ion-tab-button>
  
          <ion-tab-button tab="search" href="/search">
            <ion-icon :icon="ioniconsCog" />
            <ion-label>Search</ion-label>
          </ion-tab-button>
        </ion-tab-bar>
      </ion-tabs>
    </ion-page>
  </template>