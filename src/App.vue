<script setup>
import Bio from './components/Bio.vue'
import NewsList from './components/NewsList.vue'
import EducationList from './components/EducationList.vue'
import CPublicationList from './components/CPublicationList.vue'
import PublicationList from './components/PublicationList.vue'
import AwardList from './components/AwardList.vue'
import SoftwareList from './components/SoftwareList.vue'
import Footer from './components/Footer.vue'

</script>

<template>
  <div> 
  <header>
    <Bio />
    <hr>
  </header>

  <main>
    <NewsList />
    <hr>
    <EducationList />
    <CPublicationList />
      <PublicationList />
      <AwardList />
      <SoftwareList />
  </main>

  <Footer />
  </div>  
</template>

<style>

</style>
