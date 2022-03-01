<template>


   <!-- Sidebar -->
   <ul class="navbar-nav bg-gradient-primary sidebar sidebar-dark accordion" id="accordionSidebar">
             <SideBrandComponent></SideBrandComponent>
             <DashBoardComponent></DashBoardComponent>
             <AddonsComponent></AddonsComponent>
             <ChartComponent></ChartComponent>
             <TableComponent></TableComponent>




      

      


   </ul>
   <!-- End of Sidebar -->
</template>

<script>
// import BrandComponent from "./SideBarComponents/BrandComponent.vue";
import SideBrandComponent from "./SideBarComponents/SideBrandComponent.vue";
import DashBoardComponent from "./SideBarComponents/DashboardComponent.vue";
import AddonsComponent from "./SideBarComponents/AddonsComponent.vue";
import ChartComponent from "./SideBarComponents/ChartComponent.vue";
import TableComponent from "./SideBarComponents/TableComponent.vue";
export default {
  name: "SideBarComponent",
  components: { SideBrandComponent, DashBoardComponent, AddonsComponent, ChartComponent, TableComponent},
};
</script>