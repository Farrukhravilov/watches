<template>
  <div>
    <div class="header">
      <div class="container">
        <div class="header-logo">
          <NuxtLink to="/" >
            <img src="@/assets/images/svg/logo.svg" alt="" />
          </NuxtLink>
        </div>
        <nav class="header-menu">
          <ul class="header-menu__list">
            <li class="header-menu__item">
              <a class="header-menu__link" href="#">Bosh sahifa</a>
            </li>
            <li class="header-menu__item">
              <a class="header-menu__link" href="#">Katalog</a>
            </li>
            <li class="header-menu__item">
              <a class="header-menu__link" href="#">Biz haqimizda</a>
            </li>
            <li class="header-menu__item">
              <a class="header-menu__link" href="#"
                >Ko’p beriladigan savollar</a
              >
            </li>
            <li class="header-menu__item">
              <a class="header-menu__link" href="#">Fikrlar</a>
            </li>
            <li class="header-menu__item">
              <a class="header-menu__link" href="#">Aloqa</a>
            </li>
          </ul>
        </nav>
        <div class="media-wrap">
          <div class="header-phone">
            <img src="@/assets/images/svg/Vector.svg" alt="" />
            <span>971351721</span>
          </div>
          <div class="header-media">
            <button @click="isMenuOpen = !isMenuOpen">
              <img src="@/assets/images/svg/menu.svg" alt="" />
            </button>
          </div>
        </div>
        <div class="header-socials">
          <div class="header-wrap">
            <svg
              width="22"
              height="19"
              viewBox="0 0 22 19"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M21.6832 0.273256C21.567 0.172913 21.4256 0.106179 21.2743 0.0802424C21.123 0.0543058 20.9674 0.0701501 20.8245 0.126068L1.82508 7.56138C1.55581 7.66608 1.32785 7.85543 1.1755 8.1009C1.02316 8.34638 0.954685 8.6347 0.980384 8.92246C1.00608 9.21022 1.12457 9.48184 1.31799 9.69644C1.51142 9.91103 1.76933 10.057 2.05289 10.1123L6.9757 11.0789V16.5679C6.97473 16.8669 7.06358 17.1593 7.23074 17.4072C7.3979 17.6551 7.63565 17.8471 7.9132 17.9583C8.19032 18.0714 8.49507 18.0986 8.78783 18.0362C9.0806 17.9739 9.34782 17.8248 9.55476 17.6086L11.9285 15.1467L15.6945 18.4429C15.9662 18.6839 16.3166 18.8173 16.6798 18.8179C16.8389 18.8178 16.9971 18.7928 17.1485 18.7439C17.396 18.6654 17.6185 18.5234 17.794 18.3321C17.9695 18.1408 18.0919 17.9069 18.1488 17.6536L21.9541 1.09919C21.9882 0.949896 21.9809 0.79415 21.9332 0.64865C21.8855 0.50315 21.7991 0.373382 21.6832 0.273256ZM15.9513 3.64826L7.55226 9.66326L2.90226 8.75107L15.9513 3.64826ZM8.4757 16.5679V12.1167L10.7998 14.1548L8.4757 16.5679ZM16.6816 17.3179L8.93039 10.5211L20.0866 2.52513L16.6816 17.3179Z"
                fill="#B0B3B9"
              />
            </svg>
          </div>
          <div class="header-wrap">
            <svg
              width="25"
              height="24"
              viewBox="0 0 25 24"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M9.72217 22H15.7222C20.7222 22 22.7222 20 22.7222 15V9C22.7222 4 20.7222 2 15.7222 2H9.72217C4.72217 2 2.72217 4 2.72217 9V15C2.72217 20 4.72217 22 9.72217 22Z"
                stroke="#B0B3B9"
                stroke-width="1.5"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
              <path
                d="M12.7222 15.5C14.6552 15.5 16.2222 13.933 16.2222 12C16.2222 10.067 14.6552 8.5 12.7222 8.5C10.7892 8.5 9.22217 10.067 9.22217 12C9.22217 13.933 10.7892 15.5 12.7222 15.5Z"
                stroke="#B0B3B9"
                stroke-width="1.5"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
              <path
                d="M18.3583 7H18.3698"
                stroke="#B0B3B9"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
            </svg>
          </div>
          <div class="header-wrap">
            <svg
              width="25"
              height="24"
              viewBox="0 0 25 24"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M17.4443 20H7.44434C4.44434 20 2.44434 18 2.44434 15V9C2.44434 6 4.44434 4 7.44434 4H17.4443C20.4443 4 22.4443 6 22.4443 9V15C22.4443 18 20.4443 20 17.4443 20Z"
                stroke="#B0B3B9"
                stroke-width="1.5"
                stroke-miterlimit="10"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
              <path
                d="M11.8444 9.5L14.3444 11C15.2444 11.6 15.2444 12.5 14.3444 13.1L11.8444 14.6C10.8444 15.2 10.0444 14.7 10.0444 13.6V10.6C10.0444 9.3 10.8444 8.9 11.8444 9.5Z"
                stroke="#B0B3B9"
                stroke-width="1.5"
                stroke-miterlimit="10"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
            </svg>
          </div>
        </div>
      </div>
    </div>
    <!--  -->
    <NuxtPage />
    <div class="menu" :class="{'active-menu': isMenuOpen}">
      <div class="menu-header">
        <div class="menu__header-btn" @click="isMenuOpen = false">
          <button>
            <img src="@/assets/images/svg/arrow-left.svg" alt="xz" />
          </button>
        </div>
        <NuxtLink to="/" class="header-logo">
          <img src="@/assets/images/svg/logo.svg" alt="" />
        </NuxtLink>
      </div>
      <div class="menu-main">
        <ul>
          <li><a href="" id="menu__main-one">Bosh sahifa</a></li>
          <li><a href="">Katalog</a></li>
          <li><a href="">Biz haqimizda</a></li>
          <li><a href="">Ko’p beriladigan savollar</a></li>
          <li><a href="">Fikrlar</a></li>
          <li><a href="">Aloqa</a></li>
        </ul>
        <div class="menu__main-footer">
          <button class="watches__more-delivery">Buyurtma berish</button>
        </div>
      </div>
      <div class="menu-footer">
        <div class="header-socials">
          <div class="header__socials-wrapper">
            <svg
              width="22"
              height="19"
              viewBox="0 0 22 19"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M21.6832 0.273256C21.567 0.172913 21.4256 0.106179 21.2743 0.0802424C21.123 0.0543058 20.9674 0.0701501 20.8245 0.126068L1.82508 7.56138C1.55581 7.66608 1.32785 7.85543 1.1755 8.1009C1.02316 8.34638 0.954685 8.6347 0.980384 8.92246C1.00608 9.21022 1.12457 9.48184 1.31799 9.69644C1.51142 9.91103 1.76933 10.057 2.05289 10.1123L6.9757 11.0789V16.5679C6.97473 16.8669 7.06358 17.1593 7.23074 17.4072C7.3979 17.6551 7.63565 17.8471 7.9132 17.9583C8.19032 18.0714 8.49507 18.0986 8.78783 18.0362C9.0806 17.9739 9.34782 17.8248 9.55476 17.6086L11.9285 15.1467L15.6945 18.4429C15.9662 18.6839 16.3166 18.8173 16.6798 18.8179C16.8389 18.8178 16.9971 18.7928 17.1485 18.7439C17.396 18.6654 17.6185 18.5234 17.794 18.3321C17.9695 18.1408 18.0919 17.9069 18.1488 17.6536L21.9541 1.09919C21.9882 0.949896 21.9809 0.79415 21.9332 0.64865C21.8855 0.50315 21.7991 0.373382 21.6832 0.273256ZM15.9513 3.64826L7.55226 9.66326L2.90226 8.75107L15.9513 3.64826ZM8.4757 16.5679V12.1167L10.7998 14.1548L8.4757 16.5679ZM16.6816 17.3179L8.93039 10.5211L20.0866 2.52513L16.6816 17.3179Z"
                fill="#B0B3B9"
              />
            </svg>
          </div>
          <div class="header__socials-wrapper">
            <img src="@/assets/images/svg/youtube.svg" alt="youtube" />
          </div>
          <div class="header__socials-wrapper">
            <img src="@/assets/images/svg/instagram.svg" alt="insta" />
          </div>
        </div>
      </div>
    </div>
    <div class="footer">
      <div class="container">
        <div class="footer-top">
          <div class="header-logo">
            <img src="@/assets/images/svg/logo.svg" alt="" />
          </div>
          <nav class="header-menu">
            <ul class="header-menu__list">
              <li class="header-menu__item">
                <a class="header-menu__link" href="#">Bosh sahifa</a>
              </li>
              <li class="header-menu__item">
                <a class="header-menu__link" href="#">Katalog</a>
              </li>
              <li class="header-menu__item">
                <a class="header-menu__link" href="#">Biz haqimizda</a>
              </li>
              <li class="header-menu__item">
                <a class="header-menu__link" href="#"
                  >Ko’p beriladigan savollar</a
                >
              </li>
              <li class="header-menu__item">
                <a class="header-menu__link" href="#">Fikrlar</a>
              </li>
              <li class="header-menu__item">
                <a class="header-menu__link" href="#">Aloqa</a>
              </li>
            </ul>
          </nav>
          <div class="header-phone">
            <img src="@/assets/images/svg/Vector.svg" alt="" />
            <span>971351721</span>
          </div>
          <div class="header-socials">
            <div class="header-wrap">
              <img src="@/assets/images/svg/Vector (4).svg" alt="" />
            </div>
            <div class="header-wrap">
              <img src="@/assets/images/svg/instagram.svg" alt="" />
            </div>
            <div class="header-wrap">
              <img src="@/assets/images/svg/youtube.svg" alt="" />
            </div>
          </div>
        </div>
      </div>
      <div class="footer-bottom">
        <p>
          Copyright Fargenius Software Group © 2023-2024. All Rights Reserved.
        </p>
      </div>
    </div>
    <!-- <menu /> -->
  </div>
</template>

<script setup>
const isMenuOpen = ref(false) 

</script>

<style lang="scss" scoped></style>
