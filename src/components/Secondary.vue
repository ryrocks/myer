<template>
    <section class="secondary d-flex">
        <div class="flex-1"></div>
        <div class="d-flex primary flex-3">
            <article>
                <h1>SHAKE UP YOUR<br>SHELVES</h1>
                <hr>
                <p>Humans are inherently lazy and quite often 
                    we are drawn to routine, finding comfort in 
                    seeing the same things day after day. This 
                    is the same for your wardrobe. If it's left 
                    in the same state season to season, you're 
                    only going to reach for the items your eyes 
                    lay on first or that are within reach because 
                    subconciously, you just can't be bothered to 
                    think about it.
                </p>
                <p>Breath a bit of life into your wardrobe by 
                    moving things around. If you normally colour 
                    code your clothes, switch it up and sort them 
                    out by style instead. Looking at things differently 
                    will help those forgotten pieces.
                </p>
            </article>
            <div>
                <img src="https://cdn.glitch.com/4fe2938a-963f-4754-a48c-0af2e2df417d%2Fcontent-image-2.png?1535432066108" />
            </div>
        </div>
        <div class="flex-1"></div>
    </section>
</template>

<script>
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.secondary {
  background-color: #f4d4da;
  padding: 110px 0 60px 0;
}
.secondary div:first-child {
  background: url(https://cdn.glitch.com/4fe2938a-963f-4754-a48c-0af2e2df417d%2Fleaf-middle-left.png?1535432252574)
    no-repeat;
  background-size: contain;
  background-position: left bottom;
  opacity: 0.2;
  margin-bottom: -60px;
}

.primary {
  height: 700px;
}
.primary h1 {
  padding-top: 40px;
}

.primary hr {
  width: 65px;
  background-color: #030303;
  height: 2px;
  border: 0;
  margin: 0 0 2em 0;
}
.primary img {
  height: 100%;
}
.primary article {
  flex: 1 0 50%;
}
article p {
  text-align: left;
  color: #3f3f3f;
  font-size: 20px;
  line-height: 33px;
  overflow-wrap: break-word;
  word-wrap: break-word;
  hyphens: auto;
}
</style>
