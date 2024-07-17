<script>
    import { ChevronDown } from 'lucide-svelte';
</script>

<div class="flex flex-col gap-y-2">
    <div class="flex flex-col gap-y-2">
        <div class="flex flex-col text-white font-bold relative">
            <img class="w-screen h-screen object-cover" src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/4b/Dypsis_lutescens1.jpg/250px-Dypsis_lutescens1.jpg" alt="Mangga">
            <div class="absolute pt-64 pl-5 pr-20 w-full h-full bg-black bg-opacity-35 ">
                <p class="text-4xl">Palem Kuning</p>
                <i class="text-lg font-normal">Dypsis Lutescens</i>
                <p class="text-sme font-normal">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consectetur molestias debitis dolore, rerum magni fugiat sed illo repudiandae aliquid voluptatem.</p>
            </div>
            <a href="#main" class="absolute bottom-0 left-1/2 transform -translate-x-1/2 animate-bounce">
                <ChevronDown size="48" />
            </a>
        </div>
    </div>

    <div id="main" class="p-5 text-justify flex flex-col gap-y-5">
        <div>
            Palem kuning (Dypsis Lutescens) adalah tanaman hias populer yang biasa dijumpai di pekarangan. Tumbuhan anggota suku pinang-pinangan (Arecaceae)[1] ini berasal dari Madagaskar namun di tempat asalnya sekarang terancam. Tumbuhan ini dapat tumbuh hingga setinggi 6 meter, meskipun biasanya di pekarangan hanya setinggi 3 meter karena alasan keindahan. Seperti palem lainnya, daun tersusun majemuk, menyirip. Warna helai daun hijau terang, cenderung kekuningan (sehingga disebut palem kuning). Daun ini memiliki pelepah daun yang cukup panjang dan menutupi batang yang beruas-ruas. Jumlah anak daun sekitar 80 hingga 100 lembar.
        </div>
        <div>
            Karena tampilannya yang cantik, palem kuning menjadi favorit masyarakat Indonesia dan cocok untuk sebagai tanaman indoor maupun outdoor.
        </div>
        <div>
            <div class="font-bold">Klasifikasi dari tanaman Palem Kuning:</div>
            <ul class="list-disc px-3">
                <li>Kingdom: Plantae</li>
                <li>Subkingdom: Tracheobionta</li>
                <li>Superdivisi: Spermatophyta</li>
                <li>Divisi: Magnoliophyta</li>
                <li>Kelas: Liliopsida</li>
                <li>Subkelas: Arecidae</li>
                <li>Ordo: Arecales</li>
                <li>Famili: Arecaceae</li>
                <li>Genus: Dypsis</li>
                <li>Spesies: Dypsis Lutescens</li>
            </ul>
        </div>
        <div>
            Palem kuning memiliki berbagai manfaat, antara lain:
            <ul class="list-decimal px-3">
                <li>Bisa Menahan Erosi. Seperti tanaman palem lainnya, tanaman ini juga memiliki tipe perakaran berserabut. Dengan tipe tersebut, palem ini dapat membuat partikel tanah di sekitar terbentuk dengan baik. Kemudian, tanaman tersebut juga bisa memunculkan tunas-tunas dan anakan yang bisa membuat diameter rumpun tanaman jadi lebih cepat membesar. Pembentukan tersebut membuat palem kuning cukup efektif dalam menahan erosi permukaan tanah.</li>
                <li>Dapat Meredam Getaran. Bentuknya yang seperti tiang membuat tanaman ini dapat menerima getaran dengan lebih baik. Dengan begitu, bagi kamu yang memiliki rumah di jalan raya atau di kawasan rel kereta api, kamu bisa lo menanam tanaman ini agar getaran yang dihasilkan dari kendaraan bisa diminimalkan.</li>
                <li>Mampu Mereduksi Gas Polutan. Kini, gas polutan sangat rentan menyebar ke seluruh permukaan bumi dan membuat polusi udara semakin merebak. Untuk mengatasinya, kamu bisa menanam pohon palem yang kabarnya mampu mengurangi konsentrasi dari gas polutan, sehingga udara di sekitar rumah menjadi lebih bersih. </li>
            </ul>
        </div>
        <div>
            Status konservasi Palem Kuning (Dypsis lutescens) adalah "Hampir Terancam" (Near Threatened) menurut IUCN Red List. Hal ini disebabkan oleh aktivitas manusia di daerah asalnya, Madagaskar, yang menyebabkan populasi tumbuhan tersebut semakin terancam
        </div>
    </div>
</div>