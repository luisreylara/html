<template>
   <div class="contenedor">
        <h2>Login</h2>
        <form id="forma" name="forma" method="POST">
            <div class="elemento">
                <label for="usuario">Usuario</label>
                <input type="text" id="usuario" name="usuario" required="true"/>
            </div>
            <div class="elemento">
                <label for="password">Password</label>
                <input type="password" id="password" name="passwrod" required="true"/>
            </div>
            <div class="elemento">
                <input type="submit" value="Enviar"/>
            </div>
        </form>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
html{
    height: 100%;
}
body{
    margin: 0;
    padding: 0;
    background: linear-gradient(#7209b7, #3f37c0);
}
.contenedor{
    margin: 50px auto;
    width: 400px;
    padding: 30px;
    background: rgba(0,0,0, .5);
    border-radius: 10px;
}
.contenedor h2{
    margin: 0 0 30px;
    padding: 0;
    font-size: 30px;
    color: #4cc9f0;
    text-align: center;
}
</style>
