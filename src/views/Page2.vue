<template>
  <ion-page>
    <ion-content :fullscreen="true">
      <div class="navbar" style="margin-inline: 30px">
        <h1>Kolam</h1>
        <div>
          <img src="/assets/icon/Sorting.svg" alt="" />
          <img src="/assets/icon/Vector.svg" alt="" />
        </div>
      </div>
      <div>
        <ion-card class="box">
          <ion-card-header>
            <div class="head">
              <ion-card-title style="color: black; margin-top: 12px"
                >Alpha</ion-card-title
              >
              <button class="tombol">Aktif</button>
            </div>
            <hr />
          </ion-card-header>

          <ion-card-content>
            <div class="tanggal">
              <img src="assets/icon/tanggal.svg" alt="" />
              <p>01-09-2022</p>
            </div>
            <div class="hari" style="display: flex; gap: 5px">
              <img src="assets/icon/hari.svg" alt="" />
              <p>90 Hari</p>
            </div>
            <div class="hari" style="display: flex; gap: 5px">
              <img src="assets/icon/ikan.svg" alt="" />
              <p>200 Ekor</p>
            </div>
          </ion-card-content>
        </ion-card>
        <ion-card class="box">
          <ion-card-header>
            <div
              class="head"
              style="display: flex; justify-content: space-between"
            >
              <ion-card-title style="color: black; margin-top: 12px"
                >Beta</ion-card-title
              >
              <button class="tombol">Aktif</button>
            </div>
            <hr />
          </ion-card-header>

          <ion-card-content>
            <div class="tanggal">
              <img src="assets/icon/tanggal.svg" alt="" />
              <p>01-09-2022</p>
            </div>
            <div class="hari" style="display: flex; gap: 5px">
              <img src="assets/icon/hari.svg" alt="" />
              <p>90 Hari</p>
            </div>
            <div class="hari" style="display: flex; gap: 5px">
              <img src="assets/icon/ikan.svg" alt="" />
              <p>200 Ekor</p>
            </div>
          </ion-card-content>
        </ion-card>
        <ion-card class="box">
          <ion-card-header>
            <div
              class="head"
              style="display: flex; justify-content: space-between"
            >
              <ion-card-title style="color: black; margin-top: 12px"
                >Charlie</ion-card-title
              >
              <button class="tombol">Aktif</button>
            </div>
            <hr />
          </ion-card-header>

          <ion-card-content>
            <div class="tanggal">
              <img src="assets/icon/tanggal.svg" alt="" />
              <p>01-09-2022</p>
            </div>
            <div class="hari" style="display: flex; gap: 5px">
              <img src="assets/icon/hari.svg" alt="" />
              <p>90 Hari</p>
            </div>
            <div class="hari" style="display: flex; gap: 5px">
              <img src="assets/icon/ikan.svg" alt="" />
              <p>200 Ekor</p>
            </div>
          </ion-card-content>
        </ion-card>
        <ion-card class="box">
          <ion-card-header>
            <div
              class="head"
              style="display: flex; justify-content: space-between"
            >
              <ion-card-title style="color: black; margin-top: 12px"
                >Delta</ion-card-title
              >
              <button class="non-active">Tidak Aktif</button>
            </div>
            <hr />
          </ion-card-header>

          <ion-card-content>
            <div class="tanggal">
              <img src="assets/icon/tanggal.svg" alt="" />
              <p>01-09-2022</p>
            </div>
            <div class="hari" style="display: flex; gap: 5px">
              <img src="assets/icon/hari.svg" alt="" />
              <p>90 Hari</p>
            </div>
            <div class="hari" style="display: flex; gap: 5px">
              <img src="assets/icon/ikan.svg" alt="" />
              <p>200 Ekor</p>
            </div>
          </ion-card-content>
        </ion-card>
        <ion-card class="box">
          <ion-card-header>
            <div
              class="head"
              style="display: flex; justify-content: space-between"
            >
              <ion-card-title style="color: black; margin-top: 12px"
                >Epsilon</ion-card-title
              >
              <button class="tombol">Aktif</button>
            </div>
            <hr />
          </ion-card-header>

          <ion-card-content>
            <div class="tanggal">
              <img src="assets/icon/tanggal.svg" alt="" />
              <p>01-09-2022</p>
            </div>
            <div class="hari" style="display: flex; gap: 5px">
              <img src="assets/icon/hari.svg" alt="" />
              <p>90 Hari</p>
            </div>
            <div class="hari" style="display: flex; gap: 5px">
              <img src="assets/icon/ikan.svg" alt="" />
              <p>200 Ekor</p>
            </div>
          </ion-card-content>
        </ion-card>
      </div>
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { IonContent, IonPage } from "@ionic/vue";
import { defineComponent } from "vue";

export default defineComponent({
  name: "PageSecond",
  components: {
    IonContent,
    IonPage,
  },
});
</script>

<style scoped>
* {
  font-family: Poppins;
  font-weight: bold;
}

@font-face {
  font-family: "Poppins";
  src: url(../../public/assets/font/Poppins-Regular.ttf);
}

hr {
  border-top: 3px solid black;
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

.head {
  display: flex;
  justify-content: space-between;
  margin-top: -10px;
}

.tanggal {
  display: flex;
  gap: 5px;
}

.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin: 20px 12px;
  font-weight: bold;
}
.navbar img {
  width: 30px;
}


.tombol {
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
