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
          <a href="#">
            <button>delete</button>
          </a>
        </tr>
        <tr>
          <td>Bertram Gilfoyle</td>
          <td>gilfoyle@gmail.com</td>
          <a href="#">
            <button>delete</button>
          </a>
        </tr>
        <tr>
          <td>Dinesh Chugtai</td>
          <td>dinesh@gmail.com</td>
          <a href="#">
            <button>delete</button>
          </a>
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

