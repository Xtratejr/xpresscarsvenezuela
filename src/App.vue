<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <header class="">
    <div class="header">
      <div class="logo-container">
        <img alt="Vue logo" class="logo" src="/img/logo_large_plus.png" width="125" height="125" style="max-width: 134px;"/>
      </div>
      <div class="search-container">
        <input type="search" name="" id="">
      </div>
      <div class="promo-container">
        <img src="https://http2.mlstatic.com/D_NQ_612768-MLA54902434366_042023-OO.webp" alt="">
      </div>
    </div>
    <div class="navigation-area">
      <div class="categories">
        <ul>
          <li>
            <span>categorias</span>
            <ul>
              <li></li>
            </ul>
          </li>
        </ul>
      </div>
      <div class="nav-helper"></div>
      <div class="account"></div>
    </div>
  </header> 

  <main>
    <div class="wrapper">
      <div class="banner-slider">
        <div>
          <img src="/img/banner-2.webp" alt=""/>
        </div>
        <div></div>
        <div></div>
      </div>
      
      <div class="products-wrapper">
        <h2>Ofertas de la semana</h2>
        <div class="cards-wrapper">
          <div class="product">
            <img src="/img/product-1.webp" alt="">
          </div>
          <div class="product">
            <img src="/img/product-2.webp" alt="">
          </div>
          <div class="product">
            <img src="/img/product-5.webp" alt="">
          </div>
          <div class="product">
            <img src="/img/product-4.webp" alt="">
          </div>
          <div class="product">
            <img src="/img/product-5.webp" alt="">
          </div>
        </div>
      </div>

      <div class="double-categories">
        <div>
          <h2>Descubre Nuevas Experiencias</h2>

          <div class="new-cards">
            <div class="left">
              <div>
                <span>Envio Gratis + EXPRESS</span>
                <span>TODO EN CELULARES</span>
                <button>
                  <a>Ver Mas</a>
                </button>
              </div>
              <div>
                <img src="/img/product-example-1.webp" />
              </div>
            </div>
            <div class="right">
              <div>
                <span>Envio Gratis + EXPRESS</span>
                <span>TODO EN CELULARES</span>
                <button>
                  <a>Ver Mas</a>
                </button>
              </div>
              <div>
                <img src="/img/product-example-2.webp" />
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="shops-menu">
        <div>
          <h2>Las mejores tiendas te esperan <a>Ver tiendas</a></h2>

          <section class="new-cards">
            <div class="special-card">
              <div class="sup-banner">
                <div class="top"></div>
                <div class="logo"></div>
              </div>
              <div class="content">
                <h2>Old Man Emu</h2>
                <div class="tri-products">
                  <img src="/img/tri-1-example.webp" alt="" />
                  <img src="/img/tri-2-example.webp" alt="" />
                  <img src="/img/tri-3-example.webp" alt="" />
                </div>
              </div>
            </div>
            <div class="special-card">
              <div class="sup-banner">
                <div class="top"></div>
                <div class="logo"></div>
              </div>
              <div class="content">
                <h2>Old Man Emu</h2>
                <div class="tri-products">
                  <img src="/img/tri-1-example.webp" alt="" />
                  <img src="/img/tri-2-example.webp" alt="" />
                  <img src="/img/tri-3-example.webp" alt="" />
                </div>
              </div>
            </div>
            <div class="special-card">
              <div class="sup-banner">
                <div class="top"></div>
                <div class="logo"></div>
              </div>
              <div class="content">
                <h2>Old Man Emu</h2>
                <div class="tri-products">
                  <img src="/img/tri-1-example.webp" alt="" />
                  <img src="/img/tri-2-example.webp" alt="" />
                  <img src="/img/tri-3-example.webp" alt="" />
                </div>
              </div>
            </div>
            <div class="special-card">
              <div class="sup-banner">
                <div class="top"></div>
                <div class="logo"></div>
              </div>
              <div class="content">
                <h2>Old Man Emu</h2>
                <div class="tri-products">
                  <img src="/img/tri-1-example.webp" alt="" />
                  <img src="/img/tri-2-example.webp" alt="" />
                  <img src="/img/tri-3-example.webp" alt="" />
                </div>
              </div>
            </div>

            
          </section>
        </div>
      </div>

      <section class="final-ads">
        <div>
          <img src="">
          <h2>Compra sin moverte</h2>
          <p>
            Encuentra lo que necesitas, y 
            coordina el pago y la entrega con el vendedor.
             Es fácil y rápido. ¡Todos podemos hacerlo!
          </p>
          <a>Cómo comprar en Mercado Libre</a>
        </div>
        <div>
          <img src="">
          <h2>Recibe tu producto</h2>
          <p>
            Acuerda la entrega de tu compra con el vendedor. 
            Puedes recibirlo en tu casa, en la oficina o retirarlo. 
            ¡Tú decides qué prefieres!
          </p>
          <a>Cómo coordino la entrega</a>
        </div>
        <div>
          <img src="">
          <h2>Vende gratis</h2>
          <p>
            Miles de personas quieren lo que ofreces. 
            Publica y verás qué pronto llegan las compras. 
            ¡Tú no pagas nada!
          </p>
          <a>Cómo vender en Mercado Libre</a>
        </div>
      </section>


    </div>
    <!-- <TheWelcome /> -->
  </main>
  <footer>
    <div></div>
  </footer>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {

  .logo {
    margin: 0 2rem 0 0;
  }

}
</style>
