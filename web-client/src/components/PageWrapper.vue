<template>
   <!-- Page Wrapper -->
   <div id="wrapper">
      <!-- Sidebar -->
      <SideBar></SideBar>
      <!-- End of Sidebar -->

      <!-- Content Wrapper -->
      <ContentWrapper></ContentWrapper>
      <!-- End of Content Wrapper -->
   </div>
   <!-- End of Page Wrapper -->
</template>
<script>
import SideBar from './PageWrapperComponents/SideBar'
import ContentWrapper from './PageWrapperComponents/ContentWrapper'
export default {
   name: 'PageWrapper',
   components: {
      SideBar,
      ContentWrapper
   }
}
</script>