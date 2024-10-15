<template>
  <div class="footer">
    <div class="row nav container">
      <div class="col">
        <h1 class="text-uppercase text-h5 text-weight-bold">xxxxxxx.id</h1>
        <div class="socialmedia">
          <ul>
            <li>
              <router-link to="/"
                ><q-icon name="fab fa-facebook"
              /></router-link>
            </li>
            <li>
              <router-link to="/"
                ><q-icon name="fab fa-linkedin"
              /></router-link>
            </li>
            <li>
              <router-link to="/"><q-icon name="fab fa-youtube" /></router-link>
            </li>
            <li>
              <router-link to="/"
                ><q-icon name="fab fa-instagram"
              /></router-link>
            </li>
          </ul>
        </div>
      </div>
      <div class="col-2">
        <h3 class="text-uppercase text-h6 text-weight-medium">Navigasi</h3>
        <ul class="navfooter">
          <li><router-link to="/tentang">Tentang Kami</router-link></li>
          <li><router-link to="/profil">Profil Kami</router-link></li>
          <li><router-link to="/kontak">Hubungi Kami</router-link></li>
        </ul>
      </div>
      <div class="col-2">
        <h3 class="text-uppercase text-h6 text-weight-medium">xxxx</h3>
        <ul class="navfooter">
          <li><router-link to="/peta">xxxx</router-link></li>
          <li>
            <router-link to="/jurnal" jurnal>xxxxxx/ xxxxx</router-link>
          </li>
          <li><router-link to="/event">xxxxx</router-link></li>
        </ul>
      </div>
      <div class="col-2">
        <h3 class="text-uppercase text-h6 text-weight-medium">Lainnya</h3>
        <ul class="navfooter">
          <li><router-link to="/ketentuan">Ketentuan Layanan</router-link></li>
          <li><router-link to="/hakcipta">Hak Cipta</router-link></li>
          <li><router-link to="/disclaimer">Disclaimer</router-link></li>
        </ul>
      </div>
    </div>
    <div class="row text-center copyright">
      <div class="col">Hak Cipta Dilindungi Undang-Undang</div>
    </div>
  </div>
</template>
<style>
ul.navfooter {
  padding-left: 0px;
  font-size: 16px;
  line-height: 35px;
  font-weight: bold;
}
.navfooter li {
  list-style-type: none;
}
.navfooter li a {
  text-decoration: none;
  color: #666;
}
.socialmedia ul {
  list-style-type: none;
  padding-left: 0;
}
.socialmedia ul li {
  float: left;
  padding: 0 10px;
  font-size: 20px;
  color: #666;
}
.socialmedia ul li a {
  color: #444;
}
.copyright {
  background-color: #111;
  color: #eee;
  padding: 30px 0;
}
.footer > .row.nav {
  padding: 70px 0;
}
</style>
