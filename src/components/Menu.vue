<template>
    <div class="menu">
        <a href="#">Home</a>
        <a href="#">contact</a>
    </div>
</template>
  
<script>
export default {
    name: 'MenuVue',

}
</script>
  
<style scoped>
.menu{
    border-bottom: 1px solid #2c2c2c;
    background-color: #202020;
    display: flex;
    justify-content: space-between;
    flex-direction: row;
    position: fixed;
    top: 0px;
    width: 100%;
}
.menu > a {
    padding: 10px;
    font-weight: 600;
    text-decoration: none;
    text-decoration-line: none;
    color: rgb(209, 205, 205);
}
</style>
  