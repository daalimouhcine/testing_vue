<template>
  <div id="app" class="small-container">
    <h2>Add Employee</h2>
    <Employee-input />
    <h2>Employees</h2>
    <employee-table />
  </div>
</template>

<script>
  import EmployeeTable from '@/components/EmployeeTable.vue'
  import EmployeeInput from '@/components/EmployeeInput.vue'

  export default {
    name: 'app',
    components: {
      EmployeeTable,
      EmployeeInput
    },
  }
</script>

<style>
  button {
    background: #009435;
    border: 1px solid #009435;
  }

  .small-container {
    max-width: 680px;
  }
</style>