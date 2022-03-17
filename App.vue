<template>
  <div class="Info">
    <div class="left">
      <div class="left-info">
        <div class="picture">
          <img src="./assets/Profilepicture.jpg" width="100%" height="100%">
        </div>
          <h3>Maglalang Francis</h3>
      </div>

      <div class="contactInfo"></div>
        <h4 class="information"> Personal information</h4>
        <ul class="contact">
          <li>Name : Maglalang Francis Jose L.</li>
          <li>Age : 20</li>
          <li>Birthday : September 07, 2001</li>
          <li>Address : 611 Sitio Marimar Sapang Biabas Mabalacat City</li>
        </ul>

      <div class="contactInfo"></div>
        <h4 class="information"> Hobbies</h4>
        <ul class="contact">
          <li>Sleeping</li>
          <li>Traveling</li>
          <li>Eating</li>
          <li>Playing Computer Games</li>
          <li>Working Out</li>
        </ul>

        <div class="contactInfo"></div>
          <h4 class="information"> Contact information</h4>
          <ul class="contact">
            <li>Email : maglalangfrancis192@gmail.com</li>
            <li>School Email : flmaglalang@student.hau.edu.ph</li>
            <li>Contact No. : 0921412223</li>
          </ul>

        </div>

        <div class="right">
          <div class="about">
            <h2 class="title">Something About Me</h2>
              <about-me></about-me>
          </div>
          <br>
          <div class="Favorites">
                    <h2 class="title">Favorites </h2>
                    <fave></fave>
                </div>
          <br>
          <div class="Skills">
              <h2 class="title">Skills</h2>
                <skills></skills>
          </div>
          <br>
          <div class="Language">
            <h2 class="title">Language </h2>
            <language></language>
          </div>

            </div>
        </div>
</template>

<script>
//------------Imports--------------//
import AboutMe from './AboutMe.vue'
import Fave from './Motto.vue'
import Skills from './skills.vue'
import Language from './Language.vue'
//---------------------------------//
export default {
  //--------Components---------//
  components: { 
    AboutMe,
    Fave,
    Skills,
    Language
    
  },

  name: 'app',
  data () {
    return {
      msg: ''
    }
  }
}
</script>

<style>
*
{
    margin: 0;
    padding: 0;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
}

body {
    background-color: royalblue;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
}

.Info {
    position: relative;
    width: 100%;
    max-width: 1000px;
    min-height: 1000px;
    margin: 50px;
    background-color: skyblue;
    display: grid;
    grid-template-columns: 1fr 2fr;
    box-shadow: 0 35px 55px rgb(255, 255, 255);
}
/***************************************************/
.Info .left {
    position: relative;
    background: brown;
    padding: 40px;
}

.left-info{
    position: relative;
    display: flex;
    flex-direction: column;
    align-items: center;
    padding-bottom: 20px;
    border-bottom: 2px solid black;
}

.picture {
    position: relative;
    width: 200px;
    height: 200px;
    border-radius: 45%;
    overflow: hidden;
}

.left-info h3 {
    color: white;
    font-size: 1.5em;
    margin-top: 20px;
    text-transform: uppercase;
    text-align: center;
    font-weight: 600;
    line-height: 1.4em;
}

.contactInfo {
    padding-top: 40px;
}

.contact {
    color: white;
    font-weight: 300;
    font-size: 18px;
    display: inline-block;
    
}

.information {
    color: white;
    text-transform: uppercase;
    font-weight: 600;
    letter-spacing: 1px;
    margin-bottom: 20px;

}
/***************************************************/
.Info .right {
    position: relative;
    background: turquoise;
    padding: 40px;
}

.about {
    margin-bottom: 50px;
}

.title {
    color: whitesmoke;
    text-transform: uppercase;
    letter-spacing: 1px;
    margin-bottom: 10px;
}

p {
    color: rgb(255, 253, 248);
}

ul {
    font-size: 20px;
    color: whitesmoke;
    font-weight: 300;
    letter-spacing: 1px;
    margin-bottom: 20px;
}
</style>
