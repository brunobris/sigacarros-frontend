<script>
export default {
  name: 'Anuncio',
  data () {
    return {
     
    }
  }
}
</script>
<template>
<section id="change-items" class="item-grid">
    <article>	
        <a href="one-products.html" class="single-image picture video">
            <img src="@/assets/images/temp/thumb-1.jpg" alt="">
        </a>

        <div class="detailed">
            <h6 class="title-item">
                <a href="one-products.html">2009 Aston Martin DB9</a>
            </h6>
            <span class="price">$8.966</span>
            <div class="clear"></div>
            <ul class="list-entry">
                <li><b class="label">Engine:</b><span>1.4i TS 5Dr</span></li>
                <li><b class="label">Mileage:</b><span>75000</span></li>	
                <li><b class="label">Year:</b><span>2009</span></li>	
                <li><b class="label">Location:</b><span>New Jersey/ Newark</span></li>	
            </ul><!--/ .list-entry-->
            <label class="compare"><input type="checkbox" />Compare</label>
            <a href="one-products.html" class="button orange">Detalhes</a>
        </div><!--/ .detailed-->
    </article>
    </section>
</template>

<style @import src="@/assets/styles/style.css"></style>