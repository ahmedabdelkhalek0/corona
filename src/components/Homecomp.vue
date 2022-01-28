<template>
<section class="test position-relative">
<div class="caption position-absolute top-50 start-50 translate-middle">
    <h6>DESIGN/DEVELOPMENT/PHOTOGRAPHY</h6>
    <h1>CREATIVITY HAVE NEW LEVEL</h1>
    <button type="button" class="btn-career">PREVIEW</button>
    <button type="button" class="btn-career">GET THEME</button>
    </div>
</section>


</template>

<style>
.test{
    background-image: url(../assets/imgs/header.jpg);
    height:80vh;
    color:var(--third-color);
    background-size: cover;
    background-color: var(--main-color);
    background-blend-mode: multiply;
}
.test .caption .btn-career{
    color:var(--third-color);
    background-color: var(--main-color);
    border:1px solid white;
    padding:10px 50px;
    margin:10px;
    border-radius:5px;
    font-size: 12px;

}
.test{
    margin-top: -70px;
}

.test .caption .btn-career:hover{
    background-color: var(--second-color);
}

</style>

<script>
export default{
    name:"Slider"

}

</script>