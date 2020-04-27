<template>
  <div class="body">
    <h1 class="name col-md-12">River Merrill</h1>
    <ul class="information row">
      <li class="col-md-4">760 SW Vista Ave</li>
      <li class="col-md-4">Portland, Oregon 97205</li>
      <li class="col-md-4">rivermerrill.me@gmail.com</li>
    </ul>
    <h2 class="col-md-12">Summary</h2>
    <p class="col-md-12">
      Accomplished musician and developer; young, exuberant, ready to take on
      the world.
    </p>
    <div class="left-section col-md-7">
      <h2 class="header">Work Experience</h2>
      <h3 class="company">Allata</h3>
      <p class="job-title">Application Development, March 2018 - March 2020</p>
      <p class="respon">
        Responsibilities: Application development and design in Angular 8 and
        .NET Core
      </p>
      <h3 class="company">Gigmi, Inc.</h3>
      <p class="job-title">
        Lead Front-End Web Developer, December 2015 - July 2016
      </p>
      <p class="respon">
        Responsibilities: Front-end web development for local startup using
        Ionic framework
      </p>
      <h3 class="company">BoiseCodeWorks</h3>
      <p class="job-title">
        Web Development Course Mentor, January 2016 - March 2016
      </p>
      <p class="respon">
        Responsibilities: Mentoring students in learning full stack web
        development, group project facilitator
      </p>
      <h3 class="company">Container and Packaging Supply</h3>
      <p class="job-title">Intern in IT Department, Sep 2015 - Nov 2015</p>
      <p class="respon">
        Aquired new skills: Working with relational databases, using SCRUM
        practices, working with a team
      </p>
      <h3 class="company">Gemtek Pest Control</h3>
      <p class="job-title">Assistant Marketing Director, Jun 2014 - Aug 2014</p>
      <p class="respon">
        Responsibilities: Photoshop, Illustrator, and InDesign for flyers and
        online marketing
      </p>
      <h3 class="company">7th Dimension</h3>
      <p class="job-title">Intern, Jan 2013 - Aug 2014</p>
      <p class="respon">
        Responsibilities: Inventory and organization of computer hardware, setup
        and installation of software
      </p>
      <hr />
      <h3 class="company">Freelance Web Development</h3>
      <p class="job-title">Roots Records, November 2017 - February 2018</p>
      <p class="respon">Web development and audio engineering</p>
      <p class="job-title">
        "Meals, Deals, and Steals" app, March 2016 - December 2017
      </p>
      <p class="respon">
        Full stack development for Android and iOS using Ionic and Firebase
      </p>
      <p class="job-title">Merrill's Organics, 2015</p>
      <p class="respon">
        Website analytics, Paypal integration, stylization using CSS
      </p>
    </div>
    <div class="right-section col-md-offset-1 col-md-4">
      <h2 class="header">Education</h2>
      <h3 class="education-location">BoiseCodeWorks</h3>
      <p class="education-completed">Alumni, Nov 2015</p>
      <h3 class="education-location">Homeschool</h3>
      <p class="education-completed">High School Diploma, May 2015</p>
      <h3 class="education-location">Nielsen School of Music</h3>
      <p class="education-completed">
        Creative Music Ensemble, Sept 2014 - May 2016
      </p>
      <h3 class="education-location">Arts West</h3>
      <p class="education-completed">
        Music program with emphasis on Jazz piano and theory
      </p>
      <h2 class="header">Programming Skills</h2>
      <p class="skills">
        <span class="bold">Languages:</span> HTML, CSS, Javascript, C#
      </p>
      <p class="skills">
        <span class="bold">Frameworks:</span> AngularJS, Angular 2+, Vue, .NET
        Core, Jquery, NodeJS, Ionic, Bootstrap, Angular Material
      </p>
      <p class="skills">
        <span class="bold">Tools:</span> Jetbrains Rider/Webstorm, Git, Command
        Line, Heroku, NPM/Yarn
      </p>
      <h2 class="header">Additional Skills</h2>
      <p class="skills">Audio Engineering/Music Production</p>
      <p class="skills">Graphic Design (Photoshop, Illustrator, etc.)</p>
      <h2 class="header">Links</h2>
      <a
        class="link"
        target="_blank"
        href="https://github.com/rivermerrill"
      >github.com/rivermerrill</a>
      <a
        class="link"
        target="_blank"
        href="https://www.linkedin.com/in/river-m-a0901295"
      >linkedin.com/in/river-m-a0901295/</a>
      <a
        class="link"
        target="_blank"
        href="http://rivermerrill.com"
      >rivermerrill.com</a>
    </div>
  </div>
</template>

<script>
export default {
  head: {
    link: [
      { rel: 'stylesheet', href: 'https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css' }
    ]
  }
}
</script>  


<style scoped>
.body {
  text-align: center;
  margin-bottom: 3%;
}
hr {
  border-color: lightgrey;
}
a {
  color: grey;
  text-decoration: none;
  display: block;
}
a:hover,
a:visited:hover,
a:focus {
  color: black;
  text-decoration: none;
}
a:visited:hover {
  color: black;
  text-decoration: none;
}
.container {
  color: gray;
  /* background-color: antiquewhite; */
}
.information {
  padding-right: 2%;
  border-bottom: 1px solid grey;
  background-color: white;
}
.information li {
  list-style-type: none;
  text-align: center;
}
.left-section {
  text-align: center;
}

.right-section {
  text-align: left;
}
.header {
  /*background-color: lightblue;*/
  border-top: 2px solid lightblue;
  border-bottom: 2px solid lightblue;
  font-weight: bold;
  text-align: center;
}
.company {
  font-weight: bold;
}
.job-title {
  font-style: italic;
  font-weight: bold;
}
.education-location {
  font-weight: bold;
}
.education-completed {
  font-style: italic;
}
.bold {
  font-weight: bold;
}
</style>