<template>
  <q-header class="dlj_mainnav text-black">
    <div class="row container">
      <q-toolbar class="col">
        <q-toolbar-title>
          <q-btn flat to="/" class="text-capitalize text-center">
            <h1 class="text-h6">
              <!-- <q-img src="/public/logo.jpg" width="50px"/> -->
              <!-- <q-icon name="fas fa-podcast" />  -->
              Fatherless the Movie
            </h1>
          </q-btn>

          <div class="desktop-only float-right q-pt-md">
            <q-tabs
              indicator-color="transparent"
              dense
              inline-label
              class="text-black"
            >
              <q-route-tab
                exact
                class="text-capitalize"
                label="Beranda"
                to="/"
              />
              <q-route-tab
                exact
                class="text-capitalize"
                label="Sinopsis"
                to="/"
              />
              <q-route-tab
                exact
                class="text-capitalize"
                label="Cast"
                to="/"
              />
              <q-route-tab
                exact
                class="text-capitalize"
                label="Pernyataan Sutradara"
                to="/"
              />
              <q-route-tab
                exact
                class="text-capitalize"
                label="Profil"
                to="/"
              />
              <!-- <q-route-tab exact class="text-capitalize" label="About" to="/" /> -->
            </q-tabs>
          </div>
        </q-toolbar-title>
      </q-toolbar>
    </div>
  </q-header>
</template>
