<template>
  <div>
    <hero-section
      backgroundImage="homepage-hero.jpg"
      title="Welcome to Instaflickr"
      subtitle="A photo app created by Fanpan Zeng"/>
    <div class="wrapper">
      <recent-photos />
      <place-photos />

    </div>
  </div>
</template>

<script>
import HeroSection from '@/components/HeroSection';
import RecentPhotos from '@/components/RecentPhotos';
import PlacePhotos from '@/components/PlacePhotos';

export default {
  name: 'home',
  components: { 
    HeroSection,
    RecentPhotos,
    PlacePhotos

  }
};
</script>