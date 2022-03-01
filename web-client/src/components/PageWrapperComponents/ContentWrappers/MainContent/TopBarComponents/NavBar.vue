<template>
   <!-- Page Wrapper -->
   <div id="wrapper">
      <!-- Sidebar -->
      <AlertComponent></AlertComponent>
      <!-- End of Sidebar -->

      <!-- Content Wrapper -->
      <MessageComponent></MessageComponent>
      <!-- End of Content Wrapper -->

        <!-- Content Wrapper -->
      <UserInfoComponent></UserInfoComponent>
      <!-- End of Content Wrapper -->
   </div>
   <!-- End of Page Wrapper -->
</template>
<script>
import AlertComponent from './NavBarComponents/AlertComponent'
import MessageComponent from './NavBarComponents/MessageComponent'
import UserInfoComponent from './NavBarComponents/UserInfoComponent'
export default {
   name: 'PageWrapper',
   components: {
      AlertComponent,
      MessageComponent,
      UserInfoComponent
   }
}
</script>