<!-- eslint-disable vue/valid-template-root -->
<template>
  <div class="main-container">
    <div class="container-one">
      <div class="profile">
        <img src="../assets/Me.png" class="pic" alt="photo">
        <h1>LAOUINI Slim</h1>
        <p>Junior Web Developer</p>
        <div class="social-links">
          <div class="link">
            <a href="https://github.com/laouinis/"
              target="_blank">
            <img src="../assets/github-mark-white.png" 
              class="pic git" 
              alt="GitHub link">
            </a>
          </div>          
          <div class="link">
            <a href="https://www.linkedin.com/feed/"
              target="_blank">
              <img src="../assets/LinkedIn-logo.png" 
                class="pic linkedin" 
                alt="LinkedIn link">
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    
  }
</script>

<style scoped>
  a {
    text-decoration: none;
  }
  h1, h2, p{
    color: #fff;
  }
  .pic {
    width: 150px;
    height: 200px;
  }
  .git{
    width: 10%;
    height: 10%;
  }
  .linkedin {
    width: 10%;
    height: 10%;
  }
</style>