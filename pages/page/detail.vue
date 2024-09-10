<template>
  <div>
    <div class="main">
      <div class="container">
        <div class="main-wrap">
          <div class="main-left">
            <!-- Отображаем выбранную картинку -->
            <img :src="selectedImage" alt="selected image" />
          </div>
          <div class="main-right">
            <div class="main-rigt-wrap">
              <h4>EUTOUR Magnetic Eng yaxshi yog'och soatlar E031</h4>
              <h6>Buyurtmangiz 2-9-sentyabrgacha yetkaziladi</h6>
              <div class="main-right-wrap">
                <div class="right-title">
                  <h5 class="right-price">600 000</h5>
                  <span class="right-uzsd">uzs</span>
                  <div class="right-uzs">
                    <span>150 uzs / oyiga</span>
                  </div>
                </div>
              </div>
              <button class="main-count">
                <span @click="decrease"> - </span>
                <h4>{{ count }}</h4>
                <span @click="increase">+</span>
              </button>
              <!-- <button class="main-count">
                <span> - </span>
                <h4>1</h4>
                <span>+</span>
              </button> -->
            </div>

            <div class="main-all-wrap">
              <div class="main-box">
                <!-- Цикл по картинкам для отображения внутри main-box -->
                <div
                  v-for="(image, index) in images"
                  :key="index"
                  class="main-block"
                  @click="selectImage(index)"
                  :class="{ active: selectedIndex === index }"
                >
                  <img :src="image" alt="photo" />
                </div>
              </div>
              <div class="main-info">
                <button class="info-btnn">Batafsil ma’limot olish</button>
                <button class="info-btn" @click="openBuy = true">
                  Buyurtmani rasmiylashtirish
                </button>
              </div>
            </div>
          </div>
        </div>
        <div class="main-characters">
          <!-- Характеристики и описание -->
          <!-- Оставляю это без изменений -->
        </div>
      </div>
    </div>
    <!-- <div class="main">
      <div class="container">
        <div class="main-wrap">
          <div class="main-left">
            <img src="@/assets/images/png/banner.png" alt="" />
          </div>
          <div class="main-right">

            <div class="main-rigt-wrap">
              <h4>EUTOUR Magnetic Eng yaxshi yog'och soatlar E031</h4>
              <h6>Buyurtmangiz 2-9-sentyabrgacha yetkaziladi</h6>
              <div class="main-right-wrap">
                <div class="right-title">
                  <h5 class="right-price">600 000</h5>
                  <span class="right-uzsd">uzs</span>
                  <div class="right-uzs">
                    <span>150 uzs / oyiga</span>
                  </div>
                </div>
              </div>
              <button class="main-count">
                <span> - </span>
                <h4>1</h4>
                <span>+</span>
              </button>
            </div>


            <div class="main-all-wrap">
              <div class="main-box">
                <div class="main-block"><img src="https://picsum.photos/200/300" alt="photo" /></div>
                <div class="main-blockk"><img src="https://picsum.photos/seed/picsum/200/300" alt="photo"></div>
                <div class="main-blockk"><img src="https://picsum.photos/200/300?grayscale" alt="photo"  /></div>
                <div class="main-blockk"><img src="https://picsum.photos/200/300?grayscale"  alt="photo2"  /></div>
              </div>
              <div class="main-info">
                <button class="info-btnn">Batafsil ma’limot olish</button>
                <button class="info-btn" @click="openBuy = true" >Buyurtmani rasmiylashtirish</button>
              </div>
            </div>
          </div>
        </div>
        <div class="main-characters">
          <div class="characters-left">
            <h1>Xarakteristikasi</h1>
            <ul>
              <li>
                Model raqami<NuxtLink to="/" class="character-name"
                  >E031A-M1</NuxtLink
                >
              </li>
              <li>
                Rangi<NuxtLink to="/" class="character-name">Qora</NuxtLink>
              </li>
              <li>
                Harakat<NuxtLink to="/" class="character-name"
                  >RONDA Quartz-M1</NuxtLink
                >
              </li>
              <li>
                Batareya<NuxtLink to="/" class="character-name"
                  >920 tugmali hujayra (45 oy)</NuxtLink
                >
              </li>
              <li>
                Suvga chidamliligi<NuxtLink to="/" class="character-name"
                  >3ATM</NuxtLink
                >
              </li>
              <li>
                Koson materiali:<NuxtLink to="/" class="character-name"
                  >mis (PVD)</NuxtLink
                >
              </li>
              <li>
                Dial<NuxtLink to="/" class="character-name"
                  >Tabiiy yog'och
                </NuxtLink>
              </li>
              <li>
                Band materiali<NuxtLink to="/" class="character-name"
                  >Tabiiy yog'och</NuxtLink
                >
              </li>
              <li>
                Koson diametri<NuxtLink to="/" class="character-name"
                  >40mm</NuxtLink
                >
              </li>
              <li>
                Band uzunligi<NuxtLink to="/" class="character-name"
                  >Moslashuvchan
                </NuxtLink>
              </li>
            </ul>
          </div>
          <div class="characters-right">
            <h1>Ta’rifi</h1>
            <span>Tabiiy yog'och material</span>
            <p>
              58% mis qotishmasidan va tabiiy qizil sandal daraxtidan
              tayyorlangan har bir magnitli yog'och soat qo'lda ehtiyotkorlik
              bilan ishlangan. Ushbu soatlarning har bir detalidan ularning ter
              va donoligini his qilishingiz mumkin. Ularning barchasi toksik
              bo'lmagan va hipoalerjenikdir.
            </p>
            <span>Tabiiy yog'och material Og'ir yuk komponentlari </span>
            <p>
              Shveytsariyalik RONDA kvarts harakati bilan jihozlangan bu yog'och
              soatlar bardoshli va har bir harakatingiz uchun aniq vaqtni ushlab
              turishi mumkin. Batareyaning ishlash muddati 45 oygacha.
            </p>
            <span>Moslashtirilgan yog'och soat tasmasi </span>
            <p>
              Yog'ochdan yasalgan magnit soatlar yog'ochning tabiiy go'zalligini
              saqlaydigan, bo'yoq va kimyoviy moddalarsiz, nafis ishlangan
              EUTOUR yog'och bantlari bilan birga keladi. Har bir guruh noyob
              bo'lib, nafislik va estetikani taqdim etadi. O'lchamlarni sozlash
              uchun professional vositalar taqdim etiladi, bu esa soat bandini
              oson sozlash imkonini beradi.
            </p>
            <span>3ATM suv o'tkazmaydigan jism </span>
            <p>
              30 metrgacha (3ATM) suvga chidamliligi bilan bu soatlar ter,
              yomg'ir yoki suvning chayqalishiga bardosh bera oladi. Biroq, ular
              suzish, dush olish, sho'ng'in qilish yoki snorkeling uchun mos
              emas.
            </p>
          </div>
        </div>
      </div>
    </div> -->
    <div class="speed-questions">
      <div class="container">
        <h1 class="questions-title">Tez-tez berildigan savollar</h1>

        <div class="question-wrap">
          <div
            v-for="(question, index) in questions"
            :key="index"
            class="question-card"
          >
            <div class="card-wrap">
              <div class="class__wrap-title" @click="toggleQuestion(index)">
                <h2>{{ question.title }}</h2>
                <img
                  :src="isQuestionOpen(index) ? minusIcon : plusIcon"
                  alt="toggle"
                />
              </div>
              <!-- Показываем текст только если вопрос открыт -->
              <p v-if="isQuestionOpen(index)">{{ question.text }}</p>
            </div>
          </div>
        </div>
        <!-- <div class="question-wrap">
            <div class="question-card">
              <div class="card-wrap">
                <div class="class__wrap-title" >
                  <h2>Soatlarni qanday buyurtma qilsam bo ‘ladi?</h2>
                  <img src="@/assets/images/svg/Minus.svg" alt="minus" />
                </div>
                <p>1 Oʻzingizga yoqqan soatni tanlab,  shaxsiy maʼlumotlaringizni kiriting. Tez orada siz bilan bogʼlanamiz.
                   <br></br> 2  Soatlarni saytdagi telefon raqamimizga aloqaga chiqib, buyurtma berishingiz mumkin.</p>
              </div>
              <div class="card-wrap">
                <div class="class__wrap-title" >
                      <h2>Soat sotib olsam dostavkaga ham alohida to‘lov qilamanmi?</h2>
                      <img src="@/assets/images/svg/Vector (5).svg" alt="minus" />
                </div>
              </div>
              <div class="card-wrap">
                <div class="class__wrap-title" >
                      <h2>Buyurtmam necha kunda keladi?</h2>
                      <img src="@/assets/images/svg/Vector (5).svg" alt="minus" />
                </div>
              </div>
              <div class="card-wrap">
                <div class="class__wrap-title" >
                      <h2>Buyurtmam vaqtida kelmasa nima bo‘ladi?</h2>
                      <img src="@/assets/images/svg/Vector (5).svg" alt="minus" />
                </div>
              </div>
              <div class="card-wrap">
                <div class="class__wrap-title" >
                      <h2>Agar buyurtmam yoqmasa qaytarib bersam bo‘ladimi?</h2>
                      <img src="@/assets/images/svg/Vector (5).svg" alt="minus" />
                </div>
              </div>
              <div class="card-wrap">
                <div class="class__wrap-title" >
                      <h2>Dizaynga qildirish pullimi?</h2>
                      <img src="@/assets/images/svg/Vector (5).svg" alt="minus" />
                </div>
              </div>
              <div class="card-wrap">
                <div class="class__wrap-title" >
                      <h2>Qanday bonuslar mavjud?</h2>
                      <img src="@/assets/images/svg/Vector (5).svg" alt="minus" />
                </div>
              </div>
              <div class="card-wrap">
                <div class="class__wrap-title" >
                      <h2>Bo‘lib to‘lashga ham soat sotib olsam bo‘ladimi?</h2>
                      <img src="@/assets/images/svg/Vector (5).svg" alt="minus" />
                </div>
              </div>
            </div>
          </div> -->
      </div>
    </div>
    <div class="falsehood">
      <div class="container">
        <h4>Aloqa</h4>
        <div class="falsehood-wrap">
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
          <div class="falsehood-right">
            <iframe
              src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d24316.778372714223!2d71.794688!3d40.3734528!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x38bb849f74579c91%3A0x58a5f62abaf90bad!2z0JPQvtGB0YLQuNC90LjRhtCwINCQ0LfQuNGP!5e0!3m2!1sru!2s!4v1725530748351!5m2!1sru!2s"
              style="border: 0"
              allowfullscreen=""
              loading="lazy"
              referrerpolicy="no-referrer-when-downgrade"
            ></iframe>
          </div>
        </div>
      </div>
    </div>
    <div class="product-modal" :class="{ 'active-product': openBuy }">
      <div class="product__modal-text-wrapper">
        <h4>
          Mahsulot yetib borishi uchun ma’lumotlaringizni to‘g‘ri to‘ldiring
        </h4>
        <button @click="openBuy = false">
          <img src="@/assets/images/svg/сloseee.svg"  alt="close" />
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
                <!-- <USelect v-model="country" :options="countries" option-attribute="name" /> -->
                <!-- <input placeholder="Xabar kiriting...." type="text" /> -->
                <USelect class="new" v-model="country" :options="countries" />
                  
                 <!-- <button>
                  <div class="detail-list">

                  </div>
                 </button> -->
              </div>
              <button>Yuborish</button>
            </form>
          </div>
        </div>
      </div>
    </div>
    <!-- <ProductBuy v-show="openBuy" :openBuy="openBuy" /> -->
  </div>
</template>

<script setup>
import minusIcon from "@/assets/images/svg/minusIcon.svg";
import plusIcon from "@/assets/images/svg/Vector (6).svg";
const openBuy = ref(false);

const questions = ref([
  {
    title: "Soatlarni qanday buyurtma qilsam bo‘ ladi?",
    text: "O‘zingizga yoqqan soatni tanlab, shaxsiy maʼlumotlaringizni kiriting. Tez orada siz bilan bogʼlanamiz.",
  },
  {
    title: "Soat sotib olsam dostavkaga ham alohida to‘lov qilamanmi?",
    text: "Yetkazib berish narxi sizning joylashuvingizga bog‘liq.",
  },
  {
    title: "Buyurtmam necha kunda keladi?",
    text: "Buyurtma 2-5 kun ichida yetkazib beriladi.",
  },
  {
    title: "Buyurtmam vaqtida kelmasa nima bo‘ladi?",
    text: "Bizning mijozlar qo‘llab-quvvatlash xizmati bilan bog‘laning.",
  },
  {
    title: "Agar buyurtmam yoqmasa qaytarib bersam bo‘ladimi?",
    text: "Ha, qaytarish imkoniyati mavjud.",
  },
  {
    title: "Dizaynga qildirish pullimi?",
    text: "Yo‘q, dizayn bepul qilinadi.",
  },
  {
    title: "Qanday bonuslar mavjud?",
    text: "Har bir xaridda bonus tizimidan foydalanishingiz mumkin.",
  },
  {
    title: "Bo‘lib to‘lashga ham soat sotib olsam bo‘ladimi?",
    text: "Ha, bo‘lib to‘lash imkoniyati mavjud.",
  },
]);
const toggleQuestion = (index) => {
  openQuestionIndex.value = openQuestionIndex.value === index ? null : index;
};

const isQuestionOpen = (index) => {
  return openQuestionIndex.value === index;
};
const openQuestionIndex = ref(null);

const images = ref([
  "https://picsum.photos/200/300",
  "https://picsum.photos/seed/picsum/200/300",
  "https://picsum.photos/200/300?grayscale",
  "https://picsum.photos/200/300?grayscale",
]);

const selectedIndex = ref(0);

const selectedImage = ref(images.value[selectedIndex.value]);

const selectImage = (index) => {
  selectedIndex.value = index;
  selectedImage.value = images.value[index];
};

const countries = [
  "Farg`ona",
  "Navoiy",
  "Buxoro",
  "Qashqadaryo",
  "Surxondaryo",
  "Jizzax",
  "Samarqand",
  "Toshkent",
  "Namangan",
  "Xorazm",
  "Sirdaryo",
  "Andijon",
];

const country = ref(countries[0]);

const count = ref(1);

const increase = () => {
  if (count.value < 10) {
    count.value++;
  }
};

const decrease = () => {
  if (count.value > 0) {
    count.value--;
  }
};
</script>

<style lang="sass" scoped>
.main-block.active
  transform: scale(1.1)
  border: 2px solid #E59046
// .ring-gray-300
//   border: none
//   color: none
//   background: none
  
</style>
