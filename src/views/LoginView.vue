<template>
    <div class="form-container">
        <h2>Login</h2>
        <form action="/login" method="post">
            <div class="form-group">
                <label for="name">Name:</label>
                <input type="text" id="name" name="username" placeholder="Enter your name" required autocomplete="off">
            </div>
            <div class="form-group">
                <label for="password">Password:</label>
                <input type="password" id="password" name="password" placeholder="password" required>
            </div>
            <button type="submit" class="submit-btn">Login</button>
            <p>Don't have an account ? <a href="/signup">Signup</a></p>
        </form>
    </div>
</template>
<script>
export default {
    
}
</script>
<style>
    
</style>