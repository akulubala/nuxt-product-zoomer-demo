<template>
  <div class="container">
    <ProductZoomer :base-images="images" :base-zoomer-options="zoomerOptions"></ProductZoomer>
  </div>
</template>

<script>
import Logo from "~/components/Logo.vue";

export default {
  data() {
    return {
      images: {
        thumbs: [
          {
            id: 1,
            url:
              "https://yoohooworld.com/assets/images/vue_product_zoomer/thumbs/1.jpeg"
          },
          {
            id: 2,
            url:
              "https://yoohooworld.com/assets/images/vue_product_zoomer/thumbs/2.jpeg"
          },
          {
            id: 3,
            url:
              "https://yoohooworld.com/assets/images/vue_product_zoomer/thumbs/3.jpeg"
          },
          {
            id: 4,
            url:
              "https://yoohooworld.com/assets/images/vue_product_zoomer/thumbs/4.jpeg"
          },
          {
            id: 5,
            url:
              "https://yoohooworld.com/assets/images/vue_product_zoomer/thumbs/5.jpeg"
          },
          {
            id: 6,
            url:
              "https://yoohooworld.com/assets/images/vue_product_zoomer/thumbs/6.jpeg"
          },
          {
            id: 7,
            url:
              "https://yoohooworld.com/assets/images/vue_product_zoomer/thumbs/7.jpeg"
          },
          {
            id: 8,
            url:
              "https://yoohooworld.com/assets/images/vue_product_zoomer/thumbs/8.jpeg"
          },
          {
            id: 9,
            url:
              "https://yoohooworld.com/assets/images/vue_product_zoomer/thumbs/9.jpeg"
          }
        ],
        normal_size: [
          {
            id: 1,
            url:
              "https://yoohooworld.com/assets/images/vue_product_zoomer/normal_size/1.jpeg"
          },
          {
            id: 2,
            url:
              "https://yoohooworld.com/assets/images/vue_product_zoomer/normal_size/2.jpeg"
          },
          {
            id: 3,
            url:
              "https://yoohooworld.com/assets/images/vue_product_zoomer/normal_size/3.jpeg"
          },
          {
            id: 4,
            url:
              "https://yoohooworld.com/assets/images/vue_product_zoomer/normal_size/4.jpeg"
          },
          {
            id: 5,
            url:
              "https://yoohooworld.com/assets/images/vue_product_zoomer/normal_size/5.jpeg"
          },
          {
            id: 6,
            url:
              "https://yoohooworld.com/assets/images/vue_product_zoomer/normal_size/6.jpeg"
          },
          {
            id: 7,
            url:
              "https://yoohooworld.com/assets/images/vue_product_zoomer/normal_size/7.jpeg"
          },
          {
            id: 8,
            url:
              "https://yoohooworld.com/assets/images/vue_product_zoomer/normal_size/8.jpeg"
          },
          {
            id: 9,
            url:
              "https://yoohooworld.com/assets/images/vue_product_zoomer/normal_size/9.jpeg"
          }
        ],
        large_size: [
          {
            id: 1,
            url:
              "https://yoohooworld.com/assets/images/vue_product_zoomer/large_size/1.jpeg"
          },
          {
            id: 2,
            url:
              "https://yoohooworld.com/assets/images/vue_product_zoomer/large_size/2.jpeg"
          },
          {
            id: 3,
            url:
              "https://yoohooworld.com/assets/images/vue_product_zoomer/large_size/3.jpeg"
          },
          {
            id: 4,
            url:
              "https://yoohooworld.com/assets/images/vue_product_zoomer/large_size/4.jpeg"
          },
          {
            id: 5,
            url:
              "https://yoohooworld.com/assets/images/vue_product_zoomer/large_size/5.jpeg"
          },
          {
            id: 6,
            url:
              "https://yoohooworld.com/assets/images/vue_product_zoomer/large_size/6.jpeg"
          },
          {
            id: 7,
            url:
              "https://yoohooworld.com/assets/images/vue_product_zoomer/large_size/7.jpeg"
          },
          {
            id: 8,
            url:
              "https://yoohooworld.com/assets/images/vue_product_zoomer/large_size/8.jpeg"
          },
          {
            id: 9,
            url:
              "https://yoohooworld.com/assets/images/vue_product_zoomer/large_size/9.jpeg"
          }
        ]
      },
      zoomerOptions: {
        zoomFactor: 3,
        pane: "pane",
        hoverDelay: 300,
        namespace: "zoomer-left",
        move_by_click: false,
        scroll_items: 4,
        choosed_thumb_border_color: "#dd2c00",
        scroller_position: "left"
      }
    };
  }
};
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
