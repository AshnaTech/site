<script setup>
import $ from 'jquery'

const fullPageOptions = {
  navigation: true,
  anchors: ['home', 'about', 'skills', 'projects', 'contact'],
  menu: '#right-container',
  scrollingSpeed: 1000,
  scrollOverflow: false
}

</script>

<template>
  <!-- <div class="absolute w-screen z-10">
    <div class="blob"></div>
  </div> -->
  <div id="main-container" class="rounded-lg flex overflow-hidden glass z-20">
    <div id="left-container" class="h-full">
      <div id="app">
        <full-page :options="fullPageOptions">
          <div class="section" data-fp-styles="null" data-anchor="home">
            <div class="flex dir-rtl justify-between px-36 -mt-10 h-screen">
              <div id="home-right" class="w-1/3 h-100 flex align-center items-center text-center text-gray-200">
                <div class="h-100 flex flex-col text-right text-justify gap-3 animated animated-top">
                  <h1 class="text-5xl animated animated-top">گروه برنامه نویسی <span class="text-red-500">آشنا</span></h1>
                  <h3 class="animated animated-top">طراحی و توسعه سایت شخصی، فروشگاهی و استارتاپی با جدیدترین ابزارهای
                    دنیا
                    و به صورت حرفه ای، طراحی لوگو
                    و موشن گرافیک به صورت حرفه ای، تبلیغات و توسعه برند</h3>

                </div>
              </div>
              <div id="home-left" class="w-1/3 h-100 flex align-center items-center text-center text-gray-200">
                <svg id="desk" class="animated animated-left" width="64" height="64" viewBox="0 0 64 64" fill="none"
                  xmlns="http://www.w3.org/2000/svg">
                  <g id="study">
                    <rect width="64" height="64" />
                    <g id="smoke">
                      <path id="smoke-2"
                        d="M9 21L9.55279 19.8944C9.83431 19.3314 9.83431 18.6686 9.55279 18.1056L9 17L8.44721 15.8944C8.16569 15.3314 8.16569 14.6686 8.44721 14.1056L9 13"
                        stroke="#797270" />
                      <path id="smoke-1"
                        d="M6.5 22L7.05279 20.8944C7.33431 20.3314 7.33431 19.6686 7.05279 19.1056L6.5 18L5.94721 16.8944C5.66569 16.3314 5.66569 15.6686 5.94721 15.1056L6.5 14"
                        stroke="#797270" />
                    </g>
                    <g id="laptop">
                      <rect id="laptop-base" x="17" y="28" width="20" height="3" fill="#F3F3F3" stroke="#453F3C"
                        stroke-width="2" />
                      <rect id="laptop-screen" x="18" y="17" width="18" height="11" fill="#5A524E" stroke="#453F3C"
                        stroke-width="2" />
                      <rect id="line-1" x="20" y="19" width="14" height="1" fill="#F78764" />
                      <rect id="line-2" x="20" y="21" width="14" height="1" fill="#F9AB82" />
                      <rect id="line-3" x="20" y="23" width="14" height="1" fill="#F78764" />
                      <rect id="line-4" x="20" y="25" width="14" height="1" fill="#F9AB82" />
                    </g>
                    <g id="cup">
                      <rect id="Rectangle 978" x="5" y="24" width="5" height="7" fill="#CCC4C4" stroke="#453F3C"
                        stroke-width="2" />
                      <path id="Ellipse 416" d="M11 28C12.1046 28 13 27.1046 13 26C13 24.8954 12.1046 24 11 24"
                        stroke="#453F3C" stroke-width="2" />
                      <rect id="Rectangle 996" x="6" y="25" width="3" height="1" fill="#D6D2D1" />
                    </g>
                    <g id="books">
                      <rect id="Rectangle 984" x="58" y="27" width="4" height="14" transform="rotate(90 58 27)"
                        fill="#B16B4F" stroke="#453F3C" stroke-width="2" />
                      <rect id="Rectangle 985" x="56" y="23" width="4" height="14" transform="rotate(90 56 23)"
                        fill="#797270" stroke="#453F3C" stroke-width="2" />
                      <rect id="Rectangle 986" x="60" y="19" width="4" height="14" transform="rotate(90 60 19)"
                        fill="#F78764" stroke="#453F3C" stroke-width="2" />
                      <rect id="Rectangle 993" x="47" y="20" width="12" height="1" fill="#F9AB82" />
                      <rect id="Rectangle 994" x="43" y="24" width="12" height="1" fill="#54504E" />
                      <rect id="Rectangle 995" x="45" y="28" width="12" height="1" fill="#804D39" />
                    </g>
                    <g id="desk">
                      <rect id="Rectangle 973" x="4" y="31" width="56" height="5" fill="#797270" stroke="#453F3C"
                        stroke-width="2" />
                      <rect id="Rectangle 987" x="10" y="36" width="30" height="6" fill="#797270" stroke="#453F3C"
                        stroke-width="2" />
                      <rect id="Rectangle 975" x="6" y="36" width="4" height="24" fill="#797270" stroke="#453F3C"
                        stroke-width="2" />
                      <rect id="Rectangle 974" x="40" y="36" width="18" height="24" fill="#797270" stroke="#453F3C"
                        stroke-width="2" />
                      <line id="Line 129" x1="40" y1="48" x2="58" y2="48" stroke="#453F3C" stroke-width="2" />
                      <line id="Line 130" x1="22" y1="39" x2="28" y2="39" stroke="#453F3C" stroke-width="2" />
                      <line id="Line 142" x1="46" y1="42" x2="52" y2="42" stroke="#453F3C" stroke-width="2" />
                      <line id="Line 131" x1="46" y1="54" x2="52" y2="54" stroke="#453F3C" stroke-width="2" />
                      <rect id="Rectangle 988" x="11" y="37" width="28" height="1" fill="#54504E" />
                      <rect id="Rectangle 992" x="5" y="32" width="54" height="1" fill="#9E9492" />
                      <rect id="Rectangle 989" x="7" y="37" width="2" height="1" fill="#54504E" />
                      <rect id="Rectangle 990" x="41" y="37" width="16" height="1" fill="#54504E" />
                      <rect id="Rectangle 991" x="41" y="49" width="16" height="1" fill="#54504E" />
                      <line id="Line 143" y1="60" x2="64" y2="60" stroke="#453F3C" stroke-width="2" />
                    </g>
                  </g>
                </svg>
              </div>

              <div class="decor-home-shape">
                <img src="../assets/media/images/background/decorative-2.png" alt="">
              </div>

              <div class="side-dots">
                <img class="dots_decor" src="../assets/media/images/background/side-dots.png" alt="">
              </div>

              <div class="home-hero">
                <svg width="903" height="887" viewBox="0 0 903 887" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path d="M47.2262 320.433L114.319 320.792L118.976 335.892L52.0914 336.238L47.2262 320.433Z"
                    fill="#F4A949"></path>
                  <path d="M134.246 320.858L201.343 321.227L205.994 336.318L139.104 336.663L134.246 320.858Z"
                    fill="#1C5F9A"></path>
                  <path d="M97.3566 353.899L164.437 354.261L169.088 369.365L102.209 369.702L97.3566 353.899Z"
                    fill="#1C5F9A"></path>
                  <path d="M221.413 321.768L485.765 322.185L490.419 337.284L226.28 337.562L221.413 321.768Z"
                    fill="#1C5F9A">
                  </path>
                  <path d="M202.902 354.015L638.794 357.201L643.448 372.291L207.775 369.82L202.902 354.015Z"
                    fill="#9C27B0">
                  </path>
                  <path d="M478.267 521.382L894.745 524.805L899.401 539.9L483.124 537.176L478.267 521.382Z"
                    fill="#1C5F9A">
                  </path>
                  <path d="M177.996 354.168L194.845 354.651L199.501 369.748L182.857 369.972L177.996 354.168Z"
                    fill="#F4A949"></path>
                  <path d="M358.89 389.3L424.034 390.501L428.68 405.6L363.757 405.092L358.89 389.3Z" fill="#F4A949">
                  </path>
                  <path d="M299.752 487.208L316.603 487.687L321.258 502.79L304.619 503.005L299.752 487.208Z"
                    fill="#F4A949">
                  </path>
                  <path d="M326.155 486.923L343.001 487.404L347.649 502.497L331.026 502.73L326.155 486.923Z"
                    fill="#F4A949">
                  </path>
                  <path d="M107.698 387.455L222.122 388.706L226.773 403.81L112.567 403.258L107.698 387.455Z"
                    fill="#1C5F9A">
                  </path>
                  <path d="M335.415 421.264L449.857 422.522L454.508 437.619L340.288 437.071L335.415 421.264Z"
                    fill="#1C5F9A"></path>
                  <path d="M175.659 487.91L290.087 489.164L294.747 504.27L180.515 503.712L175.659 487.91Z" fill="#1C5F9A">
                  </path>
                  <path d="M342.326 520.75L456.777 521.989L461.425 537.08L347.2 536.54L342.326 520.75Z" fill="#1C5F9A">
                  </path>
                  <path d="M208.827 454.265L424.046 456.49L428.701 471.576L213.681 470.068L208.827 454.265Z"
                    fill="#1C5F9A">
                  </path>
                  <path d="M236.887 388.975L351.317 390.227L355.967 405.323L241.747 404.773L236.887 388.975Z"
                    fill="#1C5F9A"></path>
                  <path d="M78.2267 421.127L145.324 421.484L149.974 436.587L83.0959 436.92L78.2267 421.127Z"
                    fill="#F4A949">
                  </path>
                  <path d="M156.512 420.877L317.531 421.363L322.181 436.463L161.364 436.688L156.512 420.877Z"
                    fill="#9C27B0"></path>
                  <path d="M433.682 456.113L745.839 455.683L750.486 470.793L438.556 471.918L433.682 456.113Z"
                    fill="#9C27B0"></path>
                  <path d="M131.938 454.719L199.041 455.071L203.696 470.177L136.815 470.523L131.938 454.719Z"
                    fill="#F4A949"></path>
                  <path d="M117.207 488.433L165.999 488.62L170.638 503.714L122.08 504.239L117.207 488.433Z"
                    fill="#9C27B0">
                  </path>
                  <path d="M275.51 520.95L324.298 521.124L328.953 536.228L280.376 536.745L275.51 520.95Z" fill="#9C27B0">
                  </path>
                  <path d="M109.231 521.806L254.295 520.887L258.947 535.998L114.098 537.606L109.231 521.806Z"
                    fill="#1C5F9A"></path>
                </svg>
              </div>
            </div>
          </div>
          <div class="section" data-fp-styles="null" data-anchor="about">
            <div>
              <div>

              </div>
              
            </div>
          </div>
          <div class="section" data-fp-styles="null" data-anchor="skills">
            <h1>Skills</h1>
          </div>

          <div class="section" data-fp-styles="null" data-anchor="projects">
            <h1>Projects</h1>
          </div>

          <div class="section" data-fp-styles="null" data-anchor="contact">
            <h1>Contact</h1>
          </div>
        </full-page>
      </div>
    </div>


    <div id="right-container" class="h-full flex justify-center items-center align-center navigation-glass">

      <div id="logo-right-container" class="absolute top-0 flex flex-col gap-3">
        <img id="" class="p-2 w-16" src="../assets/media/images/logo/Logo.png">
        <h2 class="dir-rtl -rotate-90 whitespace-nowrap text-red-700 text-sm">گروه برنامه نویسی آشنا</h2>
      </div>

      <nav id="navigation-bar" class="w-full">

        <ul class="flex flex-col aligns-center justify-center items-center p-2">

          <li class="nav-button active" data-menuanchor="home">
            <a id="home-button" href="#home" title="home">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 48 48">
                <path
                  d="M39.5,43h-9c-1.381,0-2.5-1.119-2.5-2.5v-9c0-1.105-0.895-2-2-2h-4c-1.105,0-2,0.895-2,2v9c0,1.381-1.119,2.5-2.5,2.5h-9C7.119,43,6,41.881,6,40.5V21.413c0-2.299,1.054-4.471,2.859-5.893L23.071,4.321c0.545-0.428,1.313-0.428,1.857,0L39.142,15.52C40.947,16.942,42,19.113,42,21.411V40.5C42,41.881,40.881,43,39.5,43z"
                  fill="#FFFFFF" />
              </svg>
            </a>
          </li>

          <li class="nav-button" data-menuanchor="about">
            <a id="about-button" href="#about" title="about">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 48 48">
                <path
                  d="M20 4 A 10 10 0 0 0 20 24 A 10 10 0 0 0 20 4 z M 40.5 4 A 2.5 2.5 0 0 0 40.5 9 A 2.5 2.5 0 0 0 40.5 4 z M 38.5 11 A 1.50015 1.50015 0 1 0 38.5 14L39 14L39 23L38.5 23 A 1.50015 1.50015 0 1 0 38.5 26L42.5 26 A 1.50015 1.50015 0 1 0 42.5 23L42 23L42 14L42.5 14 A 1.50015 1.50015 0 1 0 42.5 11L38.5 11 z M 7.9785156 28C5.7845156 28 4 29.784516 4 31.978516L4 33.5C4 36.812 5.8846406 39.6755 9.3066406 41.5625C12.153641 43.1345 15.952 44 20 44C27.706 44 36 40.714 36 33.5L36 31.978516C36 29.784516 34.215484 28 32.021484 28L7.9785156 28 z"
                  fill="#FFFFFF" />
              </svg>
            </a>
          </li>

          <li class="nav-button" data-menuanchor="skills">
            <a id="skills-button" href="#skills" title="skills">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 48 48">
                <path
                  d="M21.668 5.782c-.88-.565-1.948-.861-3.095-.764C15.948 5.239 14 7.573 14 10.208v.542.044c-5.487 1.715-8 5.997-8 9.456 0 1.262.287 2.528.79 3.666C8.55 22.088 10.943 21 13.3 21c3.838 0 6.176 2.353 6.274 2.453.579.593.566 1.542-.026 2.121-.594.578-1.542.566-2.121-.027C17.371 25.492 15.835 24 13.3 24c-1.632 0-3.393.861-4.596 2.248C7.85 27.232 7 28.75 7 31c0 3.735 3.719 6.724 7 6.932l0 0C13.964 40.725 16.216 43 19 43c1.325 0 2.521-.522 3.413-1.366C22.8 41.267 23 40.744 23 40.211V8.283C23 7.28 22.512 6.324 21.668 5.782zM19.5 36c-.829 0-1.5-.672-1.5-1.5 0-1.379-1.122-2.5-2.5-2.5-.829 0-1.5-.672-1.5-1.5s.671-1.5 1.5-1.5c3.033 0 5.5 2.468 5.5 5.5C21 35.328 20.329 36 19.5 36zM16.5 18c-.829 0-1.5-.672-1.5-1.5s.671-1.5 1.5-1.5c.827 0 1.5-.673 1.5-1.5 0-.828.671-1.5 1.5-1.5s1.5.672 1.5 1.5C21 15.981 18.981 18 16.5 18zM34.7 21c2.357 0 4.75 1.088 6.51 2.916C41.713 22.778 42 21.512 42 20.25c0-3.459-2.513-7.741-8-9.456V10.75v-.542c0-2.634-1.948-4.969-4.573-5.189-1.147-.096-2.214.199-3.095.764C25.488 6.324 25 7.28 25 8.283v31.929c0 .531.198 1.053.583 1.418 1.218 1.156 3.007 1.71 4.916 1.15C32.605 42.162 34 40.154 34 37.96v-.028c3.281-.208 7-3.197 7-6.932 0-2.25-.85-3.768-1.704-4.752C38.094 24.861 36.333 24 34.7 24c-2.536 0-4.071 1.492-4.126 1.547-.579.594-1.527.605-2.121.027-.593-.579-.605-1.528-.026-2.121C28.524 23.353 30.862 21 34.7 21zM32.5 29c.829 0 1.5.672 1.5 1.5S33.329 32 32.5 32c-1.378 0-2.5 1.121-2.5 2.5 0 .828-.671 1.5-1.5 1.5S27 35.328 27 34.5C27 31.468 29.467 29 32.5 29zM27 13.5c0-.828.671-1.5 1.5-1.5s1.5.672 1.5 1.5c0 .827.673 1.5 1.5 1.5.829 0 1.5.672 1.5 1.5 0 .828-.671 1.5-1.5 1.5C29.019 18 27 15.981 27 13.5zM41 5A2 2 0 1041 9 2 2 0 1041 5zM7 39A2 2 0 107 43 2 2 0 107 39zM41 39A2 2 0 1041 43 2 2 0 1041 39zM46 16A2 2 0 1046 20 2 2 0 1046 16zM46 28A2 2 0 1046 32 2 2 0 1046 28zM2 16A2 2 0 102 20 2 2 0 102 16zM2 28A2 2 0 102 32 2 2 0 102 28zM7 5A2 2 0 107 9 2 2 0 107 5z"
                  fill="#FFFFFF" />
              </svg>
            </a>
          </li>

          <li class="nav-button" data-menuanchor="projects">
            <a id="projects-button" href="#projects" title="project">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 48 48">
                <path
                  d="M18.5 6C16.585045 6 15 7.5850452 15 9.5L15 12L7.5 12C5.57 12 4 13.57 4 15.5L4 28L21 28L21 27.5C21 26.67 21.67 26 22.5 26L25.5 26C26.33 26 27 26.67 27 27.5L27 28L44 28L44 15.5C44 13.57 42.43 12 40.5 12L33 12L33 9.5C33 7.5850452 31.414955 6 29.5 6L18.5 6 z M 18.5 9L29.5 9C29.795045 9 30 9.2049548 30 9.5L30 12L18 12L18 9.5C18 9.2049548 18.204955 9 18.5 9 z M 4 31L4 38.5C4 40.43 5.57 42 7.5 42L40.5 42C42.43 42 44 40.43 44 38.5L44 31L27 31L27 31.5C27 32.33 26.33 33 25.5 33L22.5 33C21.67 33 21 32.33 21 31.5L21 31L4 31 z"
                  fill="#FFFFFF" />
              </svg>
            </a>
          </li>

          <li class="nav-button" data-menuanchor="contact">
            <a id="contact-button" href="#contact" title="contact">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 48 48">
                <path
                  d="M39.5,8c2.485,0,4.5,2.015,4.5,4.5v23.009c0,2.485-2.015,4.5-4.5,4.5h-31c-2.485,0-4.5-2.015-4.5-4.5V12.5 C4,10.015,6.015,8,8.5,8H39.5z M18.5,25h-7c-0.759,0-1.387,0.564-1.486,1.296L10,26.5v0.984l0.016,0.217 c0.325,2.227,2.189,3.302,4.984,3.302c2.662,0,4.479-0.974,4.928-2.989l0.057-0.31L20,27.485V26.5c0-0.759-0.564-1.387-1.296-1.486 L18.5,25z M36.5,25.992h-8.995l-0.204,0.014c-0.732,0.099-1.296,0.727-1.296,1.486c0,0.759,0.564,1.387,1.296,1.486l0.204,0.014 H36.5l0.204-0.014C37.436,28.879,38,28.252,38,27.492c0-0.759-0.564-1.387-1.296-1.486L36.5,25.992z M15,17.004 c-1.657,0-3,1.343-3,3c0,1.657,1.343,3,3,3s3-1.343,3-3C18,18.347,16.657,17.004,15,17.004z M36.5,19h-8.995l-0.204,0.014 c-0.732,0.099-1.296,0.727-1.296,1.486s0.564,1.387,1.296,1.486L27.505,22H36.5l0.204-0.014C37.436,21.887,38,21.259,38,20.5 s-0.564-1.387-1.296-1.486L36.5,19z"
                  fill="#FFFFFF" />
              </svg>
          </a>
        </li>
        <div class="line"></div>
      </ul>
    </nav>

  </div>
</div></template>