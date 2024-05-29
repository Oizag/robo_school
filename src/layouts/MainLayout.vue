<template>

  <q-layout view="hhh lpR fff">

    <q-header class="q-px-xl">
      <q-toolbar class="row justify-center">
        <q-toolbar-title class="col text-weight-bold">
          ROBO.SCHOOL
        </q-toolbar-title>
        <div class="col">
          <q-tabs>
            <q-route-tab
              to="/page1"
              label="О школе"
            />
            <q-route-tab
              to="/page2"
              label="Тренеры"
            />
            <q-route-tab
              to="/page3"
              label="Стоимость"
            />
          </q-tabs>
        </div>
        <div class="col">
          <q-toolbar-title class="text-right text-weight-bold">+7 800 000 11 22</q-toolbar-title>
        </div>
      </q-toolbar>

      <div class="column justify-center">
        <div
          class="app-banner__body flex q-mx-auto"
          style="max-width: 150vh"
        >
          <div class="col-8 flex items-center">
            <div class="test-content body__text q-gutter-xl">
              <p class="text__title text-h1 text-weight-bold">ROBO SCHOOL</p>
              <p class="text_description">Курсы повышения квалификации по робототехнике для педагогов начальной школы
              </p>
              <q-btn
                class="text__btn"
                label="Записаться на курс"
                padding="md"
                style="background-color: #D52027;"
              />
            </div>
          </div>
          <div
            class="col-4 relative-position"
            style="width: 50vh; height: 100vh"
          >
            <q-img
              :src="bannerImage"
              style="width: 100%; height: auto;"
              class="absolute-bottom-right"
            />
          </div>
        </div>
      </div>


    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>

    <q-footer class="q-px-xl">
      <q-toolbar>
        <q-toolbar-title>
          <p class="text-weight-bold">ROBO.SCHOOL</p>
          <p class="text-subtitle1 text-weight-thin">© ROBO.SCHOOL</p>
        </q-toolbar-title>
        <q-toolbar-title class="text-right text-weight-bold">+7 800 000 11 22</q-toolbar-title>
      </q-toolbar>
    </q-footer>

  </q-layout>

  <q-page-container>
    <router-view />
  </q-page-container>



</template>

<script setup lang="ts">
import bannerImage from "images/banner-image.png";
</script>
