<template>
  <!-- Content Wrapper -->
  <div id="main content" class="d-flex flex-column">
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
   name: 'MainContent',
   components: {
      TopBar,
      BeginContent
   }
}
</script>