<template>
  <div>
    <div class="hero">
      <div class="container">
        <div class="hero__text-btn-wrap">
          <h1 class="hero__title">EUTOUR E030</h1>
          <h3 class="hero__desc">Erkaklar uchun Magnit Sport soatlari</h3>
          <div class="hero__price-wrap">
            <h2 class="hero__price">600 uzs</h2>
            <h2 class="hero__pricee">150 uzs / oyiga</h2>
          </div>

          <div class="hero__btn-wrap">
            <button class="hero__btn">Batafsil</button>
            <button class="hero__btnn">Buyurtma berish</button>
          </div>
        </div>

        <div class="hero__img-wrap">
          <img
            class="hero__img-3"
            src="@/assets/images/png/watchesOne.png"
            alt=""
          />
          <img
            class="hero__img"
            src="@/assets/images/png/watchesTwo.png"
            alt=""
          />
          <img
            class="hero__img-2"
            src="@/assets/images/png/watchesSry.png"
            alt=""
          />
        </div>
      </div>
    </div>
    <!-- <div class="watches">
      <div class="container">
        <div class="watches-wrap">
          <div class="watches-left">
            <h4>EUTOUR E030</h4>
            <p>Erkaklar uchun Magnit Sport soatlari</p>
            <div class="watches__left-price">
              <span>600 uzs</span>
              <div class="watches__left-uzs">
                <span>150 uzs / oyiga</span>
              </div>
            </div>
            <div class="watches__more">
              <button class="watches__more-all">Batafsil</button>
              <button class="watches__more-delivery">Buyurtma berish</button>
            </div>
          </div>
          <div class="watches-right">
            <img id="one" class="perviy" src="@/assets/images/png/watchesOne.png" />
            <img id="ty" src="@/assets/images/png/watchesTwo.png" />
            <img id="sry" src="@/assets/images/png/watchesSry.png" />
          </div>
        </div>
      </div>
    </div> -->

    <div class="products">
      <div class="container">
        <h4>Mahsulotlarimiz</h4>

        <NuxtLink to="/page/detail" class="products-wrapper">
          <div class="product-card" id="card-one">
            <div class="product__card-wrapper">
              <div class="card-image">
                <img src="@/assets/images/png/black.png" alt="watch" />
              </div>

              <h6>EUTOUR E030</h6>
              <div class="watches__left-price">
                <span>600 uzs</span>
                <div class="watches__left-uzs">
                  <span>150 uzs / oyiga</span>
                </div>
              </div>
            </div>
          </div>
          <div class="product-card">
            <div class="product__card-wrapper">
              <div class="card-image">
                <img src="@/assets/images/png/black.png" alt="watch" />
              </div>
              <h6>EUTOUR E030</h6>
              <div class="watches__left-price">
                <span>600 uzs</span>
                <div class="watches__left-uzs">
                  <span>150 uzs / oyiga</span>
                </div>
              </div>
            </div>
          </div>
          <div class="product-card">
            <div class="product__card-wrapper">
              <div class="card-image">
                <img src="@/assets/images/png/black.png" alt="watch" />
              </div>
              <h6>EUTOUR E030</h6>
              <div class="watches__left-price">
                <span>600 uzs</span>
                <div class="watches__left-uzs">
                  <span>150 uzs / oyiga</span>
                </div>
              </div>
            </div>
          </div>
        </NuxtLink>

        <div class="services">
          <h5>Xizmatlarimiz</h5>
          <p>
            Bizdan soat xarid qilganingizda, qoʻshimchasiga o‘z logotipingizni
            tushurishingiz yoki ismingizni yozdirsangiz boʻladi.
          </p>
          <div class="global-services">
            <ClientOnly>
              <VueCompareImage :left-image="cat1" :right-image="cat2" />
            </ClientOnly>
            <!-- <img src="@/assets/images/png/image.png" alt="watch" /> -->
            <!--  -->
          </div>
        </div>

        <div class="info-forme">
          <h4>Biz haqimizda</h4>
          <div class="info__forme-wrap">
            <div class="info__wrap-left">
              <img src="@/assets/images/png/seting.png" alt="seting" />
            </div>
            <div class="info__wrap-right">
              <div class="info__right-subtitle">
                <p>
                  “Watch Tailor”ga xush kelibsiz! Bizning soatlarimiz nafaqat
                  vaqtni ko‘rsatadi, balki sizning unutilmas onlaringizda ham
                  hamrohlik qiladi.
                </p>
                <p>
                  Bizning maqsadimiz — har bir mijozimizning ehtiyojlariga mos,
                  individual soat dizaynlarini yaratish. Bu O‘zbekistonda noyob
                  taklif bo‘lib, faqat bizda soatingizni o‘zingiz uchun
                  individual dizaynda qildira olasiz. Har bir soat o‘ziga xos
                  bo‘lib, sizning imidjingizga yangicha koʻrinish qo‘shadi.
                </p>
                <p>
                  Watch Tailor — yangi va o‘ziga xos soatlar dizayni bilan
                  mashhur bo‘lgan brend. Biz “EUTOUR” brendidan ilhomlanib,
                  mijozlar uchun soatlar yaratamiz. Farqimiz shundaki,
                  “EUTOUR”da siz uchun maxsus dizayn xizmatlari yo‘q, ammo bizda
                  individual tarzda soatingizni ismingiz yoki logotipingiz bilan
                  shaxsiylashtirish imkoniyatiga ega boʻlasiz.
                </p>
              </div>
            </div>
          </div>

          <div class="raiting">
            <div class="raiting-card">
              <h5>8+</h5>
              <span>Tajriba biznesda</span>
            </div>
            <div class="raiting-card">
              <h5>200+</h5>
              <span>Mijozlar</span>
            </div>
            <div class="raiting-card">
              <h5>8+</h5>
              <span>Loyihalar</span>
            </div>
            <div class="raiting-card">
              <h5>100%</h5>
              <span>Mijozlar roziligi</span>
            </div>
          </div>

          <div class="choose">
            <h5>Nima uchun bizni tanlashingiz kerak?</h5>
            <div class="choose-wrap" id="chose">
              <div class="choose__wrap-card">
                <img src="@/assets/images/svg/Login.svg" alt="login" />
                <h6>Individual</h6>
                <p>
                  Xarid qilgan soatingizga ism yoki logotipingizni tushirib
                  beramiz.
                </p>
              </div>
              <div class="choose__wrap-card">
                <img src="@/assets/images/svg/dostavka.svg" alt="login" />
                <h6>Yetkazish</h6>
                <p>
                  Xarid qilgan soatingizga ism yoki logotipingizni tushirib
                  beramiz.
                </p>
              </div>
              <div class="choose__wrap-card">
                <img src="@/assets/images/svg/kafollat.svg" alt="login" />
                <h6>Kafolat</h6>
                <p>
                  Soatlarimiz va uning detallari sifatiga 6 oygacha kafolat
                  beriladi.
                </p>
              </div>
              <div class="choose__wrap-card">
                <img src="@/assets/images/svg/tot.svg" alt="login" />
                <h6>Imtiyoz</h6>
                <p>
                  Belgilangan muddatda yetkazilmasa, 50% gacha chegirmaga ega
                  boʻlasiz.
                </p>
              </div>
              <div class="choose__wrap-card">
                <img src="@/assets/images/svg/ppp.svg" alt="login" />
                <h6>Halol nasiya</h6>
                <p>
                  Bizdan soatlarni halol boʻlib toʻlashga olishingiz mumkin.
                </p>
              </div>
              <div class="choose__wrap-card">
                <img src="@/assets/images/svg/net.svg" alt="login" />
                <h6>Bonuslar</h6>
                <p>
                  Do ‘stingiz haridi uchun sizga 10% dan chegirmalar taqdim
                  qilamiz.
                </p>
              </div>
              <div class="choose__wrap-card">
                <img src="@/assets/images/svg/prosto.svg" alt="login" />
                <h6>Dizayn</h6>
                <p>
                  Xarid qilgan soatingizga ism yoki logotipingizni tushirib
                  beramiz.
                </p>
              </div>
              <div class="choose__wrap-card">
                <img src="@/assets/images/svg/message.svg" alt="login" />
                <h6>Konsultatsiya</h6>
                <p>
                  Xarid qilgan soatingizga ism yoki logotipingizni tushirib
                  beramiz.
                </p>
              </div>
            </div>
            <div class="choose-btn">
              <button>Buyurtma berish</button>
            </div>
          </div>

          <div class="comment">
            <h3>Mijozlar fikri</h3>
            <div class="comment-wrapper">
              <div class="comment__wrapper-card">
                <div class="comment__card-top">
                  <img src="@/assets/images/svg/tak.svg " alt="prosto" />
                  <p>EUTOUR E030</p>
                </div>
                <div class="comment__card-main">
                  <p>
                    Nasiya savdo orqali soat xarid qildim, juda qulay, yetkazib
                    berish ham tekin ekan.
                  </p>
                </div>
                <div class="comment__card-footer">
                  <img src="@/assets/images/svg/krugliy.svg" alt="bbb" />
                  <span>Aziz</span>
                </div>
              </div>
              <div class="comment__wrapper-card">
                <div class="comment__card-top">
                  <img src="@/assets/images/svg/tak.svg " alt="prosto" />
                  <p>EUTOUR E030</p>
                </div>
                <div class="comment__card-main">
                  <p>
                    Soatlarning individual dizayni haqiqatan ham o‘ziga xos
                    boʻlib, sifati ham aʼlo ekan
                  </p>
                </div>
                <div class="comment__card-footer">
                  <img src="@/assets/images/svg/krugliy.svg" alt="bbb" />
                  <span>Temur</span>
                </div>
              </div>
              <div class="comment__wrapper-card">
                <div class="comment__card-top">
                  <img src="@/assets/images/svg/tak.svg " alt="prosto" />
                  <p>EUTOUR E030</p>
                </div>
                <div class="comment__card-main">
                  <p>
                    Nasiya savdo orqali soat xarid qildim, juda qulay, yetkazib
                    berish ham tekin ekan.
                  </p>
                </div>
                <div class="comment__card-footer">
                  <img src="@/assets/images/svg/krugliy.svg" alt="bbb" />
                  <span>Olim</span>
                </div>
              </div>
              <div class="comment__wrapper-card">
                <div class="comment__card-top">
                  <img src="@/assets/images/svg/tak.svg " alt="prosto" />
                  <p>EUTOUR E030</p>
                </div>
                <div class="comment__card-main">
                  <p>
                    Nasiya savdo orqali soat xarid qildim, juda qulay, yetkazib
                    berish ham tekin ekan.
                  </p>
                </div>
                <div class="comment__card-footer">
                  <img src="@/assets/images/svg/krugliy.svg" alt="bbb" />
                  <span>Aziz</span>
                </div>
              </div>
              <div class="comment__wrapper-card">
                <div class="comment__card-top">
                  <img src="@/assets/images/svg/tak.svg " alt="prosto" />
                  <p>EUTOUR E030</p>
                </div>
                <div class="comment__card-main">
                  <p>
                    Nasiya savdo orqali soat xarid qildim, juda qulay, yetkazib
                    berish ham tekin ekan.
                  </p>
                </div>
                <div class="comment__card-footer">
                  <img src="@/assets/images/svg/krugliy.svg" alt="bbb" />
                  <span>Aziz</span>
                </div>
              </div>
            </div>
          </div>

          <div class="now">
            <div class="now-wrapper">
              <div class="now__wrapper-left">
                <img src="@/assets/images/svg/25.png" alt="now" />
              </div>
              <div class="now__wrapper-right">
                <div class="now__right-subtitle">
                  <p>
                    Hoziroq o‘z stilingizni yarating va qolganlardan ajralib
                    turing!
                  </p>
                  <button>Buyurtma berish</button>
                </div>
              </div>
            </div>
          </div>
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
            <h4>EUTOUR Magnetic Eng yaxshi yog'och soatlar E031</h4>
            <h6>Buyurtmangiz 2-9-sentyabrgacha yetkaziladi</h6>
            <div class="main-right-wrap">
              <div class="right-title">
                <h5 class="right-price" >600 000</h5>
                <span class="right-uzsd" >uzs</span>
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
            <div class="main-box">
              <div class="main-block"></div>
              <div class="main-blockk"></div>
              <div class="main-blockk"></div>
              <div class="main-blockk"></div>
            </div>
            <div class="main-info">
              <button class="info-btnn" >Batafsil ma’limot olish</button>
              <button class="info-btn" >Buyurtmani rasmiylashtirish</button>
            </div>
          </div>
        </div>
        <div class="main-characters">
          <div class="characters-left">
            <h1>Xarakteristikasi</h1>
            <ul>
              <li>Model raqami<NuxtLink to="/" class="character-name" >E031A-M1</NuxtLink></li>
              <li>Rangi<NuxtLink to="/" class="character-name" >Qora</NuxtLink></li>
              <li>Harakat<NuxtLink to="/" class="character-name" >RONDA Quartz-M1</NuxtLink></li>
              <li>Batareya<NuxtLink to="/" class="character-name"  >920 tugmali hujayra (45 oy)</NuxtLink></li>
              <li>Suvga chidamliligi<NuxtLink to="/" class="character-name"  >3ATM</NuxtLink></li>
              <li>Koson materiali:<NuxtLink to="/" class="character-name"  >mis (PVD)</NuxtLink></li>
              <li>Dial<NuxtLink to="/" class="character-name"  >Tabiiy yog'och </NuxtLink> </li>
              <li>Band materiali<NuxtLink to="/" class="character-name"  >Tabiiy yog'och</NuxtLink></li>
              <li>Koson diametri<NuxtLink to="/" class="character-name"  >40mm</NuxtLink></li>
              <li>Band uzunligi<NuxtLink to="/" class="character-name"  >Moslashuvchan </NuxtLink> </li>
            </ul>
          </div>
          <div class="characters-right">
            <h1>Ta’rifi</h1>
            <span>Tabiiy yog'och material</span>
            <p>58% mis qotishmasidan va tabiiy qizil sandal daraxtidan tayyorlangan har bir magnitli yog'och soat qo'lda ehtiyotkorlik bilan ishlangan. Ushbu soatlarning har bir detalidan ularning ter va donoligini his qilishingiz mumkin. Ularning barchasi toksik bo'lmagan va hipoalerjenikdir.
            </p>
            <span>Tabiiy yog'och material   Og'ir yuk komponentlari </span>
            <p>Shveytsariyalik RONDA kvarts harakati bilan jihozlangan bu yog'och soatlar bardoshli va har bir harakatingiz uchun aniq vaqtni ushlab turishi mumkin. Batareyaning ishlash muddati 45 oygacha.
            </p>
            <span>Moslashtirilgan yog'och soat tasmasi </span>
            <p>Yog'ochdan yasalgan magnit soatlar yog'ochning tabiiy go'zalligini saqlaydigan, bo'yoq va kimyoviy moddalarsiz, nafis ishlangan EUTOUR yog'och bantlari bilan birga keladi. Har bir guruh noyob bo'lib, nafislik va estetikani taqdim etadi. O'lchamlarni sozlash uchun professional vositalar taqdim etiladi, bu esa soat bandini oson sozlash imkonini beradi.
            </p>
            <span>3ATM suv o'tkazmaydigan jism </span>
            <p>30 metrgacha (3ATM) suvga chidamliligi bilan bu soatlar ter, yomg'ir yoki suvning chayqalishiga bardosh bera oladi. Biroq, ular suzish, dush olish, sho'ng'in qilish yoki snorkeling uchun mos emas.
            </p>
          </div>
        </div>
      </div>
    </div> -->

    <!-- <div class="speed-questions">
    <div class="container">
      <h1 class="questions-title">Tez-tez berildigan savollar</h1>
      <div class="question-wrap">
        <div v-for="(question, index) in questions" :key="index" class="question-card">
          <div class="card-wrap">
            <div class="class__wrap-title" @click="toggleAnswer(index)">
              <h2>{{ question.title }}</h2>
              <img
                :src="isActive(index) ? '@/assets/images/svg/Minuss.svg' : '@/assets/images/svg/plus.svg'"
                alt="toggle"
              />
            </div>
            <p v-if="isActive(index)">{{ question.answer }}</p>
          </div>
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
  </div>
</template>

<script setup>
  import { VueCompareImage } from 'vue3-compare-image' 
  import minusIcon from '@/assets/images/svg/minusIcon.svg';
  import plusIcon from '@/assets/images/svg/Vector (6).svg'; 


  import cat1 from '@/assets/images/png/old_1.png'
  import cat2 from '@/assets/images/png/new_1.png'

const activeIndex = ref(null);



  const questions = ref([
  { title: 'Soatlarni qanday buyurtma qilsam bo‘ ladi?', text: 'O‘zingizga yoqqan soatni tanlab, shaxsiy maʼlumotlaringizni kiriting. Tez orada siz bilan bogʼlanamiz.' },
  { title: 'Soat sotib olsam dostavkaga ham alohida to‘lov qilamanmi?', text: 'Yetkazib berish narxi sizning joylashuvingizga bog‘liq.' },
  { title: 'Buyurtmam necha kunda keladi?', text: 'Buyurtma 2-5 kun ichida yetkazib beriladi.' },
  { title: 'Buyurtmam vaqtida kelmasa nima bo‘ladi?', text: 'Bizning mijozlar qo‘llab-quvvatlash xizmati bilan bog‘laning.' },
  { title: 'Agar buyurtmam yoqmasa qaytarib bersam bo‘ladimi?', text: 'Ha, qaytarish imkoniyati mavjud.' },
  { title: 'Dizaynga qildirish pullimi?', text: 'Yo‘q, dizayn bepul qilinadi.' },
  { title: 'Qanday bonuslar mavjud?', text: 'Har bir xaridda bonus tizimidan foydalanishingiz mumkin.' },
  { title: 'Bo‘lib to‘lashga ham soat sotib olsam bo‘ladimi?', text: 'Ha, bo‘lib to‘lash imkoniyati mavjud.' },
]);
const toggleQuestion = (index) => {
  openQuestionIndex.value = openQuestionIndex.value === index ? null : index;
};

const isQuestionOpen = (index) => {
  return openQuestionIndex.value === index;
};
const openQuestionIndex = ref(null);

</script>

<style lang="scss" scoped></style>
