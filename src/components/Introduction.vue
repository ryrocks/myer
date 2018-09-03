<template>
    <section class="brand">
      <img src="https://cdn.glitch.com/4fe2938a-963f-4754-a48c-0af2e2df417d%2Flogo.png?1535432056985" />
      <p class="intro">
          whimn.com.au and Myer want to inspire<br> you to spice up your fashion this summer.
      </p>
        <aside>Story by Caitlin Chander | whimn.com.au</aside>
        <div>
            <div class="article-wrapper d-flex">
                <article class="flex-1">
                    <h1>FASHION FATIGUE CAN STRIKE WHEN YOU</h1>
                    <h1>LEAST EXPECT IT</h1>
                    <hr>
                    <div>
                    <p>After three months of winter, my fashion light bulb has well and truly blown out. I'm now at point 
                        where I'm so sick at the sight of my mumcut jeans and oversized sweater dresses that every morning
                        I find myself irrationaly at my wardrobe and throwing myself onto the bed in despair.
                    </p>
                    <p>Dressing for the day is meant to inspire you, to get you up and going like an everyday YAS queen. So if
                        your wardrobe leaves you stuck in bed with feelings of disdain, then we've workded with Myer ambassador 
                        Rachael Finch to bring you ways to pull yourself out of depths of fashion boredom this season.
                    </p>
                    </div>
                </article>
            </div>
            <main class="d-flex">
                <div class="d-flex flex-column gap flex-1">
                    <div class="flex-3"></div>
                    <div class="flex-1"></div>
                </div>
                <div class="primary flex-3">
                    <img src="https://cdn.glitch.com/4fe2938a-963f-4754-a48c-0af2e2df417d%2Fcontent-image-1.png?1535432246589" />
                </div>
                <div class="d-flex flex-column gap flex-1">
                    <div class="flex-3"></div>
                    <div class="flex-1"></div>
                </div>
            </main>
        </div>
    </section>
</template>

<script>
// export default {
//   name: 'Intro',
//   props: {
//     description: String
//   }
// };
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.brand {
  background: #f7f7f7;
  text-align: center;
  padding: 430px 0 0;
}

.brand .intro {
  font-size: 25px;
  margin-bottom: 60px;
}
aside {
  margin: 60px 235px 40px 235px;
  padding: 20px 0;
  text-align: left;
  border-top: 1px solid #cfcfcf;
  border-bottom: 1px solid #cfcfcf;
  color: #bcbcbc;
}

.article-wrapper:before {
  margin-bottom: 60px;
  background: url("https://cdn.glitch.com/4fe2938a-963f-4754-a48c-0af2e2df417d%2Fleaf-top-left.png?1535432058904")
    center no-repeat;
  background-size: contain;
  display: inline-block;
  width: 320px;
  content: "";
}
.article-wrapper:after {
  background: url("https://cdn.glitch.com/4fe2938a-963f-4754-a48c-0af2e2df417d%2Fleaf-top-right.png?1535432060593")
    center no-repeat;
  margin-top: 60px;
  background-size: contain;
  display: inline-block;
  width: 320px;
  content: "";
}

article {
  color: #bc8c1a;
  padding: 0 10px;
}
article hr {
  width: 65px;
  background-color: #bc8c1a;
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

article p:first-child:first-letter {
  color: #bc8c1a;
  float: left;
  font-size: 100px;
  line-height: 65px;
  padding: 10px 30px 15px 3px;
}

.primary {
  height: 600px;
}
.primary img {
  height: 100%;
}

.gap div:last-child {
    background-color: #f4d4da;
}
</style>
