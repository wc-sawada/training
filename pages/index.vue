<template>
  <main>

  <!-- ここからhero -->
  <div class="hero">
    <div class="main-hero">
      <div class="hero-image">
        <img src="../assets/images/freely.png" alt="">
      </div>
      <div class="hero-second-sentence">
        <p class="be-engineer">Be a backendengineer</p>
      </div>
    </div>
    <!-- スクロールオブジェクト -->

    <div class="scroll">
      <div class="harf-circle">
        <div class="flex-circle">
          <img src="../assets/images/Line 10.png" alt="">
          <p>Scroll to</p>
        </div>
      </div>
    </div>
  </div>
  </main>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>

<style scoped>
html, body {
  margin: 0;
  font-family: sans-serif;
}

h1 {
  font-size:   32px;
}

.hero {
  margin-top:14vh;
  height: 100vh;
  width: 100vw
}

.hero-image img{
  display: block;
  margin: 0 auto;
  width: 72vh;
}

.hero-second-sentence {
  position: relative;
  margin-top: -100px;
  padding-top:70px;
  /*width: 100vw;
  height: 21vh;
  background: linear-gradient(180deg, rgba(127,203,247,0) 0%, rgba(127,203,247,0.2) 100%);*/
  z-index: 0;
}

.hero-second-sentence::before {
  display: block;
  position: absolute;
  top: 0;
  left: 0;
  background: inherit;
  content: '';
  width: 100vw;
  height: 21vh;
  background: linear-gradient(180deg, rgba(127,203,247,0) 0%, rgba(127,203,247,0.2) 100%);
  filter:blur(15px);
}

.be-engineer {
  display: block;
  width: 410px;
  font-size: 32px;
  color: #002626;
  letter-spacing: 0.05em;
  font-weight:bold;
  margin: 80px auto 0 auto;
  position: relative;
}

.harf-circle {
  margin: 0 auto;
  width: 214px;
  height: 107px;
  border: solid 1px #d0d6da;
  border-radius: 107px 107px 0 0;
  border-bottom: 0;
  margin-top: 60px;
}

.flex-circle {
  display: flex;
  height: 69px;
  width: 80px;
  margin: 35px auto 0 100px;
}

.harf-circle p {
  display: flex;
  transform: rotate(90deg);
  color: #bcc5c9;
  font-size: 16px;
  margin: 0;
  align-items: end;
}

</style>
