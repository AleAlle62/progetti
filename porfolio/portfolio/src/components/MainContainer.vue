<template>
    <div class="main">
        <h4>Hi I'm Alessio. Nice To meet you</h4>
        <p>I'm a junior full stack web developer, I've always been passionate about technology and in September 2022 I attended the boolean course. I'm curious, I like to keep up to date and learn new technologies</p>
    </div>
</template>


<script>
export default {
    name: 'MainContainer',
}
</script>

<style scoped>
.main {
    flex-direction: column;
    display: flex;
    align-items: center;
    justify-content: space-between;
    text-align: center;
}

p {
    font-size: 60%;
    font-size: 50%;
    text-align: center;
    margin: 2%;
}


/* titolo  */
h4 {
    background-image: linear-gradient(
    to right,
    #54b3d6,
    #54b3d6 50%,
    #000 50%
    );
    background-size: 200% 100%;
    background-position: -100%;
    display: inline-block;
    padding: 5px 0;
    position: relative;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    transition: all 0.3s ease-in-out;
}
h4:before {
    content: '';
    background: #54b3d6;
    display: block;
    position: absolute;
    bottom: -3px;
    left: 0;
    width: 0;
    height: 3px;
    transition: all 0.3s ease-in-out;
}
h4:hover {
    background-position: 0;
    scale: 1.1;
}
h4:hover::before {
        width:100%;
}
</style>