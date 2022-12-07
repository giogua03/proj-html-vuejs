<template>
  <div>
    <div class="blu-cont">
      <img src="/images/artist-shape-color-paint-top-left-300x170.png" alt="">
      <div class="h1"><h1>Newletter to get in touch</h1></div>
      <input type="text" class="bg-color" value="Your e-mail">
      <img src="/images/artist-shape-color-paint-bottom-right-300x153.png" alt="">
    </div>
    <div class="frooter">
      <div class="container">
        <div class="row">
          <div class="col">
            <ul>
              <h2>Address</h2>
              <li>382 NE 191 ST # 87394 Miami, FL 33179-3899</li>
              <li>+1(305) 547-9909(9am - 5pm, Monday - Friday)</li>
              <li>support@maxcoach.com</li>
              <li>
                <img src="/images/favicon-32x32.png" alt="">
                <img src="/images/favicon-32x32.png" alt="">
                <img src="/images/favicon-32x32.png" alt="">
                <img src="/images/favicon-32x32.png" alt="">
              </li>
            </ul>
          </div>
          <div class="col">
            <ul>
              <h2>Explore</h2>
              <li>Start here</li>
              <li>Success story</li>
              <li>Blog</li>
              <li>Cuorses</li>
              <li>Contact us</li>
            </ul>
          </div>
          <div class="col">
            <ul>
              <h2>Information</h2>
              <li>Membership</li>
              <li>Purchase guide</li>
              <li>Privacy policy</li>
              <li>Terms of services</li>
            </ul>
          </div>
          <div class="col">
            <div class="container">
              <div class="vgfd">
                <h2>Instagram</h2>
                <p><strong>@maxcoach</strong></p>
              </div>
              <div class="nhg">
                <div class="col"><img src="/images/120084500_197897808368764_8114555493043279565_n.jpg" alt=""></div>
                <div class="col"><img src="/images/120012142_177596140500760_8623485824101406058_n.jpg" alt=""></div>
                <div class="col"><img src="/images/120099363_364334431619755_7198812647386067017_n.jpg" alt=""></div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="fine">
      <p>@ 2020 Maxcoach. All Rights Rserved</p>
      <div class="vg"><button>upt</button></div>
    </div>
  </div>
</template>

<script>
export default {
name:'PageFooter',
}
</script>

<style lang="scss" scoped>
.blu-cont{
  background-color: rgb(49, 49, 209);
  display: flex;
  justify-content: space-between;
}
.h1{
  color: white;
  text-align: end;
  max-width: 400px;
  margin: auto 0;
}
h1{
  font-size: 40px;
}
.bg-color{
  background-color:rgb(49, 49, 209);
  height: 30px;
  width: 600px;
  margin: auto 0 ;
  color: white;
}
li{
list-style: none;
margin:  1rem 0;
}
li img{
  margin-right: 1rem ;
  margin-top:1rem;
}
.vgfd{
  display: flex;
}
 .vgfd p{
  color: red;
  margin-top: .5rem;
  font-size:20px;
}
.nhg{
  display: flex;
}
.nhg .col img{
  height: 150px;
  margin-right: 1rem;
}
.frooter{
  margin:  5rem 0;
}
.fine p{
  color: lightgrey;
  
}
.fine .vg button{
  border-radius: 100% ;
  color: white;
  background-color: orange;
  text-align: center;
  border-color: orange;
}
.fine{
  display: flex;
  justify-content: center;

}

</style>