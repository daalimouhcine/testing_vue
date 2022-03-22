<template>
  <div id="employee">
    <table>
      <thead>
        <tr>
          <th>Employee name</th>
          <th>Employee email</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Richard Hendricks</td>
          <td>richard@gmail.com</td>
          <button>delete</button>
        </tr>
        <tr>
          <td>Bertram Gilfoyle</td>
          <td>gilfoyle@gmail.com</td>
          <button>delete</button>
        </tr>
        <tr>
          <td>Dinesh Chugtai</td>
          <td>dinesh@gmail.com</td>
          <button>delete</button>
        </tr>
      </tbody>
    </table>
  </div>
</template>

<script>
  export default {
    name: 'employee-table',
  }
</script>
