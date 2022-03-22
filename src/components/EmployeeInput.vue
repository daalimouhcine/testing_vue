<template>
    <form id="Employee" action="" method="post">
        <div>
            <label for="fullName">Full Name</label>
            <input type="text" name="fullName">
        </div>
        <div>
            <label for="email">Full Name</label>
            <input type="email" name="email">
        </div>
        <input type="submit" value="Add">
    </form>
</template>

<script>
    export default {
        name: 'Employee-input',
    }
</script>

