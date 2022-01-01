<template>
  <footer class="footer">
    <div class="footer-top text-center ">
      <h1 class="display-4 text-white title-join">JOIN THE CLUB</h1>
      <div class="container w-50 mb-5">
        <p class="text-left text-white font-weight-normal h5">
          Texte à définir. Lorem ipsum derabat Ipsum gitem aredabitur est debanatam. Estatum alea jacta est.
        </p>
      </div>

      <div class="container w-50">
        <div class="row">
          <div class="col">
            <button type="button" class="btn btn-danger w-100 btn-group1 border-0">
              <div class="button-icon">
                <img
                    src="../assets_dani/icon/group.png"
                    alt="group-icon"
                    class="icon-strong mr-2"
                />
                <p class="h2">JOIN US ON DISCORD</p>
              </div>
            </button>
          </div>
        </div>
        <div class="row mt-3">
          <div class="col">
            <button type="button" class="btn btn-danger w-100 custom-button btn-instagram border-0">
              <div  class="button-icon">
                <img
                    src="../assets_dani/icon/instagram.png"
                    alt="group-icon"
                    class="icon mr-2"
                >
                <p class="h3">INSTAGRAM</p>
              </div>
            </button>
          </div>
          <div class="col">
            <button type="button" class="btn btn-danger w-100 btn-twitter border-0">
              <div class="button-icon">
                <img
                    src="../assets_dani/icon/twitter.png"
                    alt="group-icon"
                    class="icon mr-2"
                />
                <p class="h3">TWITTER</p>
              </div>
            </button>
          </div>
        </div>
      </div>
    </div>
    <div class="footer-bottom">
      <div class="container text-center">
        <div class="row">
          <div class="col">
            <img src="../assets_dani/icon/MontreOr.png" alt="logo" class="logo">
          </div>
          <div class="col">
            <img src="../assets_dani/icon/logo.png" alt="logo" class="logo">
          </div>
          <div class="col">
            <img src="../assets_dani/icon/Redlip.png" alt="logo" class="logo">
          </div>
        </div>

        <p class="title-terms">Terms & Conditions</p>

        <p class="text-white" style="margin-bottom: 0px;">MGDC - All Rights Reserved 2022</p>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "footer_desk"
}
</script>

<style scoped>
.footer-top{
  background-image: url("../assets_dani/img/footerTop.png");
  width: 100%;
  height: 100vh;
  padding-top: 140px;
  background-position: center;
  background-repeat: no-repeat;
  background-size: auto;
  position: relative;
}

.footer-bottom{
  width: 100%;
  background-image: url("../assets_dani/img/footerBottom.png");
  height: auto;
  background-position: center;
  background-repeat: no-repeat;
  background-size: auto;
  position: relative;
  padding: 30px;
}

.icon{
  width: 30px;
  height: auto;
}

.icon-strong{
  width: 45px;
  height: auto;
}

.title-join{
  text-shadow: 0px -10px 2px #E53261;
  margin-bottom: 30px;
  font-weight: 400;
  font-size: 78px;
}

.button-icon{
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-evenly;
}

.btn-group1{
  background-color: #E53261;
  border-radius: 10px;
  padding: 10px;
}

.btn-instagram{
  background-color: #A6357D;
  padding: 10px;
  border-radius: 10px;
}

.btn-twitter{
  background-color: #DF5F3D;
  padding: 10px;
  border-radius: 10px;
}

.logo{
  width: 250px;
  height: 300px;
  margin-top: -100px;
}

.title-terms{
  color: #fff !important;
  margin-bottom: 90px;
  margin-top: -30px;
}
</style>
