<template>
  <div class="teacher-container column q-py-xl ">
    <div class="row">
      <div class="col-8">
        <p class="text-h3 text-weight-bold">Профессиональные тренеры</p>
      </div>
    </div>
    <div class="row">
      <div class="col">
        <q-card
          flat
          style="width: 360px;"
        >
          <q-img
            :src="irinaPhoto"
            class="q-mb-md"
          />
          <p class="teacher__name text-weight-bold q-mb-md">Ирина Лайм</p>
          <p class="teacher__position q-mb-md">Преподаватель по робототехнике</p>
          <q-btn
            flat
            label="Подробнее"
            style="color: #D52027; padding: 0;"
          />
        </q-card>
      </div>
      <div class="col">
        <q-card
          flat
          style="width: 360px;"
        >
          <q-img
            :src="marinaPhoto"
            class="q-mb-md"
          />
          <p class="teacher__name text-weight-bold q-mb-md">Ирина Лайм</p>
          <p class="teacher__position q-mb-md">Преподаватель по робототехнике</p>
          <q-btn
            flat
            label="Подробнее"
            style="color: #D52027; padding: 0;"
          />
        </q-card>
      </div>
      <div class="col">
        <q-card
          flat
          style="width: 360px;"
          class="relative-position"
        >
          <q-img
            :src="maksikPhoto"
            class="q-mb-md"
          />

          <p class="teacher__name text-weight-bold q-mb-md">Ирина Лайм</p>
          <p class="teacher__position q-mb-md">Преподаватель по робототехнике</p>
          <q-btn
            flat
            label="Подробнее"
            style="color: #D52027; padding: 0;"
          />
        </q-card>
      </div>
    </div>
    <div class="teachers-nav absolute-bottom-right">
      <q-avatar>
        <q-btn>
          <img :src="arrowBtn">
        </q-btn>
      </q-avatar>
      <q-avatar>
        <q-btn>
          <img
            :src="arrowBtn"
            style="rotate: 180deg;"
          >
        </q-btn>
      </q-avatar>
    </div>
  </div>
</template>

<script setup lang="ts">
import irinaPhoto from 'src/assets/images/irina.jpg'
import marinaPhoto from 'src/assets/images/marina.jpg'
import maksikPhoto from 'src/assets/images/maksik.jpg'
import arrowBtn from 'src/assets/images/Arrow.svg'
</script>
