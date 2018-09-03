<template>
    <section class="third d-flex flex-column">
        <div class="d-flex primary-wrapper">
            <div class="flex-1"></div>
            <article class="primary flex-2">
                <h1 class="text-center">REMOVE ALL THE BLACK</h1>
                <hr>
                <p>
                    No need to freak out, this is only a temporary fix 
                    but one that will do you wonders. Black clothing for 
                    me represents a comfortable but chic look. You could 
                    be rocking up to work wearing joggers and a daggy 
                    t-shirt but if it's all black, it's sah farshun.
                </p>
                <p>
                    Get all the black out of your sight. Whether you throw 
                    your black clothing into the back of your car of drop 
                    them off at your parents' house I don't care. Just get 
                    rid of it. After a week, you'll find you're less dependent 
                    on black items that usually fill the gaps in your outfilts. 
                    The benefit of doing it at this time of the year is that 
                    clothing stores are thankfully blessing us with colourful, 
                    summer tones. Then, reward yourself by taking yourself 
                    shopping to select one.
                </p>
            </article>
            <div class="flex-1"></div>
        </div>
        <div class="carousel d-flex">
            <div></div>
            <div></div>
            <div></div>
        </div>
        
        <div class="d-flex primary-wrapper">
            <div class="flex-1"></div>
            <article class="primary flex-2">
                <h1 class="text-center">DOLL UP THE BASICS</h1>
                <hr>
                <p>
                    If you ever find yourself erring on the side of caution 
                    and sticking to a basic tee with jeans, try digging into 
                    your accessories to create some versatility. Rachael suggests 
                    playing with statement pieces to zhoosh up an outfit: "A great 
                    pair of heels, a long drop earring, especially from Christie 
                    Nicolaides, a trailored blazer or a bold lip colour."
                </p>
                <p>
                    Thankfully the warmer seasons are bringing colour and vibrancy 
                    to accessories. Play with headscarves, statement earrings, chunky 
                    chains or bright shoes to spice things up. Be daring and 
                    brave when it comes to your accessories and you'll be pleasantly 
                    surprised by the outcome, Honestly, you could probably get 
                    away with the same white tee and jeans for a 
                </p>
            </article>
            <div class="flex-1"></div>
        </div>
         
        <div class="d-flex gallery justify-content-center">
            <div class="d-flex flex-column left">
                <div class="flex-1"></div>
                <div class="flex-1"></div>
            </div>
            <div class="right"></div>

        </div>
    </section>
</template>

<script>


</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.third {
  margin-top: 60px;
}

.primary-wrapper:first-child div:first-child {
  background: url('https://cdn.glitch.com/4fe2938a-963f-4754-a48c-0af2e2df417d%2Fflower-middle-left.png?1535432059252')
    left no-repeat;
  background-size: contain;
}

article {
  padding: 0 20px;
}

article hr {
  width: 65px;
  background-color: #030303;
  height: 2px;
  border: 0;
}
article p {
  text-align: left;
  color: #3f3f3f;
  font-size: 21px;
  line-height: 33px;
  overflow-wrap: break-word;
  word-wrap: break-word;
  hyphens: auto;
}

.carousel {
    min-height: 700px;
}

.carousel div {
    background-size: contain;
    width: 800px;
}

.carousel div:first-child {
    background: url('https://cdn.glitch.com/4fe2938a-963f-4754-a48c-0af2e2df417d%2Fslider-1.png?1535432071389')
    center no-repeat;
}

.carousel div:nth-child(2) {
    background: url('https://cdn.glitch.com/4fe2938a-963f-4754-a48c-0af2e2df417d%2Fslider-2.png?1535432067649')
    center no-repeat;
}

.carousel div:last-child {
    background: url('https://cdn.glitch.com/4fe2938a-963f-4754-a48c-0af2e2df417d%2Fslider-3.png?1535432222217')
    center no-repeat;
}

.gallery {
    min-height: 425px;
}

.gallery .left {
    width: 400px;
}

.gallery .right {
    width: 500px;

}

.gallery .left div:first-child {
  background: url('https://cdn.glitch.com/4fe2938a-963f-4754-a48c-0af2e2df417d%2Fmosaic-1.png?1535432059511')
    center no-repeat;
  background-size: contain;
  margin-bottom: 10px;
}

.gallery .left div:last-child {
  background: url('https://cdn.glitch.com/4fe2938a-963f-4754-a48c-0af2e2df417d%2Fmosaic-2.png?1535432063562')
    center no-repeat;
  background-size: contain;
  margin-top: 10px;
}

.gallery .right {
  background: url('https://cdn.glitch.com/4fe2938a-963f-4754-a48c-0af2e2df417d%2Fmosaic-3.png?1535432064870')
    center no-repeat;
  background-size: contain;
}
</style>
