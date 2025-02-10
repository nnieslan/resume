<script setup lang="ts"></script>

<template>
  <div class="hero-banner">
    <div class="hero-banner-image">
      <img src="@/assets/images/nick-headshot.jpg" alt="Nick Nieslanik" />
    </div>
    <div class="hero-banner-text">
      <h1>Nick Nieslanik</h1>
      <h2>Product & Technology Executive</h2>

      <p>
        <br />
        <i class="fas fa-map"></i><span>&nbsp;</span>Denver, CO
        <br />
        <i class="fa-solid fa-mobile"></i><span>&nbsp;</span
        ><a href="tel:1-720-939-9808">720-939-9808</a>
        <br />
        <i class="fas fa-inbox"></i><span>&nbsp;</span>
        <a href="mailto:nicknieslanik@gmail.com">nicknieslanik@gmail.com</a>
      </p>
    </div>
  </div>
</template>
<style scoped>
.hero-banner {
  display: flex;
  align-items: center;
}
.hero-banner-image {
  position: relative;
}

.hero-banner-image::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-image: linear-gradient(
    90deg,
    #111111 0%,
    transparent 30%,
    transparent 70%,
    #111111 100%
  );
  z-index: 1;
}

.hero-banner img {
  height: 100%;
  display: block;
  position: relative;
  z-index: 0;
}

.hero-banner-text {
  padding-left: 2rem;
}

.hero-banner-text h1 {
  font-weight: bold;
  font-size: 3rem;
}
.hero-banner-text h2 {
  font-weight: normal;
  font-size: 2rem;
}
.hero-banner-text p {
  font-size: 1rem;
  padding: 0.5rem 0;
}
a {
  font-weight: bold;
}
@media screen and (max-width: 768px) {
  .hero-banner-image::before {
    background-image: linear-gradient(
      90deg,
      #111111 0%,
      transparent 30%,
      transparent 70%,
      #111111 100%
    );
  }
  .hero-banner img {
    width: 100%;
    height: auto;
  }

  .hero-banner-text {
    padding-left: 20px;
  }

  .hero-banner-text h1 {
    font-size: 1.25rem;
  }

  .hero-banner-text h2 {
    font-size: 1rem;
  }

  .hero-banner-text p {
    font-size: 0.5rem;
  }
}
</style>
