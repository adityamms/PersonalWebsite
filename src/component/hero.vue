<template>
    <div id="hero" style="position: relative; top: 100px;padding: 30px;">
        <div id="container">
        <div id="image" data-aos="fade-in" data-aos-duration="1200">
            <img src="../img/pp.jpg" alt="" >
        </div>
        <div style="max-width: 350px;" data-aos="fade-right" data-aos-duration="1200">
            <h2>
               aditya marzuk
           </h2>
                <p>
                    web developer
                </p>
             <p style="text-align:start;">
                design and develop websites and web applications by using web technologies such as HTML, CSS, DOM, and JavaScript, that either run on the Open Web Platform or function as compilation input for non-web platform environments and make sure the design is responsive every part of it
             </p>
        </div>
    </div>
</div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>

#hero{

    #container{
    position: relative;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 20px;
    }

    #image>img{
        border-radius: 50%;
        aspect-ratio: 1;
        width: 200px;
        border: 5px solid rgb(0, 0, 0);
        box-shadow: 2px 5px 2px white;
        filter: saturate(0);
    }

    #image>img:hover{
               filter: saturate(1);
    }

    button{
        position: absolute;
        width: fit-content;
    }

    p{
        text-transform: capitalize;
    }

}
</style>