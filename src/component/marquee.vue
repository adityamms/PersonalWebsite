<template>
<div style="position: relative;top: 750px; display: flex; justify-content: center;display: grid; gap: 100px;" id="kotak-marque">
    <div><h1 style="text-align: center;" id="toolsku" data-aos="fade-right" data-aos-duration="1200">Tools</h1></div>
    <div class="marquee">
        <div style="display:flexbox; max-height: 100px;">
      <img src="../img/html-5.png" alt="html"/>
      <img src="../img/css-3-besar.png" alt="css"/>
      <img src="../img/js-(besar).png" alt="javascript"/>
      <img src="../img/react-besar.png" alt="react"/>
      <img src="../img/python.png" alt="phyton"/>
      <img src="../img/bootstrap-(besar).png" alt="bootstrap"/>
      <img src="../img/sass-besar.png" alt="sass"/>
      <img src="../img/tailwind.png" alt="tailwind">
      <img src="../img/instagram.png" alt="instagram">
      <img src="../img/linkedin.png" alt="linkedin">
      <img src="../img/paypal.png" alt="paypall">
      <img src="../img/bitcoin.png" alt="bitcoin">
      <img src="../img/adobe-photoshop.png" alt="adobe">
      <img src="../img/figma.png" alt="figma">
</div>
</div>
</div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
.marquee{
    img{
       margin-left: 50px; 
       height: 80px;
       width: 80px;
       filter: saturate(0);
    }
    img:hover{
        filter: saturate(1);
    }
}
        .marquee {
            width: 100%;
  margin: 0 auto;
  overflow: hidden;
  box-sizing: border-box;
}

.marquee div {
  display: inline-block;
  width: max-content;
  padding-left: 100%;
  /* show the marquee just outside the paragraph */
  will-change: transform;
  animation: marquee 15s linear infinite;
}

.marquee div:hover {
  animation-play-state: paused
}



@keyframes marquee {
  0% { transform: translate(0, 0); }
  100% { transform: translate(-100%, 0); }
}


/* Respect user preferences about animations */

@media (prefers-reduced-motion: reduce) {
  .marquee div {
    animation-iteration-count: 1;
    animation-duration: 0.01; 
    /* instead of animation: none, so an animationend event is */
 
    }
}
    
</style>