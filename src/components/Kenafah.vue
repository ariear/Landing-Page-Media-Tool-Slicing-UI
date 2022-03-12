<template>
  <div class="pt-56 md:pt-96 pb-40 flex flex-col lg:flex-row justify-between items-center container mx-auto">

      <div class="px-7 md:px-0 md:w-[450px]">

          <div class="flex items-center mb-5">
          <div class="w-[45px] border border-[#FC881D]"></div>
          <p class="font-title font-semibold text-[#FC881D] ml-3">KENAPA SIH?</p>
          </div>

          <p class="text-3xl font-title font-bold">Kenapa Kami Tidak Memberikan Insight Apapun ?</p>
          <p class="font-title text-base py-8">Di sini kita akan klarifikasi mengapa kita tidak memberikan insight apapun di tool ini kepada kamu. Pada dasarnya hal ini kami lakukan semata-mata ingin menyelamatkan planet bumi.</p>
          
          <button class="py-4 px-6 bg-[#0D0E25] rounded-full text-white font-dmsans flex items-center shadow-lg hover:bg-[#212238] transition-all">Pelajari Lebih Lanjut <img src="/arrow.png" class="ml-3" ></button>
      </div>


    <div class="grid grid-cols-1 md:grid-cols-2 lg:mt-0 mt-28">

        <div class="w-[290px] bg-[#0D0E25] text-white rounded-lg p-9">
            <div class="flex items-center">
                <img src="/icon-database.png" alt="">
                <p class="font-title font-semibold ml-5">Database</p>
            </div>
            <p class="font-title mt-7">
                Data insight yang banyak kan bakal disimpen di database, ya kalo datanya banyak kan jadi gede juga size database-nya.
            </p>
        </div>

        <div class="w-[290px] rounded-lg p-9">
            <div class="flex items-center">
                <img src="/server.png" alt="">
                <p class="font-title font-semibold ml-5">Server</p>
            </div>
            <p class="font-title mt-7">
                Kalo ada insight, kamu akan bulak balik ngecek kan? Otomatis server harus idup terus, itu butuh listrik! 
            </p>
        </div>

                <div class="w-[290px] rounded-lg p-9">
            <div class="flex items-center">
                <img src="/listrik.png" alt="">
                <p class="font-title font-semibold ml-5">Listrik</p>
            </div>
            <p class="font-title mt-7">
                Biaya listrik mahal, bos! Listrik kita ini masih batu bara, nggak bagus buat lingkungan. Kalo pake nuklir sih oke-oke aja.
            </p>
        </div>

            <div class="w-[290px] border-t border-l p-9">
            <div class="flex items-center">
                <img src="/lingkungan.png" alt="">
                <p class="font-title font-semibold ml-5">Lingkungan</p>
            </div>
            <p class="font-title mt-7">
                Pokoknya nggak bagus lah buat lingkungan, ini alesan kita kenapa gak kasih insight. Demi menyelamatkan bumi!
            </p>
        </div>


    </div>
  </div>
</template>

<script>
export default {

}
</script>
