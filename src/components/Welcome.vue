<template>
  <section id="welcome">
    <navigation />
    <div class="welcome-wrapper">
      <h1>
        Uwieczniamy najpiękniejsze chwile!
      </h1>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit.<br>
        Cras ultricies, arcu ut.
      </p>
      <a class="btn" href="">
        Więcej
      </a>
    </div>
    <div class="background-video">
      <div class="video-overlay"></div>
      <video src="@/assets/background-video.mp4" autoplay loop></video>
    </div>
  </section>
</template>

<script>
import Navigation from '@/components/Navigation.vue'

export default {
  components: {
    Navigation
  }
}
</script>

<style lang="scss">
#welcome {
  background: $color1;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-between;
  padding: 5vh 0 15vh 0;
  position: relative;
  .background-video{
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    z-index: 0;
    .video-overlay{
      background: black;
      opacity: .8;
      position: absolute;
      width: 100%;
      height: 100%;
    }
    video{
      height: 100%;
      width: 100%;
      object-fit: cover;
    }
  }
  .welcome-wrapper{
    text-align: center;
    z-index: 2;
    h1{
      font-size: 3rem;
      color: $color1;
    }
    p{
      color: white;
    }
    a{
      color: $color-text;
      text-transform: uppercase;
      font-size: .8rem;
      background: $color1;
      color: white;
      border-color: $color1;
      margin-top: 25px;
      display: inline-block;
    }
  }

}
</style>
