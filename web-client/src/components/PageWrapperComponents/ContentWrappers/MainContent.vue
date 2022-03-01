<template>
  <!-- Content Wrapper -->
  <div id="content-wrapper" class="d-flex flex-column">
    <!-- Main Content -->
    <div id="content">
      <TopBar />
      <!-- Begin Page Content -->
      <BeginContent />
    </div>
  </div>
  <!-- End of Content Wrapper -->
</template>
<script>
import TopBar from './MainContent/TopBar'
import BeginContent from './MainContent/BeginContent'
export default {
   name: 'PageWrapper',
   components: {
      TopBar,
      BeginContent
   }
}
</script>