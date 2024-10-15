<template>
  <div class="homeprofil">
    <div class="row container">
      <div class="col">
        <q-img
          src="https://placehold.co/300x400/000000/FFF?text=Dummy"
          :ratio="16 / 9"
        />
      </div>
      <div class="col q-pl-xl">
        <h1 class="text-h4 text-weight-bold">Profil Kami</h1>
        <p class="text-subtitle1">
          Project ini kami gagas sebagai upaya kontribusi positif pengembangan
          dan memperkaya identitas kebudayaan nasional
        </p>
        <q-btn size="md" color="dark" class="text-capitalize" to="/profil"
          >Baca Selengkapnya</q-btn
        >
      </div>
    </div>
  </div>
</template>

<style>
.homeprofil {
  padding: 30px 0 100px;
  background-color: #dedede;
}
</style>
