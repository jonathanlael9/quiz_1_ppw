<template>
  <ion-page>
    <ion-tabs>
      <ion-router-outlet></ion-router-outlet>
      <ion-tab-bar slot="bottom">
        <ion-tab-button tab="HomePage" href="/tabs/home">
          <ion-icon src="/assets/svg/Home.svg" style="height: 30px; width: 30px;"/>
          <p style="color: rgb(128, 129, 149); margin: -2px">home</p>
        </ion-tab-button>

        <ion-tab-button tab="PageSecond" href="/tabs/Page2">
          <ion-icon src="/assets/svg/Kolam 1.svg" style="height: 30px; width: 30px;"/>
          <p style="color: rgb(86, 75, 166); margin: -2px">Pond List</p>
        </ion-tab-button>
      </ion-tab-bar>
    </ion-tabs>
  </ion-page>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import { IonTabBar, IonTabButton, IonTabs, IonIcon, IonPage, IonRouterOutlet } from "@ionic/vue";
import { ellipse, triangle } from "ionicons/icons";

export default defineComponent({
  name: "TabsPage",
  components: { IonTabs, IonTabBar, IonTabButton, IonIcon, IonPage, IonRouterOutlet },
  setup() {
    return {
      ellipse,
      triangle,
    };
  },
});
</script>

<style scoped>
ion-tab-bar {
  background-color: #252836;
  border-radius: 15px 15px 0px 0px;
}
ion-tab-button {
  background-color: #252836;
}
</style>
