<template>
  <div class="home">
    <header>
      <div class="container">
        <!--<br /><br />
        <p class="text-right">
          <i class="fas fa-bars"></i>
        </p>-->
        <div class="row">
          <div class="col-sm-12 col-md-6">
            <img src="../assets/fsdlogo.jpg" class="logo"/>
            <h1>
              Fullstack <br />Developers<br />Lagos
            </h1>
          </div>
          <div class="col-sm-12 col-md-6 img-cover">
            <img src="../assets/developer.svg" class="full-width-img"/>
          </div>
        </div>
      </div>
    </header>
    <div class="container section">
      <div class="row">
        <div class="col-sm-12 col-md-8">
          <p>
            The Full Stack Developers Lagos Meetup is a group that brings together practitioners 
            that use a combination of front-end and back-end development frameworks and technologies 
            to build unique projects that solve day-to-day problems in todays society.
          </p>
          <p>
            The group is majorly for seasoned and aspiring developers coming together with a common 
            interest of leveling up their software developement skills in the sense of sharing experience 
            using hybrid frameworks that cut across different platforms, as well as getting up-to-date with 
            latest developer technologies. 
          </p>
          <!--<router-link to='/' class="more">Find out more</router-link>-->
        </div>
      </div>
    </div>
    <div class="blue-bg">
      <div class="row">
        <div class="col-sm-12 col-md-12 text-center">
          <h2>Our next meetup</h2>
          <br />
          <p>Join us at the <span class="underline">Fullstack developers meetup</span> on <span class="underline">March 2nd, 2019</span> at <span class="underline">Our venue</span> by <span class="underline">11am</span> for our next meetup</p>
          <a href="https://www.meetup.com/gdg-Ajah/events/258556771/?rv=co1&_xtd=gatlbWFpbF9jbGlja9oAJGQyZThhMjQ4LWFiMTItNDEwMS04YzVlLTIxMzVmMjVmM2JmYw" target="_blank" class="btn btn-rsvp">Rsvp here</a>
        </div>
      </div>
    </div>
    <div class="container section">
      <div class="row">
        <div class="col-sm-12 col-md-12 text-center">
          <h2>Meet our Facilitators</h2>
          <br />
        </div>
      </div>
      <div class="row">
        <div class="col-sm-4 col-12">
          <img src="../assets/jogun.jpeg" class="facilitator" />
          <div class="facilitator-card">
            <h5>Jogun Ogedengbe</h5>
            <p class="social-icons">
              <a href="https://www.linkedin.com/in/jogun-ogedengbe-50494115/" target="_blank"><i class="fas fa-globe"></i></a>
            </p>
          </div>
        </div>
        <div class="col-sm-4 col-12">
          <img src="../assets/adora.jpg" class="facilitator" />
          <div class="facilitator-card">
            <h5>Adora Nwodo</h5>
            <p class="social-icons">
              <a href="https://twitter.com/theadoranwodo" target="_blank"><i class="fab fa-twitter"></i></a>
              <a href="https://adoranwodo.com" target="_blank"><i class="fas fa-globe"></i></a>
            </p>
          </div>
        </div>
        <div class="col-sm-4 col-12">
          <img src="../assets/sam.jpg" class="facilitator" />
          <div class="facilitator-card">
            <h5>Sam Okediji</h5>
            <p class="social-icons">
              <a href="https://twitter.com/SamuelOkediji_" target="_blank"><i class="fab fa-twitter"></i></a>
            </p>
          </div>
        </div>
      </div>
    </div>
    <div class="footer">
      <p class="text-center">Copyright Fullstack developers Lagos 2019 &copy;</p>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>

<style scoped>
.home{
  max-width: 100vw;
  overflow-x: hidden;
}
.footer{
  background: black;
  padding: 15px;
}
.footer p{ 
  color: white;
  margin-bottom: 0px;
  font-size: 13px;
}
.social-icons a{
  color: black;
  margin: 0px 5px;
}
.social-icons a:hover{
  color: rgb(112, 112, 112);
}
.fas.fa-bars{
  cursor: pointer;
  color: #baf6fa;
}
.facilitator{
  width: 100%;
  border-top-right-radius: 30px;
  border-top-left-radius: 30px;
}
.facilitator-card{
  width: 100%;
  height: 110px;
  background: rgb(204, 248, 248) !important;
  border-bottom-right-radius: 30px;
  border-bottom-left-radius: 30px;
  text-align: center;
  padding: 20px;
  margin-bottom: 30px;

}
header{
  background: rgb(17, 17, 17);
  width: 100vw;
  min-height: 90vh;
}
@media only screen and (max-width: 450px) {
  header h1{
    font-size: 30px;
  }
  .img-cover{
    display: none;
  }
}
header h1{
  padding-bottom: 0px;
  margin-top: 0px;
  color: #baf6fa;
  font-family: 'Major Mono Display', monospace !important;
}
img.logo{
  width: 80px;
  height: auto;
  padding-bottom: 30px;
  padding-top: 25vh;
}
.img-cover img{
  padding-bottom: 80px;
  padding-top: 25vh;
}
.full-width-img{
  width: 100%;
  height: auto;
}
.container.section, .blue-bg{
  padding-top: 100px;
  padding-bottom: 100px;
}
.blue-bg{
  background: rgb(0, 78, 97);
}
a.more{
  color: rgb(6, 141, 175);
  text-decoration: none;
}
h4.blue-text{
  color: rgb(6, 141, 175);
}
.blue-bg h2, .blue-bg p{
  color: white;
}
.blue-bg p{
  margin-bottom: 5px;
}
.blue-bg p span.underline{
  text-decoration: underline;
  color: rgb(190, 232, 240);
}
.btn-rsvp{
  background: black;
  color: rgb(187, 250, 250);
  margin-top: 20px;
}
.btn-rsvp:hover{
  background: rgb(44, 44, 44);
}
</style>

