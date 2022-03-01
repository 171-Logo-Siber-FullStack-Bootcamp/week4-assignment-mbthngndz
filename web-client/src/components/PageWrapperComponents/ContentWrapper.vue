<template>
  <!-- Page Wrapper -->
  <div id="content wrapper">
    <!-- Main Content -->
    <MainContent></MainContent>
    <!-- End of Main Content -->

    <!-- Footer -->
    <FooterContent></FooterContent>
    <!-- End of Footer -->
  </div>
  <!-- End of Page Wrapper -->
</template>
<script>
import MainContent from "./ContentWrappers/MainContent";
import FooterContent from "./ContentWrappers/FooterContent";
export default {
  name: "PageWrapper",
  components: {
    MainContent,
    FooterContent,
  },
};
</script>
