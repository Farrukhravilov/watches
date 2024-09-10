<template>
  <div>
    <div class="product-modal">
      <div class="container">
        <div class="product__modal-text-wrapper">
            <h4>
              Mahsulot yetib borishi uchun ma’lumotlaringizni to‘g‘ri to‘ldiring
            </h4>
            <button>
              <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none"><path d="M9 7.58579L12 10.5858L15 7.58579L16.4142 9L13.4142 12L16.4142 15L15 16.4142L12 13.4142L9 16.4142L7.58579 15L10.5858 12L7.58579 9L9 7.58579Z" fill="black"/><path fill-rule="evenodd" clip-rule="evenodd" d="M1 12C1 5.92487 5.92487 1 12 1C18.0751 1 23 5.92487 23 12C23 18.0751 18.0751 23 12 23C5.92487 23 1 18.0751 1 12ZM12 3C7.02944 3 3 7.02944 3 12C3 16.9706 7.02944 21 12 21C16.9706 21 21 16.9706 21 12C21 7.02944 16.9706 3 12 3Z" fill="black"/></svg>
            </button>
        </div>
        <div class="product__modal-wrap">
          <div class="product__wrap-left">
            <div class="main-left">
              <img src="@/assets/images/png/banner.png" alt="" />
            </div>
            <div class="product__left-text">
              <h5>EUTOUR Magnetic Eng yaxshi yog'och soatlar E031</h5>
              <p>600 000 <span>uzs</span></p>
            </div>
          </div>
          <div class="product__wrap-right">
            <div class="falsehood-left">
              <form>
                <p>
                  Talab yoki takliflaringiz bo‘lsa, maʼlumotlaringizni qoldiring.
                  Tez orada siz bilan bog‘lanamiz.
                </p>
                <div class="falsehood-inp">
                  <span>Ismingiz</span>
                  <input placeholder="Sobirjon" type="text" />
                </div>
                <div class="falsehood-inp">
                  <span>Telefon raqamingiz</span>
                  <input placeholder="+998 90 123 45 67" type="text" />
                </div>
                <div class="falsehood-inp">
                  <span>Xabaringizni yozing</span>
                  <input placeholder="Xabar kiriting...." type="text" />
                </div>
                <button>Yuborish</button>
              </form>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
// const openBuy = ref(false)

// const close = ref(false)
// const closeBuy = ref(true)
// const { openBuy } = defineProps({
//   openBuy: {
//     type: Boolean,
//   },
// });

</script>

<style lang="scss" scoped></style>
