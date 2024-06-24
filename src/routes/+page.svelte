<script>
  import AnimateDiv from "$lib/component/AnimateDiv.svelte";

  function diskonWhatsapp() {
    let message =
      "Assalamu alaykum MNA Travel, saya mau Diskonnya Paket Umroh ......";
    const url = `https://wa.me/6282240406568?text=${encodeURIComponent(message)}`;
    window.open(url, "_blank");
  }

  function infoPaket(namaPaket) {
    let message = `Assalamu alaykum MNA Travel, saya mau Info Detail Paket ${namaPaket}`;
    const url = `https://wa.me/6282240406568?text=${encodeURIComponent(message)}`;
    window.open(url, "_blank");
  }
</script>

<svelte:head>
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link
    href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap"
    rel="stylesheet"
  />
  <title>MNA - Travel | Pelayanan Umroh Terbaik</title>
  <meta
    name="description"
    content="Umroh Terbaik dan Terpercaya di Indonesia. ✔ Biaya Terjangkau, ✔ Profesional, ✔ Pasti Berangkat, ✔ Bonus City Tour Thaif, ✔ Bonus Haramian Express, ✔ Bonus Perlengkapan, ✔ Bonus Museum Wahyu, ✔ Bonus Ice Cream Uhud, ✔ Bonus Merchandise, ✔ Bonus Album Digital, ✔ Bonus Fotografer, ✔ Bonus Bus Daerah"
  />
  <meta
    name="keywords"
    content="Umroh, Travel, Pelayanan Umroh, Umroh Terbaik, MNA Travel"
  />
</svelte:head>



<div
  class="bg-gradient-to-b from-blue-400 to-blue-900 h-screen grid grid-cols-1 md:grid-cols-2 relative py-32 md:py-0 px-5 sm:px-0"
>
  <div class="absolute -bottom-2 z-20 w-full">
    <svg
      id="wave"
      style="transform:rotate(0deg); transition: 0.3s"
      viewBox="0 0 1440 210"
      version="1.1"
      xmlns="http://www.w3.org/2000/svg"
      ><defs
        ><linearGradient id="sw-gradient-0" x1="0" x2="0" y1="1" y2="0"
          ><stop stop-color="rgba(255, 255, 255, 1)" offset="0%"></stop><stop
            stop-color="rgba(255, 255, 255, 1)"
            offset="100%"
          ></stop></linearGradient
        ></defs
      ><path
        style="transform:translate(0, 0px); opacity:1"
        fill="url(#sw-gradient-0)"
        d="M0,189L80,157.5C160,126,320,63,480,63C640,63,800,126,960,157.5C1120,189,1280,189,1440,157.5C1600,126,1760,63,1920,59.5C2080,56,2240,112,2400,129.5C2560,147,2720,126,2880,112C3040,98,3200,91,3360,105C3520,119,3680,154,3840,143.5C4000,133,4160,77,4320,66.5C4480,56,4640,91,4800,105C4960,119,5120,112,5280,98C5440,84,5600,63,5760,59.5C5920,56,6080,70,6240,63C6400,56,6560,28,6720,14C6880,0,7040,0,7200,10.5C7360,21,7520,42,7680,73.5C7840,105,8000,147,8160,154C8320,161,8480,133,8640,122.5C8800,112,8960,119,9120,105C9280,91,9440,56,9600,35C9760,14,9920,7,10080,21C10240,35,10400,70,10560,77C10720,84,10880,63,11040,73.5C11200,84,11360,126,11440,147L11520,168L11520,210L11440,210C11360,210,11200,210,11040,210C10880,210,10720,210,10560,210C10400,210,10240,210,10080,210C9920,210,9760,210,9600,210C9440,210,9280,210,9120,210C8960,210,8800,210,8640,210C8480,210,8320,210,8160,210C8000,210,7840,210,7680,210C7520,210,7360,210,7200,210C7040,210,6880,210,6720,210C6560,210,6400,210,6240,210C6080,210,5920,210,5760,210C5600,210,5440,210,5280,210C5120,210,4960,210,4800,210C4640,210,4480,210,4320,210C4160,210,4000,210,3840,210C3680,210,3520,210,3360,210C3200,210,3040,210,2880,210C2720,210,2560,210,2400,210C2240,210,2080,210,1920,210C1760,210,1600,210,1440,210C1280,210,1120,210,960,210C800,210,640,210,480,210C320,210,160,210,80,210L0,210Z"
      ></path></svg
    >
  </div>
  <AnimateDiv
    className="flex flex-col justify-center items-center gap-6"
    beforeAnimated="opacity-0 translate-y-96"
    duration="duration-1000"
  >
    <img src="./logo-white.png" alt="" class="max-w-60" />
    <p class="font-semibold text-white text-center">
      Umroh Murah - Umroh Mudah - Umroh Berkah
    </p>
  </AnimateDiv>
  <AnimateDiv
    className="flex justify-center items-center"
    duration="duration-1000"
  >
    <a
      href="https://wa.me/6282240406568"
      target="_blank"
      class="bg-blue-50 hover:scale-110 transition-transform transform-gpu duration-300 text-blue-400 font-bold py-4 px-10 rounded-full flex items-center gap-3"
    >
      <div class="h-6 w-6 p-0.5">
        <svg
          fill="currentColor"
          version="1.1"
          id="Layer_1"
          xmlns="http://www.w3.org/2000/svg"
          xmlns:xlink="http://www.w3.org/1999/xlink"
          viewBox="0 0 308 308"
          xml:space="preserve"
          ><g id="SVGRepo_bgCarrier" stroke-width="0"></g><g
            id="SVGRepo_tracerCarrier"
            stroke-linecap="round"
            stroke-linejoin="round"
          ></g><g id="SVGRepo_iconCarrier">
            <g id="XMLID_468_">
              <path
                id="XMLID_469_"
                d="M227.904,176.981c-0.6-0.288-23.054-11.345-27.044-12.781c-1.629-0.585-3.374-1.156-5.23-1.156 c-3.032,0-5.579,1.511-7.563,4.479c-2.243,3.334-9.033,11.271-11.131,13.642c-0.274,0.313-0.648,0.687-0.872,0.687 c-0.201,0-3.676-1.431-4.728-1.888c-24.087-10.463-42.37-35.624-44.877-39.867c-0.358-0.61-0.373-0.887-0.376-0.887 c0.088-0.323,0.898-1.135,1.316-1.554c1.223-1.21,2.548-2.805,3.83-4.348c0.607-0.731,1.215-1.463,1.812-2.153 c1.86-2.164,2.688-3.844,3.648-5.79l0.503-1.011c2.344-4.657,0.342-8.587-0.305-9.856c-0.531-1.062-10.012-23.944-11.02-26.348 c-2.424-5.801-5.627-8.502-10.078-8.502c-0.413,0,0,0-1.732,0.073c-2.109,0.089-13.594,1.601-18.672,4.802 c-5.385,3.395-14.495,14.217-14.495,33.249c0,17.129,10.87,33.302,15.537,39.453c0.116,0.155,0.329,0.47,0.638,0.922 c17.873,26.102,40.154,45.446,62.741,54.469c21.745,8.686,32.042,9.69,37.896,9.69c0.001,0,0.001,0,0.001,0 c2.46,0,4.429-0.193,6.166-0.364l1.102-0.105c7.512-0.666,24.02-9.22,27.775-19.655c2.958-8.219,3.738-17.199,1.77-20.458 C233.168,179.508,230.845,178.393,227.904,176.981z"
              ></path>
              <path
                id="XMLID_470_"
                d="M156.734,0C73.318,0,5.454,67.354,5.454,150.143c0,26.777,7.166,52.988,20.741,75.928L0.212,302.716 c-0.484,1.429-0.124,3.009,0.933,4.085C1.908,307.58,2.943,308,4,308c0.405,0,0.813-0.061,1.211-0.188l79.92-25.396 c21.87,11.685,46.588,17.853,71.604,17.853C240.143,300.27,308,232.923,308,150.143C308,67.354,240.143,0,156.734,0z M156.734,268.994c-23.539,0-46.338-6.797-65.936-19.657c-0.659-0.433-1.424-0.655-2.194-0.655c-0.407,0-0.815,0.062-1.212,0.188 l-40.035,12.726l12.924-38.129c0.418-1.234,0.209-2.595-0.561-3.647c-14.924-20.392-22.813-44.485-22.813-69.677 c0-65.543,53.754-118.867,119.826-118.867c66.064,0,119.812,53.324,119.812,118.867 C276.546,215.678,222.799,268.994,156.734,268.994z"
              ></path>
            </g>
          </g></svg
        >
      </div>
      <span class="text-lg"> Hubungi Kami </span>
    </a>
  </AnimateDiv>
</div>

<AnimateDiv
  className="min-h-screen w-full flex flex-col items-center justify-center gap-2.5 py-16"
>
  <div class="py-3 px-5">
    <h1 class="font-bold text-3xl md:text-4xl text-center text-black">
      MNA Travel
    </h1>
    <h1 class="font-bold text-3xl md:text-4xl text-center text-blue-500">
      PT MNA GROUP INTERNASIONAL
    </h1>
  </div>
  <div class="p-10">
    <img src="./Sementara.jpg" alt="" class="w-full max-w-[540px]" />
  </div>
  <div
    class="p-5 w-full max-w-[760px] flex flex-col justify-center items-center gap-5"
  >
    <h1 class="text-blue-400 font-bold text-4xl text-center">
      لَبَّيْكَ اللَّهُمَّ لَبَّيْكَ. لَبَّيْكَ لَا شَرِيكَ لَكَ لَبَّيْكَ إِنَّ
      الْحَمْدَ والنِّعْمَةَ لَكَ وَالْمُلْكُ لَا شَرِيكَ لَكَ.
    </h1>
    <p class="text-center text-gray-500 text-lg">
      PT. MNA Travel adalah perusahaan jasa travel umroh yang didukung oleh
      tenaga ahli berpengalaman di bidangnya.
    </p>
  </div>
</AnimateDiv>

<div
  class="min-h-screen w-full flex flex-col items-center justify-center gap-12 py-20 bg-blue-100/50"
>
  <AnimateDiv className="py-3 px-5 flex flex-col gap-5">
    <h1 class="font-bold text-2xl md:text-3xl text-center text-black">
      Lihat apa kata mereka yang <span class="text-blue-500"
        >telah melaksanakan Ibadah Umroh</span
      > bersama kami
    </h1>
    <p class="text-center font-semibold text-lg md:text-xl">
      Berikut ini beberapa cerita dari jamaah MNA Travel
    </p>
  </AnimateDiv>
  <AnimateDiv
    className="grid grid-cols-1 md:grid-cols-2 w-full last:col-span-2"
  >
    <div class="flex flex-col justify-start items-center w-full gap-4 p-5">
      <img src="./star.png" alt="" />
      <p class="text-center text-lg">
        “Jamaah Ibu2 puas sejak keberangkatan, selama umroh sampai kepulangan…”
      </p>
      <a href="https://www.youtube.com/" class="text-blue-700">
        Link Youtube
      </a>
      <div class="max-h-[270px] mb-5">
        <img
          src="https://images.unsplash.com/photo-1649459304452-5a3e5d217102?q=80&w=1932&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
          alt=""
          class="h-full w-auto"
        />
      </div>
    </div>
    <div class="flex flex-col justify-start items-center w-full gap-4 p-5">
      <img src="./star.png" alt="" />
      <p class="text-center text-lg">
        “Alhamdulillah luar biasa, kontrak bintang 3 malah dapat bintang 4,
        pelayanannya bintang 5”
      </p>
      <a href="https://www.youtube.com/" class="text-blue-700">
        Link Youtube
      </a>
      <div class="max-h-[270px] mb-5">
        <img
          src="https://images.unsplash.com/photo-1520434087499-0fa48ffb40c9?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NHx8YXJhYiUyMHBlb3BsZXxlbnwwfHwwfHx8MA%3D%3D"
          alt=""
          class="h-full w-auto"
        />
      </div>
    </div>
    <div
      class="flex flex-col justify-start items-center w-full gap-4 p-5 md:col-span-2"
    >
      <img src="./star.png" alt="" />
      <p class="text-center text-lg">
        “Alhamdulillah diberi kelancaran, selama ibadah dibimbing dengan baik"
      </p>
      <a href="https://www.youtube.com/" class="text-blue-700">
        Link Youtube
      </a>
      <div class="max-h-[270px] mb-5">
        <img
          src="https://images.unsplash.com/photo-1507020177664-e4eac8761972?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8M3x8YXJhYiUyMHBlb3BsZXxlbnwwfHwwfHx8MA%3D%3D"
          alt=""
          class="h-full w-auto"
        />
      </div>
    </div>
  </AnimateDiv>
</div>

<div
  class="min-h-screen w-full flex flex-col items-center justify-center gap-12 py-24 bg-blue-900"
>
  <AnimateDiv className="py-3 px-5">
    <h1 class="font-bold text-3xl md:text-4xl text-center text-white">
      Mengapa harus <span class="text-blue-200">Haji & Umroh</span> bersama kami
      ?
    </h1>
  </AnimateDiv>
  <AnimateDiv
    className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6 px-10"
  >
    <div
      class="bg-white rounded-lg h-full flex flex-col justify-start items-center gap-8 p-8"
    >
      <div class="h-16 w-16 text-blue-900">
        <svg
          fill="currentColor"
          version="1.1"
          id="Capa_1"
          xmlns="http://www.w3.org/2000/svg"
          xmlns:xlink="http://www.w3.org/1999/xlink"
          viewBox="0 0 188.547 188.547"
          xml:space="preserve"
          ><g id="SVGRepo_bgCarrier" stroke-width="0"></g><g
            id="SVGRepo_tracerCarrier"
            stroke-linecap="round"
            stroke-linejoin="round"
          ></g><g id="SVGRepo_iconCarrier">
            <g>
              <path
                d="M94.589,145.478v13.019h46.765l6.235,6.235v6.235H29.118v-6.235l6.235-6.235h46.765v-13.025H15.281 C6.884,145.471,0,138.584,0,130.188V32.861c0-8.397,6.877-15.281,15.281-15.281h146.143c8.415,0,15.284,6.875,15.284,15.281V64.05 c-1.925-2.125-3.964-4.125-6.235-5.849v-25.34c0-4.987-4.056-9.045-9.049-9.045H15.281c-4.993,0-9.045,4.058-9.045,9.045v78.626 c0,4.993,4.052,9.049,9.045,9.049h90.184c8.476,12.124,22.426,19.57,37.405,19.57c2.49,0,4.957-0.268,7.398-0.676l3.508,6.053 H94.589V145.478z M176.951,74.77c10.863,18.816,4.396,42.977-14.432,53.822c-18.815,10.863-42.965,4.415-53.828-14.425 c-10.859-18.804-4.396-42.953,14.42-53.813C141.919,49.491,166.082,55.951,176.951,74.77z M171.3,78.043 c-9.073-15.707-29.222-21.099-44.926-12.054c-15.704,9.073-21.111,29.216-12.026,44.92c9.066,15.704,29.21,21.136,44.907,12.062 C174.965,113.887,180.355,93.744,171.3,78.043z M172.42,126.162l-16.94,9.792l13.056,22.566l16.94-9.792L172.42,126.162z M187.229,151.834l-16.952,9.779c2.716,4.689,8.695,6.284,13.378,3.593S189.939,156.523,187.229,151.834z M108.058,45.64H26v6.235 h82.058V45.64z M86.795,60.366H26v6.235h60.794V60.366z M86.795,75.099H26v6.235h60.794V75.099z M26,96.063h60.794v-6.235H26 V96.063z"
              ></path>
            </g>
          </g></svg
        >
      </div>
      <div class="flex flex-col justify-center items-center gap-4">
        <h1 class="text-lg md:text-xl font-semibold text-center">
          Sesuai Syariat
        </h1>
        <p class="text-center text-gray-500">
          Kami berkomitmen memberikan tuntunan ibadah In Syaa Allah sesuai
          Al-Quran dan As Sunnah, sehingga kemurnian ibadah terjaga dan
          keutamaan beribadah dapat tercapai dengan baik.
        </p>
      </div>
    </div>
    <div
      class="bg-white rounded-lg h-full flex flex-col justify-start items-center gap-8 p-8"
    >
      <div class="h-16 w-16 text-blue-900">
        <svg
          viewBox="0 0 24 24"
          id="Layer_1"
          data-name="Layer 1"
          xmlns="http://www.w3.org/2000/svg"
          fill="currentColor"
          ><g id="SVGRepo_bgCarrier" stroke-width="0"></g><g
            id="SVGRepo_tracerCarrier"
            stroke-linecap="round"
            stroke-linejoin="round"
          ></g><g id="SVGRepo_iconCarrier"
            ><defs
              ><style>
                .cls-1 {
                  fill: none;
                  stroke: currentColor;
                  stroke-miterlimit: 10;
                  stroke-width: 1.91px;
                }
              </style></defs
            ><path
              class="cls-1"
              d="M18.68,1.5h1.91A1.9,1.9,0,0,1,22.5,3.41V16.77a1.9,1.9,0,0,1-1.91,1.91H3.41A1.9,1.9,0,0,1,1.5,16.77V3.41A1.9,1.9,0,0,1,3.41,1.5H18.68Z"
            ></path><line class="cls-1" x1="12" y1="22.5" x2="12" y2="18.68"
            ></line><line class="cls-1" x1="16.77" y1="22.5" x2="7.23" y2="22.5"
            ></line><line class="cls-1" x1="1.5" y1="14.86" x2="22.5" y2="14.86"
            ></line><circle class="cls-1" cx="12" cy="8.18" r="2.86"
            ></circle><line class="cls-1" x1="12" y1="5.32" x2="12" y2="3.41"
            ></line><line class="cls-1" x1="12" y1="12.95" x2="12" y2="11.05"
            ></line><line class="cls-1" x1="9.52" y1="6.75" x2="7.87" y2="5.8"
            ></line><line
              class="cls-1"
              x1="16.13"
              y1="10.57"
              x2="14.48"
              y2="9.61"
            ></line><line class="cls-1" x1="16.13" y1="5.8" x2="14.48" y2="6.75"
            ></line><line class="cls-1" x1="9.52" y1="9.61" x2="7.87" y2="10.57"
            ></line></g
          ></svg
        >
      </div>
      <div class="flex flex-col justify-center items-center gap-4">
        <h1 class="text-lg md:text-xl font-semibold text-center">Izin Resmi</h1>
        <p class="text-center text-gray-500">
          Travel Haji dan Umroh dengan Izin Resmi yang pastinya memberikan
          keamanan dan kenyamanan selama beribadah.
        </p>
      </div>
    </div>
    <div
      class="bg-white rounded-lg h-full flex flex-col justify-start items-center gap-8 p-8"
    >
      <div class="h-16 w-16 text-blue-900">
        <svg
          fill="currentColor"
          viewBox="0 0 32 32"
          version="1.1"
          xmlns="http://www.w3.org/2000/svg"
          ><g id="SVGRepo_bgCarrier" stroke-width="0"></g><g
            id="SVGRepo_tracerCarrier"
            stroke-linecap="round"
            stroke-linejoin="round"
          ></g><g id="SVGRepo_iconCarrier">
            <title>lightbulb-on</title>
            <path
              d="M20 24.75h-8c-0.69 0-1.25 0.56-1.25 1.25v2c0 0 0 0 0 0 0 0.345 0.14 0.658 0.366 0.885l2 2c0.226 0.226 0.538 0.365 0.883 0.365 0 0 0.001 0 0.001 0h4c0 0 0.001 0 0.002 0 0.345 0 0.657-0.14 0.883-0.365l2-2c0.226-0.226 0.365-0.538 0.365-0.883 0-0.001 0-0.001 0-0.002v0-2c-0.001-0.69-0.56-1.249-1.25-1.25h-0zM18.75 27.482l-1.268 1.268h-2.965l-1.268-1.268v-0.232h5.5zM27.125 12.558c0.003-0.098 0.005-0.214 0.005-0.329 0-2.184-0.654-4.216-1.778-5.91l0.025 0.040c-1.919-3.252-5.328-5.447-9.263-5.644l-0.027-0.001h-0.071c-3.934 0.165-7.338 2.292-9.274 5.423l-0.028 0.049c-1.17 1.687-1.869 3.777-1.869 6.031 0 0.012 0 0.025 0 0.037v-0.002c0.184 2.294 0.923 4.383 2.081 6.176l-0.032-0.052c0.322 0.555 0.664 1.102 1.006 1.646 0.671 0.991 1.314 2.13 1.862 3.322l0.062 0.151c0.194 0.455 0.637 0.768 1.153 0.768 0 0 0.001 0 0.001 0h-0c0.173-0 0.338-0.035 0.489-0.099l-0.008 0.003c0.455-0.194 0.768-0.638 0.768-1.155 0-0.174-0.036-0.34-0.1-0.49l0.003 0.008c-0.669-1.481-1.374-2.739-2.173-3.929l0.060 0.095c-0.327-0.523-0.654-1.044-0.962-1.575-0.939-1.397-1.557-3.083-1.71-4.901l-0.003-0.038c0.019-1.735 0.565-3.338 1.485-4.662l-0.018 0.027c1.512-2.491 4.147-4.17 7.185-4.332l0.022-0.001h0.052c3.071 0.212 5.697 1.934 7.162 4.423l0.023 0.042c0.864 1.293 1.378 2.883 1.378 4.593 0 0.053-0 0.107-0.002 0.16l0-0.008c-0.22 1.839-0.854 3.496-1.807 4.922l0.026-0.041c-0.287 0.487-0.588 0.968-0.889 1.446-0.716 1.066-1.414 2.298-2.020 3.581l-0.074 0.175c-0.067 0.148-0.106 0.321-0.106 0.503 0 0.69 0.56 1.25 1.25 1.25 0.512 0 0.952-0.308 1.146-0.749l0.003-0.008c0.625-1.33 1.264-2.452 1.978-3.52l-0.060 0.096c0.313-0.498 0.625-0.998 0.924-1.502 1.131-1.708 1.891-3.756 2.12-5.961l0.005-0.058zM15.139 5.687c-0.199-0.438-0.633-0.737-1.136-0.737-0.188 0-0.365 0.041-0.525 0.116l0.008-0.003c-2.463 1.415-4.215 3.829-4.711 6.675l-0.008 0.057c-0.011 0.061-0.017 0.132-0.017 0.204 0 0.617 0.447 1.129 1.035 1.231l0.007 0.001c0.063 0.011 0.135 0.018 0.209 0.018h0c0.615-0.001 1.126-0.446 1.23-1.031l0.001-0.008c0.366-2.067 1.575-3.797 3.252-4.852l0.030-0.017c0.437-0.2 0.735-0.634 0.735-1.138 0-0.187-0.041-0.364-0.115-0.523l0.003 0.008zM1.441 3.118l4 2c0.16 0.079 0.348 0.126 0.546 0.126 0.69 0 1.25-0.56 1.25-1.25 0-0.482-0.273-0.9-0.672-1.109l-0.007-0.003-4-2c-0.16-0.079-0.348-0.126-0.546-0.126-0.69 0-1.25 0.56-1.25 1.25 0 0.482 0.273 0.9 0.672 1.109l0.007 0.003zM26 5.25c0.001 0 0.001 0 0.002 0 0.203 0 0.395-0.049 0.564-0.135l-0.007 0.003 4-2c0.407-0.212 0.679-0.63 0.679-1.112 0-0.69-0.56-1.25-1.25-1.25-0.199 0-0.387 0.046-0.554 0.129l0.007-0.003-4 2c-0.413 0.21-0.69 0.631-0.69 1.118 0 0.69 0.559 1.25 1.249 1.25h0zM30.559 20.883l-4-2c-0.163-0.083-0.355-0.132-0.559-0.132-0.69 0-1.249 0.559-1.249 1.249 0 0.486 0.278 0.908 0.683 1.114l0.007 0.003 4 2c0.163 0.083 0.355 0.132 0.559 0.132 0.69 0 1.249-0.559 1.249-1.249 0-0.486-0.278-0.908-0.683-1.114l-0.007-0.003zM5.561 18.867l-3.913 1.83c-0.428 0.205-0.718 0.634-0.718 1.131 0 0.691 0.56 1.25 1.25 1.25 0.191 0 0.372-0.043 0.534-0.119l-0.008 0.003 3.913-1.83c0.428-0.205 0.718-0.634 0.718-1.131 0-0.691-0.56-1.25-1.25-1.25-0.191 0-0.372 0.043-0.534 0.119l0.008-0.003zM2 13.25h1c0.69 0 1.25-0.56 1.25-1.25s-0.56-1.25-1.25-1.25v0h-1c-0.69 0-1.25 0.56-1.25 1.25s0.56 1.25 1.25 1.25v0zM30 10.75h-1c-0.69 0-1.25 0.56-1.25 1.25s0.56 1.25 1.25 1.25v0h1c0.69 0 1.25-0.56 1.25-1.25s-0.56-1.25-1.25-1.25v0z"
            ></path>
          </g></svg
        >
      </div>
      <div class="flex flex-col justify-center items-center gap-4">
        <h1 class="text-lg md:text-xl font-semibold text-center">Fasilitas</h1>
        <p class="text-center text-gray-500">
          Kami selalu memberikan Fasilitas dan Layanan terbaik, terbang sesuai
          jadwal, penerbangan terbaik, dan paket yang sesuai keinginan jamaah
        </p>
      </div>
    </div>
    <div
      class="bg-white rounded-lg h-full flex flex-col justify-start items-center gap-8 p-8"
    >
      <div class="h-16 w-16 text-blue-900">
        <svg
          viewBox="0 0 24 24"
          id="Layer_1"
          data-name="Layer 1"
          xmlns="http://www.w3.org/2000/svg"
          fill="currentColor"
          ><g id="SVGRepo_bgCarrier" stroke-width="0"></g><g
            id="SVGRepo_tracerCarrier"
            stroke-linecap="round"
            stroke-linejoin="round"
          ></g><g id="SVGRepo_iconCarrier"
            ><defs
              ><style>
                .cls-1 {
                  fill: none;
                  stroke: currentColor;
                  stroke-miterlimit: 10;
                  stroke-width: 1.91px;
                }
              </style></defs
            ><path
              class="cls-1"
              d="M18.68,1.5h1.91A1.9,1.9,0,0,1,22.5,3.41V16.77a1.9,1.9,0,0,1-1.91,1.91H3.41A1.9,1.9,0,0,1,1.5,16.77V3.41A1.9,1.9,0,0,1,3.41,1.5H18.68Z"
            ></path><line class="cls-1" x1="12" y1="22.5" x2="12" y2="18.68"
            ></line><line class="cls-1" x1="16.77" y1="22.5" x2="7.23" y2="22.5"
            ></line><line class="cls-1" x1="1.5" y1="14.86" x2="22.5" y2="14.86"
            ></line><circle class="cls-1" cx="12" cy="8.18" r="2.86"
            ></circle><line class="cls-1" x1="12" y1="5.32" x2="12" y2="3.41"
            ></line><line class="cls-1" x1="12" y1="12.95" x2="12" y2="11.05"
            ></line><line class="cls-1" x1="9.52" y1="6.75" x2="7.87" y2="5.8"
            ></line><line
              class="cls-1"
              x1="16.13"
              y1="10.57"
              x2="14.48"
              y2="9.61"
            ></line><line class="cls-1" x1="16.13" y1="5.8" x2="14.48" y2="6.75"
            ></line><line class="cls-1" x1="9.52" y1="9.61" x2="7.87" y2="10.57"
            ></line></g
          ></svg
        >
      </div>
      <div class="flex flex-col justify-center items-center gap-4">
        <h1 class="text-lg md:text-xl font-semibold text-center">Pembimbing</h1>
        <p class="text-center text-gray-500">
          Menghadirkan pembimbing profesional yang terikat dengan komitmen kuat
          perusahaan agar mewujudkan pelayanan ibadah yang maksimal kepada
          seluruh jemaah.
        </p>
      </div>
    </div>
    <div
      class="bg-white rounded-lg h-full flex flex-col justify-start items-center gap-8 p-8"
    >
      <div class="h-16 w-16 text-blue-900">
        <svg
          fill="currentColor"
          viewBox="0 0 32 32"
          version="1.1"
          xmlns="http://www.w3.org/2000/svg"
          ><g id="SVGRepo_bgCarrier" stroke-width="0"></g><g
            id="SVGRepo_tracerCarrier"
            stroke-linecap="round"
            stroke-linejoin="round"
          ></g><g id="SVGRepo_iconCarrier">
            <title>lightbulb-on</title>
            <path
              d="M20 24.75h-8c-0.69 0-1.25 0.56-1.25 1.25v2c0 0 0 0 0 0 0 0.345 0.14 0.658 0.366 0.885l2 2c0.226 0.226 0.538 0.365 0.883 0.365 0 0 0.001 0 0.001 0h4c0 0 0.001 0 0.002 0 0.345 0 0.657-0.14 0.883-0.365l2-2c0.226-0.226 0.365-0.538 0.365-0.883 0-0.001 0-0.001 0-0.002v0-2c-0.001-0.69-0.56-1.249-1.25-1.25h-0zM18.75 27.482l-1.268 1.268h-2.965l-1.268-1.268v-0.232h5.5zM27.125 12.558c0.003-0.098 0.005-0.214 0.005-0.329 0-2.184-0.654-4.216-1.778-5.91l0.025 0.040c-1.919-3.252-5.328-5.447-9.263-5.644l-0.027-0.001h-0.071c-3.934 0.165-7.338 2.292-9.274 5.423l-0.028 0.049c-1.17 1.687-1.869 3.777-1.869 6.031 0 0.012 0 0.025 0 0.037v-0.002c0.184 2.294 0.923 4.383 2.081 6.176l-0.032-0.052c0.322 0.555 0.664 1.102 1.006 1.646 0.671 0.991 1.314 2.13 1.862 3.322l0.062 0.151c0.194 0.455 0.637 0.768 1.153 0.768 0 0 0.001 0 0.001 0h-0c0.173-0 0.338-0.035 0.489-0.099l-0.008 0.003c0.455-0.194 0.768-0.638 0.768-1.155 0-0.174-0.036-0.34-0.1-0.49l0.003 0.008c-0.669-1.481-1.374-2.739-2.173-3.929l0.060 0.095c-0.327-0.523-0.654-1.044-0.962-1.575-0.939-1.397-1.557-3.083-1.71-4.901l-0.003-0.038c0.019-1.735 0.565-3.338 1.485-4.662l-0.018 0.027c1.512-2.491 4.147-4.17 7.185-4.332l0.022-0.001h0.052c3.071 0.212 5.697 1.934 7.162 4.423l0.023 0.042c0.864 1.293 1.378 2.883 1.378 4.593 0 0.053-0 0.107-0.002 0.16l0-0.008c-0.22 1.839-0.854 3.496-1.807 4.922l0.026-0.041c-0.287 0.487-0.588 0.968-0.889 1.446-0.716 1.066-1.414 2.298-2.020 3.581l-0.074 0.175c-0.067 0.148-0.106 0.321-0.106 0.503 0 0.69 0.56 1.25 1.25 1.25 0.512 0 0.952-0.308 1.146-0.749l0.003-0.008c0.625-1.33 1.264-2.452 1.978-3.52l-0.060 0.096c0.313-0.498 0.625-0.998 0.924-1.502 1.131-1.708 1.891-3.756 2.12-5.961l0.005-0.058zM15.139 5.687c-0.199-0.438-0.633-0.737-1.136-0.737-0.188 0-0.365 0.041-0.525 0.116l0.008-0.003c-2.463 1.415-4.215 3.829-4.711 6.675l-0.008 0.057c-0.011 0.061-0.017 0.132-0.017 0.204 0 0.617 0.447 1.129 1.035 1.231l0.007 0.001c0.063 0.011 0.135 0.018 0.209 0.018h0c0.615-0.001 1.126-0.446 1.23-1.031l0.001-0.008c0.366-2.067 1.575-3.797 3.252-4.852l0.030-0.017c0.437-0.2 0.735-0.634 0.735-1.138 0-0.187-0.041-0.364-0.115-0.523l0.003 0.008zM1.441 3.118l4 2c0.16 0.079 0.348 0.126 0.546 0.126 0.69 0 1.25-0.56 1.25-1.25 0-0.482-0.273-0.9-0.672-1.109l-0.007-0.003-4-2c-0.16-0.079-0.348-0.126-0.546-0.126-0.69 0-1.25 0.56-1.25 1.25 0 0.482 0.273 0.9 0.672 1.109l0.007 0.003zM26 5.25c0.001 0 0.001 0 0.002 0 0.203 0 0.395-0.049 0.564-0.135l-0.007 0.003 4-2c0.407-0.212 0.679-0.63 0.679-1.112 0-0.69-0.56-1.25-1.25-1.25-0.199 0-0.387 0.046-0.554 0.129l0.007-0.003-4 2c-0.413 0.21-0.69 0.631-0.69 1.118 0 0.69 0.559 1.25 1.249 1.25h0zM30.559 20.883l-4-2c-0.163-0.083-0.355-0.132-0.559-0.132-0.69 0-1.249 0.559-1.249 1.249 0 0.486 0.278 0.908 0.683 1.114l0.007 0.003 4 2c0.163 0.083 0.355 0.132 0.559 0.132 0.69 0 1.249-0.559 1.249-1.249 0-0.486-0.278-0.908-0.683-1.114l-0.007-0.003zM5.561 18.867l-3.913 1.83c-0.428 0.205-0.718 0.634-0.718 1.131 0 0.691 0.56 1.25 1.25 1.25 0.191 0 0.372-0.043 0.534-0.119l-0.008 0.003 3.913-1.83c0.428-0.205 0.718-0.634 0.718-1.131 0-0.691-0.56-1.25-1.25-1.25-0.191 0-0.372 0.043-0.534 0.119l0.008-0.003zM2 13.25h1c0.69 0 1.25-0.56 1.25-1.25s-0.56-1.25-1.25-1.25v0h-1c-0.69 0-1.25 0.56-1.25 1.25s0.56 1.25 1.25 1.25v0zM30 10.75h-1c-0.69 0-1.25 0.56-1.25 1.25s0.56 1.25 1.25 1.25v0h1c0.69 0 1.25-0.56 1.25-1.25s-0.56-1.25-1.25-1.25v0z"
            ></path>
          </g></svg
        >
      </div>
      <div class="flex flex-col justify-center items-center gap-4">
        <h1 class="text-lg md:text-xl font-semibold text-center">
          Professional & Berpengalaman
        </h1>
        <p class="text-center text-gray-500">
          Rasakan Perjalanan Spiritual Tak Terlupakan Bersama MNA Travel Layanan
          Wisata Umroh Terbaik untuk Anda
        </p>
      </div>
    </div>
    <div
      class="bg-white rounded-lg h-full flex flex-col justify-start items-center gap-8 p-8"
    >
      <div class="h-16 w-16 text-blue-900">
        <svg
          fill="currentColor"
          version="1.1"
          id="Capa_1"
          xmlns="http://www.w3.org/2000/svg"
          xmlns:xlink="http://www.w3.org/1999/xlink"
          viewBox="0 0 188.547 188.547"
          xml:space="preserve"
          ><g id="SVGRepo_bgCarrier" stroke-width="0"></g><g
            id="SVGRepo_tracerCarrier"
            stroke-linecap="round"
            stroke-linejoin="round"
          ></g><g id="SVGRepo_iconCarrier">
            <g>
              <path
                d="M94.589,145.478v13.019h46.765l6.235,6.235v6.235H29.118v-6.235l6.235-6.235h46.765v-13.025H15.281 C6.884,145.471,0,138.584,0,130.188V32.861c0-8.397,6.877-15.281,15.281-15.281h146.143c8.415,0,15.284,6.875,15.284,15.281V64.05 c-1.925-2.125-3.964-4.125-6.235-5.849v-25.34c0-4.987-4.056-9.045-9.049-9.045H15.281c-4.993,0-9.045,4.058-9.045,9.045v78.626 c0,4.993,4.052,9.049,9.045,9.049h90.184c8.476,12.124,22.426,19.57,37.405,19.57c2.49,0,4.957-0.268,7.398-0.676l3.508,6.053 H94.589V145.478z M176.951,74.77c10.863,18.816,4.396,42.977-14.432,53.822c-18.815,10.863-42.965,4.415-53.828-14.425 c-10.859-18.804-4.396-42.953,14.42-53.813C141.919,49.491,166.082,55.951,176.951,74.77z M171.3,78.043 c-9.073-15.707-29.222-21.099-44.926-12.054c-15.704,9.073-21.111,29.216-12.026,44.92c9.066,15.704,29.21,21.136,44.907,12.062 C174.965,113.887,180.355,93.744,171.3,78.043z M172.42,126.162l-16.94,9.792l13.056,22.566l16.94-9.792L172.42,126.162z M187.229,151.834l-16.952,9.779c2.716,4.689,8.695,6.284,13.378,3.593S189.939,156.523,187.229,151.834z M108.058,45.64H26v6.235 h82.058V45.64z M86.795,60.366H26v6.235h60.794V60.366z M86.795,75.099H26v6.235h60.794V75.099z M26,96.063h60.794v-6.235H26 V96.063z"
              ></path>
            </g>
          </g></svg
        >
      </div>
      <div class="flex flex-col justify-center items-center gap-4">
        <h1 class="text-lg md:text-xl font-semibold text-center">
          Proses Mudah
        </h1>
        <p class="text-center text-gray-500">
          Pelayanan yang cepat dan profesional, memudahkan Anda berangkat.
        </p>
      </div>
    </div>
  </AnimateDiv>
</div>

<AnimateDiv
  className="min-h-screen w-full flex flex-col items-center justify-center gap-2.5 py-16"
>
  <div class="flex flex-col justify-center items-center gap-4 py-3 px-5">
    <h1 class="font-bold text-3xl md:text-4xl text-center text-black">
      Gallery
    </h1>
    <h1 class="font-bold text-3xl md:text-4xl text-center text-blue-500">
      Kegiatan Jamaah
    </h1>
  </div>
  <div class="p-10">
    <img src="./Sementara.jpg" alt="" class="w-full max-w-[740px]" />
  </div>
</AnimateDiv>

<div
  class="h-[50vh] w-full flex flex-col items-center justify-center gap-2.5 py-16 bg-blue-100"
>
  <AnimateDiv
    className="flex flex-col justify-center items-center gap-4 py-3 px-5"
  >
    <h1 class="font-bold text-3xl md:text-4xl text-center text-black">
      <span class="text-blue-500">Pilihan Paket Terbaik</span> Umroh
    </h1>
    <h1 class="font-bold text-3xl md:text-4xl text-center">
      <span class="text-blue-500">Tahun 2024 M</span> - Musim 1446 H
    </h1>
  </AnimateDiv>
</div>

<div
  class="min-h-screen w-full flex flex-col items-center justify-start gap-2.5 py-16 bg-gray-200"
>
  <AnimateDiv className="text-center pb-16">
    <p class="text-blue-500 text-center">Klik Gambar untuk Detail Paket</p>
  </AnimateDiv>
  <AnimateDiv className="grid md:grid-cols-2 lg:grid-cols-3 px-10 gap-10">
    <div>
      <button
        name="clickDetail1"
        type="button"
        on:click={() => {
          infoPaket("UMROH EXCLUSIVE");
        }}
      >
        <img src="./3.png" alt="" /></button
      >
      <div class="flex flex-col text-center justify-center items-center">
        <h1 class="text-xl font-medium text-blue-900">UMROH EXCLUSIVE</h1>
        <p class="text-gray-600">Program 9 Hari</p>
        <p class="text-gray-600">Fasilitas Hotel Bintang 5</p>
        <br />
        <p class="text-gray-600">Direct Fly Tanpa Transit</p>
        <p></p>
      </div>
    </div>
    <div>
      <button
        name="clickDetail2"
        type="button"
        on:click={() => {
          infoPaket("UMROH SUPER HEMAT");
        }}
      >
        <img src="./4.png" alt="" /></button
      >
      <div class="flex flex-col text-center justify-center items-center">
        <h1 class="text-xl font-medium text-blue-900">UMROH SUPER HEMAT</h1>
        <p class="text-gray-600">Program 9 Hari</p>
        <p class="text-gray-600">Fasilitas Hotel Bintang 3</p>
        <br />
        <p class="text-gray-600">Penerbangan Transit By Emirates</p>
        <p></p>
      </div>
    </div>
    <div>
      <button
        name="clickDetail3"
        type="button"
        on:click={() => {
          infoPaket("UMROH EXCLUSIVE DUBAI");
        }}
      >
        <img src="./5.png" alt="" /></button
      >
      <div class="flex flex-col text-center justify-center items-center">
        <h1 class="text-xl font-medium text-blue-900">UMROH EXCLUSIVE DUBAI</h1>
        <p class="text-gray-600">Program 10 Hari</p>
        <p class="text-gray-600">Fasilitas Hotel Bintang 4</p>
        <br />
        <p class="text-gray-600">Direct Fly Tanpa Transit by Saudi/Garuda</p>
        <p></p>
      </div>
    </div>
  </AnimateDiv>
</div>

<div
  class="bg-gradient-to-b from-blue-400 to-blue-900 min-h-[50vh] py-32 md:py-20 flex flex-col justify-center items-center gap-24 w-full"
>
  <div class="flex flex-col justify-center items-center gap-6 px-5">
    <h1 class="font-bold text-3xl md:text-4xl text-center text-white">
      Ingat !!! Pilih Travel Haji & Umroh dengan izin Resmi
    </h1>
  </div>
  <div class="grid md:grid-cols-3 w-full px-10 gap-12">
    <div class="bg-white rounded-lg w-full relative my-4">
      <div
        class="flex flex-col justify-center items-center gap-4 text-center min-h-[220px]"
      >
        <h1 class="text-blue-700 text-4xl font-bold">5000 +</h1>
        <p class="text-black font-semibold">Memberangkatkan Jamaah</p>
      </div>
      <div class="absolute -top-12 w-full flex justify-center items-center">
        <div
          class="bg-yellow-100 drop-shadow h-24 w-24 rounded-full flex justify-center items-center"
        >
          <img src="./mengapa2.png" alt="" class="w-10 h-10" />
        </div>
      </div>
    </div>
    <div class="bg-white rounded-lg w-full relative my-4">
      <div
        class="flex flex-col justify-center items-center gap-4 text-center min-h-[220px]"
      >
        <h1 class="text-blue-700 text-4xl font-bold">1 - 3</h1>
        <p class="text-black font-semibold">Keberangkatan per Bulan</p>
      </div>
      <div class="absolute -top-12 w-full flex justify-center items-center">
        <div
          class="bg-yellow-100 drop-shadow h-24 w-24 rounded-full flex justify-center items-center"
        >
          <img src="./mengapa3.png" alt="" class="w-10 h-10" />
        </div>
      </div>
    </div>
    <div class="bg-white rounded-lg w-full relative my-4">
      <div
        class="flex flex-col justify-center items-center gap-4 text-center min-h-[220px]"
      >
        <h1 class="text-blue-700 text-4xl font-bold">7 +</h1>
        <p class="text-black font-semibold">Tahun Pengalaman</p>
      </div>
      <div class="absolute -top-12 w-full flex justify-center items-center">
        <div
          class="bg-yellow-100 drop-shadow h-24 w-24 rounded-full flex justify-center items-center"
        >
          <img src="./mengapa1.png" alt="" class="w-10 h-10" />
        </div>
      </div>
    </div>
  </div>
</div>

<div
  class="h-[50vh] w-full flex flex-col items-center justify-center gap-2.5 py-16 bg-blue-100"
>
  <div class="flex flex-col justify-center items-center gap-8 py-3 px-5">
    <h1 class="font-bold text-2xl md:text-3xl text-center text-black">
      Daftar Secara Online Dapatkan Diskon Spesial
    </h1>
    <div class="max-w-[1100px] text-center">
      <p>
        Pendaftaran Haji dan Umroh bisa datang langsung ke kantor kami, atau
        bisa melakukan pendaftaran secara online dengan menghubungi admin kami.
      </p>
      <br />
      <p>
        Pembayaran hanya melalui Nomor Rekening Resmi Perusahaan atas nama PT
        Wafdullah Tamu Mulia.
      </p>
    </div>
    <button
      name="clickDiskon"
      on:click={() => {
        diskonWhatsapp();
      }}
      class="px-6 py-4 bg-blue-900 rounded-lg gap-4 flex justify-center items-center"
    >
      <div class="w-8 h-8 text-white">
        <svg
          viewBox="0 0 1024 1024"
          fill="currentColor"
          class="icon"
          version="1.1"
          xmlns="http://www.w3.org/2000/svg"
          ><g id="SVGRepo_bgCarrier" stroke-width="0"></g><g
            id="SVGRepo_tracerCarrier"
            stroke-linecap="round"
            stroke-linejoin="round"
          ></g><g id="SVGRepo_iconCarrier"
            ><path
              d="M361.45 1023.91c-14.34 0-28.682-5.454-39.586-16.358L16.458 702.148c-21.84-21.84-21.84-57.348-0.016-79.172l441.16-441.158c20.48-20.48 59.956-31.526 88.092-24.636l206.536 50.646c24.588 6.062 49.332 27.854 60.19 53.004a7.998 7.998 0 0 1-4.17 10.514c-4.032 1.75-8.78-0.11-10.514-4.17-8.716-20.2-29.932-39.024-49.318-43.804L541.88 172.726c-22.886-5.624-56.3 3.75-72.968 20.402L27.754 634.288c-7.516 7.514-11.638 17.542-11.638 28.26 0 10.732 4.138 20.762 11.654 28.292l305.404 305.404c15.592 15.576 40.976 15.576 56.566-0.016l441.126-441.142c16.67-16.668 25.994-50.098 20.386-72.984l-37.336-152.266a8 8 0 0 1 5.858-9.686 8.008 8.008 0 0 1 9.672 5.876l37.336 152.264c7.014 28.588-3.796 67.298-24.606 88.106L401.05 1007.552c-10.92 10.906-25.274 16.358-39.6 16.358z"
              fill=""
            ></path><path
              d="M663.934 423.986c-16.386 0-32.76-6.232-45.224-18.7-24.964-24.962-24.964-65.564-0.016-90.512 21.95-21.95 56.348-25.026 81.764-7.28a65.05 65.05 0 0 1 8.748 7.234 7.994 7.994 0 0 1 0.062 11.31c-3.11 3.138-8.17 3.186-11.308 0.078a48.916 48.916 0 0 0-6.61-5.468c-19.074-13.31-44.866-11.028-61.348 5.438-18.714 18.714-18.7 49.162 0.016 67.892 18.716 18.7 49.164 18.714 67.91-0.032 5.638-5.686 9.824-12.7 12.058-20.262 1.25-4.234 5.75-6.67 9.936-5.39a8 8 0 0 1 5.404 9.936c-2.982 10.092-8.542 19.418-16.074 27.01-12.496 12.498-28.916 18.746-45.318 18.746z"
              fill=""
            ></path><path
              d="M663.824 392.026c-8.466 0-16.464-3.312-22.494-9.342a31.76 31.76 0 0 1-9.376-22.666c0.016-17.636 14.374-31.978 31.994-31.978 4.42 0 7.998 3.578 7.998 7.998s-3.578 8-7.998 8c-8.81 0-15.98 7.17-15.996 15.996a15.768 15.768 0 0 0 4.686 11.326 15.768 15.768 0 0 0 11.248 4.67h0.078a15.952 15.952 0 0 0 11.874-5.326 8 8 0 0 1 11.902 10.684 31.922 31.922 0 0 1-23.728 10.638h-0.188z"
              fill=""
            ></path><path
              d="M663.95 368.03a8.002 8.002 0 0 1-7.81-6.31 8.024 8.024 0 0 1 6.138-9.514c281.864-60.692 345.6-302.204 345.6-344.116 0-4.42 3.578-8 8-8a7.994 7.994 0 0 1 7.998 8c0 43.914-66.064 296.844-358.222 359.752a8.1 8.1 0 0 1-1.704 0.188z"
              fill=""
            ></path><path
              d="M738.856 192.05a7.944 7.944 0 0 1-4.592-1.454 7.99 7.99 0 0 1-1.954-11.138C836.024 31.24 989.85 0.09 1015.908 0.09h0.016c4.42 0 7.998 3.578 7.998 8s-3.578 7.998-7.998 7.998h-0.016c-23.292 0-171.98 31.774-270.508 172.542a7.934 7.934 0 0 1-6.544 3.42zM312.1 607.95c-39.694-0.016-71.984-32.322-71.984-71.986 0-39.694 32.292-71.984 71.984-72 39.696 0.016 71.986 32.306 71.986 71.984s-32.292 71.986-71.986 72.002z m0-127.992c-30.868 0.016-55.988 25.136-55.988 56.004 0 30.854 25.122 55.974 55.988 55.99 30.87-0.016 55.99-25.136 55.99-56.006 0-30.866-25.122-55.972-55.99-55.988zM488.064 783.912c-39.696-0.016-71.986-32.322-71.986-71.984 0-39.696 32.292-71.986 71.986-72.002 39.696 0.016 71.984 32.306 71.984 72.002 0 39.662-32.288 71.968-71.984 71.984z m0-127.99c-30.87 0.016-55.988 25.136-55.988 56.006 0 30.854 25.12 55.972 55.988 55.988 30.868-0.016 55.988-25.134 55.988-55.988 0-30.87-25.12-55.99-55.988-56.006zM248.114 783.912a7.996 7.996 0 0 1-5.654-13.654l303.938-303.952a7.996 7.996 0 1 1 11.308 11.31L253.77 781.568a7.976 7.976 0 0 1-5.656 2.344z"
              fill=""
            ></path></g
          ></svg
        >
      </div>
      <span class="text-white text-lg font-medium">Ambil Diskon</span></button
    >
  </div>
</div>



<style>
  * {
    font-family: "Poppins", Sans-serif !important;
  }
</style>
