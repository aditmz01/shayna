<template>
  <section class="women-banner spad">
    <div class="container-fluid">
      <div class="row">
        <div class="col-lg-12 mt-5">
          <carousel
            class="product-slider"
            :nav="false"
            :dots="false"
            :autoplay="true"
          >
            <div class="product-item">
              <div class="pi-pic">
                <img src="img/mickey1.jpg" alt="" />
                <ul>
                  <li class="w-icon active">
                    <a href="#"><i class="icon_bag_alt"></i></a>
                  </li>
                  <li class="quick-view">
                    <router-link to="/product">+ Quick View</router-link>
                  </li>
                </ul>
              </div>
              <div class="pi-text">
                <div class="catagory-name">Coat</div>
                <a href="#">
                  <h5>Mickey Baggy</h5>
                </a>
                <div class="product-price">
                  $14.00
                  <span>$35.00</span>
                </div>
              </div>
            </div>
            <div class="product-item">
              <div class="pi-pic">
                <img src="img/products/women-2.jpg" alt="" />
                <ul>
                  <li class="w-icon active">
                    <a href="#"><i class="icon_bag_alt"></i></a>
                  </li>
                  <li class="quick-view">
                    <router-link to="/product">+ Quick View</router-link>
                  </li>
                </ul>
              </div>
              <div class="pi-text">
                <div class="catagory-name">Shoes</div>
                <a href="#">
                  <h5>Guangzhou sweater</h5>
                </a>
                <div class="product-price">$13.00</div>
              </div>
            </div>
            <div class="product-item">
              <div class="pi-pic">
                <img src="img/products/women-3.jpg" alt="" />
                <ul>
                  <li class="w-icon active">
                    <a href="#"><i class="icon_bag_alt"></i></a>
                  </li>
                  <li class="quick-view">
                    <router-link to="/product">+ Quick View</router-link>
                  </li>
                </ul>
              </div>
              <div class="pi-text">
                <div class="catagory-name">Towel</div>
                <a href="#">
                  <h5>Pure Pineapple</h5>
                </a>
                <div class="product-price">$34.00</div>
              </div>
            </div>
            <div class="product-item">
              <div class="pi-pic">
                <img src="img/products/women-4.jpg" alt="" />
                <ul>
                  <li class="w-icon active">
                    <a href="#"><i class="icon_bag_alt"></i></a>
                  </li>
                  <li class="quick-view">
                    <router-link to="/product">+ Quick View</router-link>
                  </li>
                  <li class="w-icon">
                    <a href="#"><i class="fa fa-random"></i></a>
                  </li>
                </ul>
              </div>
              <div class="pi-text">
                <div class="catagory-name">Towel</div>
                <a href="#">
                  <h5>Converse Shoes</h5>
                </a>
                <div class="product-price">$34.00</div>
              </div>
            </div>
            <div class="product-item">
              <div class="pi-pic">
                <img src="img/products/product-5.jpg" alt="" />
                <ul>
                  <li class="w-icon active">
                    <a href="#"><i class="icon_bag_alt"></i></a>
                  </li>
                  <li class="quick-view">
                    <router-link to="/product">+ Quick View</router-link>
                  </li>
                  <li class="w-icon">
                    <a href="#"><i class="fa fa-random"></i></a>
                  </li>
                </ul>
              </div>
              <div class="pi-text">
                <div class="catagory-name">Towel</div>
                <a href="#">
                  <h5>Converse Shoes</h5>
                </a>
                <div class="product-price">$34.00</div>
              </div>
            </div>
            <div class="product-item">
              <div class="pi-pic">
                <img src="img/products/product-6.jpg" alt="" />
                <ul>
                  <li class="w-icon active">
                    <a href="#"><i class="icon_bag_alt"></i></a>
                  </li>
                  <li class="quick-view">
                    <router-link to="/product">+ Quick View</router-link>
                  </li>
                  <li class="w-icon">
                    <a href="#"><i class="fa fa-random"></i></a>
                  </li>
                </ul>
              </div>
              <div class="pi-text">
                <div class="catagory-name">Towel</div>
                <a href="#">
                  <h5>Converse Shoes</h5>
                </a>
                <div class="product-price">$34.00</div>
              </div>
            </div>
            <div class="product-item">
              <div class="pi-pic">
                <img src="img/products/product-9.jpg" alt="" />
                <ul>
                  <li class="w-icon active">
                    <a href="#"><i class="icon_bag_alt"></i></a>
                  </li>
                  <li class="quick-view">
                    <router-link to="/product">+ Quick View</router-link>
                  </li>
                  <li class="w-icon">
                    <a href="#"><i class="fa fa-random"></i></a>
                  </li>
                </ul>
              </div>
              <div class="pi-text">
                <div class="catagory-name">Towel</div>
                <a href="#">
                  <h5>Converse Shoes</h5>
                </a>
                <div class="product-price">$34.00</div>
              </div>
            </div>
            <div class="product-item">
              <div class="pi-pic">
                <img src="img/products/product-8.jpg" alt="" />
                <ul>
                  <li class="w-icon active">
                    <a href="#"><i class="icon_bag_alt"></i></a>
                  </li>
                  <li class="quick-view">
                    <router-link to="/product">+ Quick View</router-link>
                  </li>
                  <li class="w-icon">
                    <a href="#"><i class="fa fa-random"></i></a>
                  </li>
                </ul>
              </div>
              <div class="pi-text">
                <div class="catagory-name">Towel</div>
                <a href="#">
                  <h5>Converse Shoes</h5>
                </a>
                <div class="product-price">$34.00</div>
              </div>
            </div>
          </carousel>
        </div>
      </div>
    </div>
  </section>
  <!-- Women Banner Section End -->
</template>

<script>
import carousel from "vue-owl-carousel";
import axios from "axios";

export default {
  name: "WomanShayna",
  components: {
    carousel,
  },
  data() {
    return {
      products: [],
      keranjangUser: [],
    };
  },
  mounted() {
    axios
      .get("http://shayna-backend.belajarkoding.com/api/products")
      .then((res) => (this.products = res.data.data.data))
      // eslint-disable-next-line no-console
      .catch((err) => console.log(err));
  },
  methods: {
    saveKeranjang(idProduct, nameProduct, priceProduct, photoProduct) {
      var productStored = {
        id: idProduct,
        name: nameProduct,
        price: priceProduct,
        photo: photoProduct,
      };

      this.keranjangUser.push(productStored);
      const parsed = JSON.stringify(this.keranjangUser);
      localStorage.setItem("keranjangUser", parsed);
    },
  },
};
</script>

<style scoped>
.product-item {
  margin-right: 25px;
}
.pi-pic img {
  height: 450px;
}
</style>