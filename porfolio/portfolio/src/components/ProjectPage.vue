<template>
    <div>        
        <div class="container">
            <div class="row">
                <div class="col-md-12 text-center">
                <h3 class="animate-charcter">What I learn</h3>
                </div>
            </div>
        </div>
        <div class="box-card">
            <div class="ciao">html5</div>
            <div class="ciao">CSS</div>
            <div class="ciao">JavaScript</div>
            <div class="ciao">VueJS</div>
            <div class="ciao">Bootrsap</div>
        </div>
        <div class="backend">
            <div class="ciao">PHP</div>
            <div class="ciao">Laravel</div>
            <div class="ciao">SQL</div>
            <div class="ciao">C#</div>
            <div class="ciao">.NET</div>
        </div>

        <div class="now">
            <p>what i'm studing now:</p> 
            <p class="ang">Angular :)</p>
        </div>
    </div>
</template>

<script>
export default {
    name: 'ProjectPage',
    }
</script>


<style scoped>

.now {
    margin-top: 30%;
    display: flex;
    justify-content: center;
    gap: 5%;
}

.ang {
    animation: rainbow 5s infinite;
}

.ang:hover {
    scale: 1.1;
    transition: 1.3s;
}
@keyframes rainbow {
    0% { color: red; }
    14% { color: orange; }
    28% { color: yellow; }
    42% { color: green; }
    57% { color: blue; }
    71% { color: indigo; }
    85% { color: violet; }
    100% { color: red; }
}



.backend {
    margin-top: 10%;
    display: flex;
    justify-content: space-between;
    gap: 10%;
}
.container {
    display: flex;
    justify-content: center;
}



.animate-charcter
{
    text-transform: uppercase;
    background-image: linear-gradient(
        -225deg,
        #231557 0%,
        #44107a 29%,
        #ff1361 67%,
        #fff800 100%
    );
    background-size: auto auto;
    background-clip: border-box;
    background-size: 200% auto;
    color: #fff;
    background-clip: text;
    text-fill-color: transparent;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    animation: textclip 2s linear infinite;
    display: inline-block;
        font-size: 50px;
}

@keyframes textclip {
    to {
        background-position: 200% center;
    }
}

.animate-charcter:hover {
    scale: 1.2;
    transition: 1s;
}


/* card  */

.box-card {
    display: flex;
    align-items: center;
    justify-content: space-around;
    gap: 10%;
}

.card {
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
.card:before {
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
.card:hover {
  background-position: 0;
  scale: 1.1;
}
.card:hover::before {
  width:100%;
}



.ciao {
    background-image: linear-gradient(
    to right,
    #ff1361,
    #ff1361 50%,
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
.ciao:before {
    content: '';
    background: #ff1361;
    display: block;
    position: absolute;
    bottom: -3px;
    left: 0;
    width: 0;
    height: 3px;
    transition: all 0.3s ease-in-out;
}
.ciao:hover {
    background-position: 0;
    scale: 1.1;
}
.ciao:hover::before {
        width:100%;
}


</style>