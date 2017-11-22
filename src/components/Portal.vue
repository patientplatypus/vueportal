<template>
  <div class="portal">
    <div class='portalcontainer'>
      <br><br><br>
      <div class="title">
        <p>
          Hello, and welcome to the world of tomorrow!  🚀
        </p>
      </div>
      <br/>
      <div class='notes'>
        <p>
          Here is a list of some of my past and ongoing projects that I am most proud of -
        </p>
      </div>
      <br/>
      <div class="projbox">
        <div class='projtitle'>
          <p>
            Newsly *Highlight*
          </p>
        </div>
        <div class='projdescription'>
          <p>
            This is a websocket based reddit clone that responds to interactions in real time! This dockerizes and phoenix backend application and sends it to Elastic Beanstalk. It also lets users add photos, stored in S3, and saves user info in AWS RDS. It's super effective!
          </p>
        </div>
        <div class='projlinky'>
          <a href="http://newsly.q8z8p.net">Linky</a>
        </div>
      </div>
      <br/>
      <div class="projbox">
        <div class='projtitle'>
          <p>
            Platypus_Tracker
          </p>
        </div>
        <div class='projdescription'>
          <p>
            This is a job tracking application that uses an interactive calendar to track applied jobs, and emails. It also lets the user scrape job boards! Written in React and Node it has the backend pushed to Heroku.
          </p>
        </div>
        <div class='projlinky'>
          <a href="http://tracker.q8z8p.net">Linky</a>
        </div>
      </div>
      <br/>
      <div class="projbox">
        <div class='projtitle'>
          Color_Portfolio
        </div>
        <div class='projdescription'>
          <p>
            This portfolio is all based on colors! I have my portfolio information (of course), but the user can change the color of the website by requesting a color palette from colormind.io. Also, I have a drum machine that changes the site colors to a beat! This project lives on Digital Ocean.
          </p>
        </div>
        <div class='projlinky'>
          <a href="http://www.q8z8p.net">Linky</a>
        </div>
      </div>
      <br/>
      <div class="projbox">
        <div class='projtitle'>
          Drawing_Share
        </div>
        <div class='projdescription'>
          <p>
            This was my final project for my coding bootcamp. It is a drawing application that lets multiple users draw on the same canvas at once! My first trial with sockets and phoenix it *mostly* works, but maybe has a few kinks. Deployed to AWS through a containerization service called nanobox.
          </p>
        </div>
        <div class='projlinky'>
          <a href="http://pennydrop.nanoapp.io">Linky</a>
        </div>
      </div>
      <br/>
      <div class='notes'>
        <p>
          ...and this one is sort of a failure! But I had fun making it anyway...
        </p>
      </div>
      <br/>
      <div class="projbox">
        <div class='projtitle'>
          RetroFuturistic_Portfolio
        </div>
        <div class='projdescription'>
          <p>
            This is a react site that uses CSS (and css tools like Glamorous from Paypal) to make a retro-futuristic website inspired from the 80s and video games. Unfortunately, I put so many animations and moving parts in the site that it crashes on all but the fastest computers. Best viewed (if possible on google chrome). Pushed to BlueHost over FTP.
          </p>
        </div>
        <div class='projlinky'>
          <a href="https://www.q8z8p.com">Linky</a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Portal',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.portalcontainer{
  text-align: center;
}
.projbox{
  width: 80%;
  margin-left: 5%;
  padding: 5%;
  border-radius: 20%;
  border-width: 5px;
  border-style: solid;
  border-color: rgba(200,200,200,0.6);
  background-color: rgba(220, 220, 220, 0.3);
}
.title{
  font-size: 4vh;
  color: tomato;
}
.projtitle{
  font-size: 3vh;
  font-weight: bold;
  color:skyblue;
}
.projdescription{
  font-size: 2vh;
  font-weight: bold;
  color:tomato;
}
.notes{
  color:red;
  font-size: 2vh;
}
h1, h2 {
  font-weight: normal;
  line-height: 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
