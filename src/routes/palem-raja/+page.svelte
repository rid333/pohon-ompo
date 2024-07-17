<script>
    import { ChevronDown } from 'lucide-svelte';
</script>

<div class="flex flex-col gap-y-2">
    <div class="flex flex-col gap-y-2">
        <div class="flex flex-col text-white font-bold relative">
            <img class="w-screen h-screen object-cover" src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/3e/Roystonea_regia.jpg/800px-Roystonea_regia.jpg" alt="Mangga">
            <div class="absolute pt-64 pl-5 pr-20 w-full h-full bg-black bg-opacity-35 ">
                <p class="text-4xl">Palem Raja</p>
                <i class="text-lg font-normal">Roystonea Regia</i>
                <p class="text-sme font-normal">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consectetur molestias debitis dolore, rerum magni fugiat sed illo repudiandae aliquid voluptatem.</p>
            </div>
            <a href="#main" class="absolute bottom-0 left-1/2 transform -translate-x-1/2 animate-bounce">
                <ChevronDown size="48" />
            </a>
        </div>
    </div>

    <div id="main" class="p-5 text-justify flex flex-col gap-y-5">
        <div>
            Palem raja adalah sekelompok palem (10 jenis) yang dikelompokkan dalam marga Roystonea. Tumbuhan ini berasal dari daerah Karibia dan Amerika tropika. Nama Roystonea diambil dari nama seorang insinyur yang bekerja di kemiliteran AS, Roy Stone. Salah satu anggotanya, R. regia biasa ditanam di pinggir jalan atau di taman-taman. Palem raja termasuk suku Arecaceae (palem-paleman), merupakan tumbuhan biji tertutup (Angiospermae) yaitu biji buahnya terbungkus daging. Palem raja (Roystonea regia) merupakan tumbuhan pohon atau panjatan. Palem raja adalah tumbuhan yang tak bercabang dan tumbuh tegak ke atas. Tumbuhan ini bisa tumbuh hingga mencapai tinggi 20 m.
        </div>
        <div>
            <div class="font-bold">Klasifikasi dari tanaman Palem Raja:</div>
            <ul class="list-disc px-3">
                <li>Kingdom: Plantae</li>
                <li>Subkingdom: Tracheobionta</li>
                <li>Superdivisi: Spermatophyta</li>
                <li>Divisi: Magnoliophyta</li>
                <li>Kelas: Liliopsida</li>
                <li>Subkelas: Arecidae</li>
                <li>Ordo: Arecales</li>
                <li>Famili: Arecaceae</li>
                <li>Genus: Roystonea</li>
                <li>Spesies: Roystonea Regia</li>
            </ul>
        </div>
        <div>
            Palem raja mempunyai beberapa manfaat antara lain sebagai berikut:
            <ul class="list-decimal px-3">
                <li>Sebagai tanam hias taman: sering kita lihat di taman-taman kota.</li>
                <li>Sebagai penghias pekarangan rumah.</li>
                <li>Sebagai kayu bakar (pelepah) di daerah pedesaan.</li>
                <li>Sebagai pohon penyejuk udara.</li>
                <li>Sebagai perkakas bangunan.</li>
            </ul>
        </div>
        <div>
            Status konservasi palem raja (Roystonea regia) adalah Risiko Rendah (IUCN 3.1)
        </div>
    </div>
</div>