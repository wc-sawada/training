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

  <!-- ここからwhy -->
  <div class="why">
    <div class="why-sentence">
      <h3>そもそもなぜエンジニアなのか</h3>
      <p>お金が稼げそう</p>
      <p>かっこいい</p>
      <p>おもしろい</p>
      <p>知らない世界</p>
    </div>
  </div>

  <!-- ここからlife-plan -->
  <div class="life-plan">
    <h2>人生でやりたいこと</h2>
    <div class="life-plan-flex">
      <div class="life-plan-box">
        <div class="life-plan-number">
          <span class="number-color"><p>1</p></span>
        </div>
        <span class="box-header"><p>自由に働く</p></span>
        <p>エンジニアの場所にとらわれない働き方にあこがれた</p>
      </div>
      <div class="life-plan-box">
        <div class="life-plan-number">
          <span class="number-color"><p>2</p></span>
        </div>
        <span class="box-header"><p>自由に働く</p></span>
        <p>エンジニアの場所にとらわれない働き方にあこがれた</p>
      </div>
      <div class="life-plan-box last-child">
        <div class="life-plan-number">
          <span class="number-color"><p>3</p></span>
        </div>
        <span class="box-header"><p>自由に働く</p></span>
        <p>エンジニアの場所にとらわれない働き方にあこがれた</p>
      </div>
    </div>
  </div>
  <!-- ここに水平スクロール -->

  <!-- backend -->
  <div class="backend">
    <h2>バックエンドエンジニアとは</h2>
    <div class="backend-box">
      <span class="box-header"><p>Resion</p></span>
      <div class="box-content">
        
        <div class="box-flex">
          <div>
            <div class="box-sentence">
              <p>ユーザーからは見えない部分を補う</p>
            </div>
            <p>データベース</p>
            <p>インフラ</p>
            <p>システム戦略</p>
            <p>環境構築等</p>
          </div>
          <div>
            <img src="../assets/images/undraw_server_cluster_jwwq 1.png" alt="" class="box-image">
          </div>
        </div>
      </div>
    
    </div>

    <div class="backend-box">
      <span class="box-header"><p>Tech</p></span>
      <div class="box-content">
        
        <div class="box-flex">
          <div>
          <div class="box-sentence">
          <p>ユーザーからは見えない部分を補う</p>
        </div>
            <p>データベース</p>
            <p>インフラ</p>
            <p>システム戦略</p>
            <p>環境構築等</p>
          </div>
          <div>
            <img src="../assets/images/undraw_maintenance_re_59vn 2.png" alt="" class="box-image">
          </div>
        </div>
      </div>
    
    </div>

    <div class="backend-box">
      <span class="box-header"><p>License</p></span>
      <div class="box-content">
        <div class="box-flex">
          <div>
            <div class="box-sentence">
              <p>ユーザーからは見えない部分を補う</p>
            </div>
            <p>データベース</p>
            <p>インフラ</p>
            <p>システム戦略</p>
            <p>環境構築等</p>
          </div>
          <div>
            <img src="../assets/images/undraw_certification_re_ifll 1.png" alt="" class="box-image">
          </div>
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

<style lang="sass" scoped>

/* primary-color */
$primary-100: '#f2pff'
$primary-200: '#bae1fe'
$primary-300: '#7fcbf7'
$primary-400: '#44b4e5'
$primary-500: '#1095c2'
$primary-600: '#057e9b'
$primary-700: '#016574'
$primary-800: '#00474d'
$primary-900: '#002626'

$secondary-100: '#fff2f9'
$secondary-200: '#ffc5e6'
$secondary-300: '#fc96d7'
$secondary-400: '#f667ca'
$secondary-500: '#eb38be'
$secondary-600: '#ba179a'
$secondary-700: '#880977'
$secondary-800: '#570451'
$secondary-900: '#260226'

$natural-100: '#fafbfc'
$natural-200: '#e5e8eb'
$natural-300: '#d0d6da'
$natural-400: '#bcc5c9'
$natural-500: '#a9b488'
$natural-600: '#879193'
$natural-700: '#656d6f'
$natural-800: '#444a4b'
$natural-900: '#222626'

html, body 
  margin: 0
  font-family: sans-serif

h1 
  font-size:   32px

.hero 
  margin-top:14vh
  height: 100vh
  width: 100vw

.hero-image img
  display: block
  margin: 0 auto
  width: 72vh


.hero-second-sentence 
  position: relative
  margin-top: -100px
  padding-top:70px
  /*width: 100vw
  height: 21vh
  z-index: 0


.hero-second-sentence::before 
  display: block
  position: absolute
  top: 0
  left: 0
  background: inherit
  content: ''
  width: 100vw
  height: 21vh
  background: linear-gradient(180deg, rgba(127,203,247,0) 0%, rgba(127,203,247,0.2) 100%)
  filter:blur(15px)


.be-engineer 
  display: block
  width: 410px
  font-size: 32px
  color: $primary-900
  letter-spacing: 0.05em
  font-weight:bold
  margin: 80px auto 0 auto
  position: relative

.scroll 
  margin-top: 50px

.harf-circle 
  margin: 0 auto
  width: 214px
  height: 107px
  border: solid 1px 
  border-color: $natural-400
  border-radius: 107px 107px 0 0
  border-bottom: 0


.flex-circle 
  display: flex
  height: 69px
  width: 80px
  margin: 35px auto 0 100px

.harf-circle p 
  display: flex
  transform: rotate(90deg)
  color: $natural-400
  font-size: 16px
  margin: 0
  align-items: end


/* why */
.why 
  width: 100vw
  height: 265px
.why-sentence
  width: 242px
  margin: 0 auto

.why-sentence p
  text-align: center
  margin: 8px 0
  
h3
  font-size: 16px
  display: block
  text-align: center
  color: $primary-600
  margin-bottom: 30px


/* life-plan */
.life-plan
  width: 100vw
  margin-top: 100px
  padding: 50px 0 30px 0

h2 
  text-align: center
  margin-bottom: 54px

.life-plan-flex
  margin: 0 auto
  width: 72vw
  display: flex
  justify-content: space-between
  
.life-plan-box
  margin-right: 4vw
  width: 300px
  height: 181px
  border: 1px solid #000000
  border-radius: 10px
  padding: 0 50px 30px 50px

  .number-color p
    display: block
    margin: -24px auto 16px auto
    padding-top: 12px
    width: 48px
    height: 48px
    border-radius: 48px
    background-color: #00474d
    color: primary-800
    text-align: center
  .box-header p
    margin-bottom: 10px
    text-align: center
.last-child
  margin-right: 0

/* 水平スクロール */


/* backend */
.backend
  width: 100vw
  margin-top: 100px

.backend-box
  width: 72vw
  margin: 30px auto 40px auto
  .box-header p
    font-size: 64px
    font-weight: bold
    text-shadow: 0 4px 4px rgba(0,0,0,0.25)
  .box-content
    margin-top: -32px
    width: 63vw
    margin-left: 8.7vw
    padding: 34px 5px 10px 58px
    background-color: #f2f9ff
  .box-sentence
    margin-bottom: 20px
    p
      color: #00474d
  .box-flex
    display: flex
    justify-content: space-between
    .box-image
      height: 200px
      margin-top: -60px

</style>
