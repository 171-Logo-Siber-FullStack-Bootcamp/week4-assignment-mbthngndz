<template>
   <!-- Page Wrapper -->
   <div id="wrapper">
      <AlertComponent></AlertComponent>
      <MessageComponent></MessageComponent>
      <UserInfoComponent></UserInfoComponent>
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