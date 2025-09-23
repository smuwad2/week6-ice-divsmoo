<script>
    export default { 

       // add code here

    }
</script>

<template>
    <h1>Please select your login option</h1>
    <!-- Add/modify code in the following to have a dropdown list 
        which lets the user to select either to login with username or email -->
    
    <select v-model="login-Type">
        <option selected>Username login</option>
        <option>Email login</option>
    </select>
    
    <div v-if="loginTyp === 'username'">
        <label>Username</label>
        <input placeholder="Enter your username">
    </div>

    <div>
        <label>Email</label>
        <input placeholder="Enter your email address">
    </div>
</template>

