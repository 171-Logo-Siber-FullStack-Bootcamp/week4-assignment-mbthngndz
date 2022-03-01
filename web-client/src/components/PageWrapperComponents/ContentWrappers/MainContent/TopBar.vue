<template>
  <!-- Topbar -->
  <nav
    class="navbar navbar-expand navbar-light bg-white topbar mb-4 static-top shadow"
  >
    <!-- Sidebar Toggle (Topbar) -->
    <button
      id="sidebarToggleTop"
      class="btn btn-link d-md-none rounded-circle mr-3"
    >
      <i class="fa fa-bars"></i>
    </button>
    <SearchBar />
    <NavBar />
  </nav>
</template>
<script>
import SearchBar from './TopBarComponents/SearchBar'
import NavBar from './TopBarComponents/NavBar'
export default {
   name: 'TopBar',
   components: {
      SearchBar,
      NavBar
   }
}
</script>