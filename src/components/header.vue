<template>
    <nav>
        <ul>
            <li><router-link to="/" exact>Blogs</router-link></li>
            <li><router-link to="/add" exact>Add</router-link></li>
        </ul>
    </nav>
</template>

<script>
export default {}
</script>

<style scoped>
ul{
    list-style-type: none;
    text-align: center;
    margin: 0;
    float: right;
    padding-right: 20px;
}
li{
    display: inline-block;
    margin: 0 10px;
}
a{
    color: #fff;
    text-decoration: none;
    padding: 12px;
    border-radius: 5px;
}
nav{
    background: #002200;
    padding: 30px 0;
    margin-bottom: 40px;
}
.router-link-active{
    background: rgba(255,255,255,0.8);
    color: #444;
}
</style>
