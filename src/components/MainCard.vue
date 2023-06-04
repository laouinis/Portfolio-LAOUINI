<!-- eslint-disable vue/valid-template-root -->
<template>
  <div class="main-container">
    <div class="container-one">
      <div class="profile">
        <img src="../assets/Me.png" class="pic" alt="photo" />
        <h1>LAOUINI Slim</h1>
        <p>Junior Fullstack Developer</p>
        <p>North of France</p>
        <div class="social-links">
          <div class="link">
            <a href="https://github.com/laouinis/" target="_blank">
              <img
                src="../assets/github-mark-white.png"
                class="logo-pics"
                alt="GitHub link"
              />
            </a>
          </div>
          <div class="link">
            <a href="https://www.linkedin.com/feed/" target="_blank">
              <img
                src="../assets/LinkedIn-logo.png"
                class="logo-pics"
                alt="LinkedIn link"
              />
            </a>
          </div>
        </div>
      </div>
    </div>
    <div class="container-two">
      <div class="about-me">
        <h2>About Me</h2>
        <p>
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Accusantium
          libero pariatur ab repellat, recusandae repellendus sapiente
          exercitationem blanditiis laudantium praesentium minus soluta ipsum
          rem magni voluptatibus, illo cupiditate ipsam totam tenetur
          reprehenderit! Consequuntur ex reprehenderit pariatur libero amet
          rerum non iure deserunt. Sequi cumque dicta fugiat corrupti nisi
          tempore iste accusantium voluptate, nulla adipisci molestiae vero
          neque quia, incidunt dolore expedita ullam officia optio autem? Vel
          porro debitis beatae! Molestiae a earum ex ducimus, quas alias optio
          cupiditate itaque autem officia, tempore temporibus dicta nihil hic
          ipsum velit modi rem voluptatem, magnam ullam minima cumque. Natus
          omnis quis recusandae enim!
        </p>
      </div>
      <div class="technology-section">
        <h2>Technologies Studied</h2>
        <img src="../assets/html5.png" class="logo-pics" alt="html5" />
        <img src="../assets/CSS3.png" class="logo-pics" alt="css3" />
        <img
          src="../assets/JavaScript-logo.png"
          class="logo-pics"
          alt="javascript"
        />
        <img src="../assets/NJS.png" class="logo-pics" alt="node js" />
        <img src="../assets/Angular.png" class="logo-pics" alt="angular" />
        <img src="../assets/Mango-db.png" class="logo-pics" alt="mangoDB" />
      </div>
      <div class="btn-container">
        <div class="btn-projects">
          <a href="">My Projects</a>
        </div>
        <div>
          <a href="">My Resume</a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.main-container {
  display: flex;
  flex-direction: row;
}
.container-one {
  background-color: red; /*for sizing test */
  width: 30%;
  padding: 2.5%;
}
.container-two {
  background-color: greenyellow; /*for sizing test */
  width: 70%;
}
/* a {
    text-decoration: none;
  } */

h1,
h2,
p {
  color: #fff;
}
.pic {
  height: 5rem;
  width: 5rem;
  border-radius: 50%;
}
.logo-pics {
  height: 40px;
}
</style>
