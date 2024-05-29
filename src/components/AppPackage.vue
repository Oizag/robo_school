<template>
  <div class="package-container column q-py-xl">
    <div class="row">
      <div class="col-8 q-mb-xl">
        <p class="text-h3 text-weight-bold">Выберите нужный пакет</p>
      </div>
    </div>
    <div class="row">
      <div class="col text-center">
        <q-card
          flat
          bordered
          class="column justify-around"
          style="width: 360px; height: 460px"
        >
          <q-card-section class="text-weight-bold text-h5">– PRO –</q-card-section>
          <q-card-section>
            <p class="price text-weight-bold text-h4 q-mb-xl">20.000 ₽</p>
            <q-card-section>
              <p class="description">УМК по робототехнике и программированию</p>
            </q-card-section>
          </q-card-section>
          <q-card-section>
            <q-btn
              label="Оставить заявку"
              padding="lg"
              text-color="white"
              style="background-color: #D52027;"
            />
          </q-card-section>
        </q-card>
      </div>
      <div class="col text-center">
        <q-card
          flat
          bordered
          class="column justify-around"
          style="width: 360px; height: 460px"
        >
          <q-card-section class="text-weight-bold text-h5">– ROBO –</q-card-section>
          <q-card-section>
            <p class="price text-weight-bold text-h4 q-mb-xl">15.000 ₽</p>
            <q-card-section>
              <p class="description">УМК по робототехнике</p>
            </q-card-section>
          </q-card-section>
          <q-card-section>
            <q-btn
              label="Оставить заявку"
              padding="lg"
              text-color="white"
              style="background-color: #D52027;"
            />
          </q-card-section>
        </q-card>
      </div>
      <div class="col text-center">
        <q-card
          flat
          bordered
          class="column justify-around"
          style="width: 360px; height: 460px"
        >
          <q-card-section class="text-weight-bold text-h5">– PROG –</q-card-section>
          <q-card-section>
            <p class="price text-weight-bold text-h4 q-mb-xl">10.000 ₽</p>
            <q-card-section>
              <p class="description">УМК по программированию</p>
            </q-card-section>
          </q-card-section>
          <q-card-section>
            <q-btn
              label="Оставить заявку"
              padding="lg"
              style="background-color: #D52027;"
              text-color="white"
            />
          </q-card-section>
        </q-card>
      </div>
    </div>
  </div>
</template>

<style scoped>
.q-card:hover {
  background-color: #141024;
  transition: background-color 0.6s;
  color: #fff;
  transform: scale(1.05) !important;
  transition: transform 0.6s;
}
</style>