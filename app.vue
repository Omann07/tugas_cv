<template>
  <div class="sticky top-0 z-50 bg-gray-800 min-h-screen"> <!-- Container utama -->
    <header class="absolute inset-x-0 top-0 z-50 bg-gray-800"> <!-- Header dengan background sama -->
      <nav class="flex items-center justify-between p-6 lg:px-8" aria-label="Global">
        <div class="flex lg:flex-1">
          <a href="#" class="-m-1.5 p-1.5">
            <p class="text-white">Abdul Rochman</p>
          </a>
        </div>
        <div class="flex lg:hidden">
          <button type="button" class="-m-2.5 inline-flex items-center justify-center rounded-md p-2.5 text-gray-300">
            <span class="sr-only">Open main menu</span>
            <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" aria-hidden="true">
              <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
            </svg>
          </button>
        </div>
        <div class="hidden lg:flex lg:gap-x-12">
          <a href="#" class="text-sm font-semibold leading-6 text-white">Home</a>
          <a href="#about1" class="text-sm font-semibold leading-6 text-white">About</a>
          <a href="#contact" class="text-sm font-semibold leading-6 text-white">Contact</a>
        </div>
      </nav>
    </header>

    <div class="relative isolate px-6 pt-14 lg:px-8">
      <div class="absolute inset-x-0 -top-200 -z-10 transform-gpu overflow-hidden blur-3xl sm:-top-80" aria-hidden="true">
        <div class="relative left-[calc(50%-11rem)] aspect-[1155/678] w-[36.125rem] -translate-x-1/2 rotate-[30deg] bg-gradient-to-tr from-[#ff80b5] to-[#9089fc] opacity-30 sm:left-[calc(50%-30rem)] sm:w-[72.1875rem]" style="clip-path: polygon(74.1% 44.1%, 100% 61.6%, 97.5% 26.9%, 85.5% 0.1%, 80.7% 2%, 72.5% 32.5%, 60.2% 62.4%, 52.4% 68.1%, 47.5% 58.3%, 45.2% 34.5%, 27.5% 76.7%, 0.1% 64.9%, 17.9% 100%, 27.6% 76.8%, 76.1% 97.7%, 74.1% 44.1%)"></div>
      </div>
      <div class="mx-auto max-w-2xl py-32 sm:py-48 lg:py-56">
        <div style="display: flex; justify-content: center; align-items: center;">
          <img src="@/assets/img/gambar2.jpg" style="width: 200px; height: 200px; border-radius: 50%;" />
        </div>

        <div class="text-center">
          <h1 class="text-4xl font-bold tracking-tight text-white sm:text-6xl">Selamat Datang</h1>
          <p class="mt-6 text-lg leading-8 text-gray-300">Terima kasih telah mampir👋👋</p>
          <p class="mt-6 text-lg leading-8 text-gray-300"></p>
          <div class="mt-10 flex items-center justify-center gap-x-6">
            <a href="#about1" class="rounded-md bg-indigo-600 px-3.5 py-2.5 text-sm font-semibold text-white shadow-sm hover:bg-indigo-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600">Get started</a>
            <a href="#" class="text-sm font-semibold leading-6 text-gray-300">Learn more <span aria-hidden="true">→</span></a>
          </div>
        </div>
      </div>
    </div>
    <div id="about1">
    <div class="text-center">
          <h1 class="text-4xl font-bold tracking-tight text-white sm:text-6xl">About Me</h1>
          <br><br>
        </div>
            <div class="md:flex mt-8">
                <div class="w-full h-64 md:mx-9 rounded-md overflow-hidden bg-cover bg-center md:w-1/2">
                    <div class="bg-gradient-to-r from-cyan-500 to-blue-500 bg-opacity-50 flex items-center h-full">
                        <div class="px-10 max-w-xl">
                            <h2 class="text-2xl text-white font-semibold">Biodata</h2>
                            <p class="mt-2 text-white">Saya, Abdul Rochman mahasiswa program studi teknologi informasi tahun 2023</p>
                            <p class="mt-2 text-white">Pacitan, Jawa Timur</p>
                        </div>
                    </div>
                </div>
                <div class="w-full h-64 mt-8 md:mx-9 rounded-md overflow-hidden bg-cover bg-center md:mt-0 md:w-1/2" style="background-image: url('@/assets/img/gambar4.png')">
                    <div class="bg-gradient-to-r from-purple-500 to-pink-500 bg-opacity-50 flex items-center h-full ">
                        <div class="px-10 max-w-xl">
                            <h2 class="text-2xl text-white font-semibold">My Project</h2>
                            <p class="mt-2 text-white">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Tempore facere provident molestias ipsam sint voluptatum pariatur.</p>
                            <button class="flex items-center mt-4 text-white text-sm uppercase font-medium rounded hover:underline focus:outline-none">
                                <span>Lihat Disini</span>
                                <svg class="h-5 w-5 mx-2" fill="none" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" viewBox="0 0 24 24" stroke="currentColor"><path d="M17 8l4 4m0 0l-4 4m4-4H3"></path></svg>
                            </button>
                        </div>
                    </div>
                </div>
            </div>
            <div class="md:flex mt-8 justify-center"> <!-- Tambahkan justify-center -->
              <div class="w-full h-64 md:mx-9 rounded-md overflow-hidden bg-cover bg-center md:w-1/2"
    style="background-image: url('https://images.unsplash.com/photo-1547949003-9792a18a2601?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=750&q=80')">
    <div class="bg-gray-900 bg-opacity-50 flex items-center h-full">
        <div class="px-10 max-w-xl">
            <h2 class="text-2xl text-white font-semibold">My Social Media</h2>
            <div class="flex items-center mt-2"> <!-- Flex container untuk gambar dan teks -->
              <a href="https://www.instagram.com/omann07?igsh=eGptMGEzdW41ZXI2"><img src="@/assets/img/instagram.png" style="width: 50px; height: 50px;" /> </a>
                <span class="text-white ml-2"><a href="https://www.instagram.com/omann07?igsh=eGptMGEzdW41ZXI2">omann07</a></span> <!-- Tambahkan tulisan "Instagram" -->
            </div>
            <div class="flex items-center mt-2"> <!-- Flex container untuk gambar dan teks -->
              <a href="https://github.com/Omann07"><img src="@/assets/img/github.png" style="width: 50px; height: 50px;" /></a>
                <span class="text-white ml-2"><a href="https://github.com/Omann07">Omann07</a></span> <!-- Tambahkan tulisan "Instagram" -->
            </div>
        </div>
    </div>
</div>

</div>

            <br><br><br><br>
          </div>
          <section class="bg-white dark:bg-gray-900">
  <div id="contact" class="py-8 lg:py-16 px-4 mx-auto max-w-screen-md">
      <h2 class="mb-4 text-4xl tracking-tight font-extrabold text-center text-gray-900 dark:text-white">Contact Me</h2>
      <p class="mb-8 lg:mb-16 font-light text-center text-gray-500 dark:text-gray-400 sm:text-xl">Hubungi saya melalui form dibawah ini</p>
      <form action="#" class="space-y-8">
          <div>
              <label for="email" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">Email</label>
              <input type="email" id="email" class="shadow-sm bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-500 focus:border-primary-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500 dark:shadow-sm-light" placeholder="email@gmail.com" required>
          </div>
          <div>
              <label for="subject" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">Name</label>
              <input type="text" id="subject" class="block p-3 w-full text-sm text-gray-900 bg-gray-50 rounded-lg border border-gray-300 shadow-sm focus:ring-primary-500 focus:border-primary-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500 dark:shadow-sm-light" placeholder="Nama anda" required>
          </div>
          <div class="sm:col-span-2">
              <label for="message" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-400">Pesan</label>
              <textarea id="message" rows="6" class="block p-2.5 w-full text-sm text-gray-900 bg-gray-50 rounded-lg shadow-sm border border-gray-300 focus:ring-primary-500 focus:border-primary-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500" placeholder="Tulis Disini..."></textarea>
          </div>
          <button type="submit" class="py-3 px-5 text-sm font-medium text-center text-black rounded-lg bg-white sm:w-fit hover:bg-gray-100 focus:ring-4 focus:outline-none focus:ring-gray-300 dark:bg-gray-800 dark:hover:bg-gray-900 dark:text-white dark:focus:ring-gray-700">
    Kirim
</button>
      </form>
  </div>
</section>
    <!-- Footer dengan background sama -->
    <div class="bg-gray-800 rounded-lg shadow dark:bg-gray-900 ">
      <div class="w-full max-w-screen-xl mx-auto p-4 md:py-8">
        <hr class="my-6 border-gray-200 sm:mx-auto dark:border-gray-700 lg:my-8" />
        <span class="block text-sm text-gray-500 sm:text-center dark:text-gray-400">© 2024 <a href="https://flowbite.com/" class="hover:underline">Abdul</a>. All Rights Reserved.</span>
      </div>
    </div>
  </div>
</template>
