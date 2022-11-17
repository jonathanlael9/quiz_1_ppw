<template>
  <ion-page>
    <ion-header :translucent="true">
      <ion-toolbar>
        <ion-title>Kolam</ion-title>
      </ion-toolbar>
    </ion-header>

    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Kolam</ion-title>
        </ion-toolbar>
      </ion-header>
      <div>
        <ion-card class="box">
          <ion-card-header>
            <div class="cardhead" style="display: flex; justify-content: space-between">
              <ion-card-title style="color: black; margin-top: 12px">Alpha</ion-card-title>
              <button class="actv">Aktif</button>
            </div>
            <hr />
          </ion-card-header>

          <ion-card-content>
            <div style="display: flex; gap: 10px; align-items: center; margin-top: 10px;">
              <img src="/assets/svg/Calendar Plus.svg" alt="1">
              <p style="font-size: 20px;">01-09-2022</p>
            </div>
            <div style="display: flex; gap: 10px; align-items: center; margin-top: 10px;">
              <img src="/assets/svg/Timesheet.svg" alt="2">
              <p style="font-size: 20px;">90 Hari</p>
            </div>
            <div style="display: flex; gap: 10px; align-items: center; margin-top: 10px;">
              <img src="/assets/svg/Whole Fish.svg" alt="3">
              <p style="font-size: 20px;">200 Ekor</p>
            </div>
          </ion-card-content>
        </ion-card>
        <ion-card class="box">
          <ion-card-header>
            <div class="cardhead" style="display: flex; justify-content: space-between">
              <ion-card-title style="color: black; margin-top: 12px">Beta</ion-card-title>
              <button class="actv">Aktif</button>
            </div>
            <hr />
          </ion-card-header>

          <ion-card-content>
            <div style="display: flex; gap: 10px; align-items: center; margin-top: 10px;">
              <img src="/assets/svg/Calendar Plus.svg" alt="1">
              <p style="font-size: 20px;">01-09-2022</p>
            </div>
            <div style="display: flex; gap: 10px; align-items: center; margin-top: 10px;">
              <img src="/assets/svg/Timesheet.svg" alt="2">
              <p style="font-size: 20px;">90 Hari</p>
            </div>
            <div style="display: flex; gap: 10px; align-items: center; margin-top: 10px;">
              <img src="/assets/svg/Whole Fish.svg" alt="3">
              <p style="font-size: 20px;">200 Ekor</p>
            </div>
          </ion-card-content>
        </ion-card>
        <ion-card class="box">
          <ion-card-header>
            <div class="cardhead" style="display: flex; justify-content: space-between">
              <ion-card-title style="color: black; margin-top: 12px">Charlie</ion-card-title>
              <button class="actv" style="margin-left: 5px; margin-right: 5px">Aktif</button>
            </div>
            <hr />
          </ion-card-header>

          <ion-card-content>
            <div style="display: flex; gap: 10px; align-items: center; margin-top: 10px;">
              <img src="/assets/svg/Calendar Plus.svg" alt="1">
              <p style="font-size: 20px;">01-09-2022</p>
            </div>
            <div style="display: flex; gap: 10px; align-items: center; margin-top: 10px;">
              <img src="/assets/svg/Timesheet.svg" alt="2">
              <p style="font-size: 20px;">90 Hari</p>
            </div>
            <div style="display: flex; gap: 10px; align-items: center; margin-top: 10px;">
              <img src="/assets/svg/Whole Fish.svg" alt="3">
              <p style="font-size: 20px;">200 Ekor</p>
            </div>
          </ion-card-content>
        </ion-card>
        <ion-card class="box">
          <ion-card-header>
            <div class="cardhead" style="display: flex; justify-content: space-between">
              <ion-card-title style="color: black; margin-top: 12px">Delta</ion-card-title>
              <button class="non-active">Tidak Aktif</button>
            </div>
            <hr />
          </ion-card-header>

          <ion-card-content>
            <div style="display: flex; gap: 10px; align-items: center; margin-top: 10px;">
              <img src="/assets/svg/Calendar Plus.svg" alt="1">
              <p style="font-size: 20px;">01-09-2022</p>
            </div>
            <div style="display: flex; gap: 10px; align-items: center; margin-top: 10px;">
              <img src="/assets/svg/Timesheet.svg" alt="2">
              <p style="font-size: 20px;">90 Hari</p>
            </div>
            <div style="display: flex; gap: 10px; align-items: center; margin-top: 10px;">
              <img src="/assets/svg/Whole Fish.svg" alt="3">
              <p style="font-size: 20px;">200 Ekor</p>
            </div>
          </ion-card-content>
        </ion-card>
        <ion-card class="box">
          <ion-card-header>
            <div class="cardhead" style="display: flex; justify-content: space-between">
              <ion-card-title style="color: black; margin-top: 12px">Epsilon</ion-card-title>
              <button class="actv" style="margin-left: 5px; margin-right: 5px">Aktif</button>
            </div>
            <hr />
          </ion-card-header>

          <ion-card-content>
            <div style="display: flex; gap: 10px; align-items: center; margin-top: 10px;">
              <img src="/assets/svg/Calendar Plus.svg" alt="1">
              <p style="font-size: 20px;">01-09-2022</p>
            </div>
            <div style="display: flex; gap: 10px; align-items: center; margin-top: 10px;">
              <img src="/assets/svg/Timesheet.svg" alt="2">
              <p style="font-size: 20px;">90 Hari</p>
            </div>
            <div style="display: flex; gap: 10px; align-items: center; margin-top: 10px;">
              <img src="/assets/svg/Whole Fish.svg" alt="3">
              <p style="font-size: 20px;">200 Ekor</p>
            </div>
          </ion-card-content>
        </ion-card>
      </div>
    </ion-content>
    <ion-fab vertical="bottom" horizontal="end" slot="fixed" style="margin-right: 15px;">
      <ion-fab-button href="/registrationpage"><span style="font-size: 60px; font-weight:bolder">+</span></ion-fab-button>
    </ion-fab>
  </ion-page>
</template>

<script lang="ts">
import { IonContent, IonHeader, IonPage, IonTitle, IonToolbar } from "@ionic/vue";
import { defineComponent } from "vue";

export default defineComponent({
  name: "PageSecond",
  components: {
    IonContent,
    IonHeader,
    IonPage,
    IonTitle,
    IonToolbar,
  },
});
</script>

<style scoped>
hr {
  border-top: 2px solid black;
  margin-bottom: -10px;
}

.non-active {
  margin-top: 10px;
  margin-left: 180px;
  justify-content: center;
  align-items: center;
  padding: 5px 10px;
  gap: 10px;

  width: 100px;
  height: 34px;

  background: #c20000;
  border-radius: 12px;
}

#container {
  text-align: center;

  position: absolute;
  left: 0;
  right: 0;
  top: 50%;
  transform: translateY(-50%);
}

#container strong {
  font-size: 20px;
  line-height: 26px;
}

#container p {
  font-size: 16px;
  line-height: 22px;

  color: #8c8c8c;

  margin: 0;
}

#container a {
  text-decoration: none;
}

.box {
  padding: 10px 0px;
  font-family: poppin;
  background-color: white;
  color: black;
  margin: 30px;
  border-radius: 16px;
  font-size: 18px;
  font-weight: 600;
  line-height: 27px;
}

.cardhead {
  margin-top: -20px;
  columns: 2;
}

.actv {
  margin-top: 10px;
  margin-left: 180px;
  justify-content: center;
  align-items: center;
  padding: 5px 10px;
  gap: 10px;

  width: 58px;
  height: 34px;

  background: #1b7c1a;
  border-radius: 12px;
}
</style>
