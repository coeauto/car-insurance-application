<template>
    <v-container class="request-form-main">
        <h1>Request Form</h1>
        <v-btn dark color="blue" @click="sendEmail()">Email</v-btn>
    </v-container>
</template>

<script>
// const Email  = require('https://smtpjs.com/v3/smtp.js');

export default {
    name: 'RequestForm',

    methods: {
        sendEmail() {
            alert(1);
            // Email.send({
            // Host: 'smtp.gmail.com',
            // Username : 'coeasiaautomation@gmail.com',
            // Password : "Inchcap3",
            // To : 'lester.fajardo@gmail.com',
            // From : 'coeasiaautomation@gmail.com',
            // Subject : '<email subject>',
            // Body : '<h1>Hello!</h1>',
            // }).then(
            //     message => alert("mail sent successfully")
            // );
        }
    }
}
</script>

<style>

</style>