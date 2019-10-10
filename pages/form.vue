<template>
    <div>
        <center>
            <div class="nav">
                <h1>Jollof Form</h1>
                <nuxt-link to="/">Home</nuxt-link>
                <nuxt-link to="/about">About</nuxt-link>
                <nuxt-link to="/form">Form</nuxt-link>
            </div>
            <br>
            <br>
            <main>
                <form
                    name="jollof-form" 
                    method="post" 
                    data-netlify="true" 
                    data-netlify-honeypot="bot-field"
                    >
                    Full name:<br>
                    <input type="text" name="name" value="Full name">
                    <br>
                    Your Favorite Jollof name:<br>
                    <select name="jollof" id="">
                        <option value="naija">Nigerian Jollof</option>
                        <option value="ghana">Ghanian Jollof</option>
                    </select>
                    <br><br>
                    <input type="submit" value="Submit">
                </form>
            </main>
        </center>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>

</style>