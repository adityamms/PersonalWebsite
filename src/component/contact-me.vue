<template>
    <div style="position: relative;top: 1450px;align-items: center;display: flex;text-align: center;justify-content: center;" id="call">    
        <div>
            <a href="https://wa.me/089663651526">
                <div id="bungkus">
                    <img src="../img/phone-call.png" alt="">
                </div>
            </a>
        </div>

    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
    #call{

        #bungkus{
            background-color: grey;
            width: 200px;height: 200px;
            display: flex;
            align-items: center;
            justify-content: center;
            border-radius: 50%;
            border: 3px solid white;
            box-shadow: 2px 2px 2px solid white;
            animation: geeter 1500ms ease-in infinite;
        }
        img{
            aspect-ratio: 1;
            width: 100px;
        }
        }

    
</style>