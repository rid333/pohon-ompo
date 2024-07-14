<script>
    import PucukMerah from '$lib/assets/pucuk_merah.jpg';
    import { ChevronDown } from 'lucide-svelte';
</script>

<div class="flex flex-col gap-y-2">
    <div class="flex flex-col gap-y-2">
        <div class="flex flex-col text-white font-bold relative">
            <img class="w-screen h-screen object-cover" src={PucukMerah} alt="Mangga">
            <div class="absolute pt-64 pl-5 pr-20 w-full h-full bg-black bg-opacity-35 ">
                <p class="text-4xl">Pucuk Merah</p>
                <i class="text-lg font-normal">Syzygium Myrtifolium</i>
                <p class="text-sme font-normal">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consectetur molestias debitis dolore, rerum magni fugiat sed illo repudiandae aliquid voluptatem.</p>
            </div>
            <a href="#main" class="absolute bottom-0 left-1/2 transform -translate-x-1/2 animate-bounce">
                <ChevronDown size="48" />
            </a>
        </div>
    </div>

    <div id="main" class="p-5 text-justify flex flex-col gap-y-5">
        <div>
            Pucuk merah atau daun pucuk merah (Syzygium Myrtifolium) adalah spesies tumbuhan yang dikenal sebagai tanaman hias yang berasal dari genus Syzygium, famili Myrtaceae. Warna tunas daun yang baru muncul memiliki warna merah menyala sehingga tumbuhan ini memiliki sebutan Pucuk Merah. Warna daun akan berubah perlahan menjadi hijau seiring berjalannya waktu.Pucuk merah adalah sejenis tanaman perdu yang biasanya dijadikan tanaman hias di pekarangan rumah, perkantoran dan sebagainya serta masih termasuk ke dalam family yang sama dengan tanaman cengkih. Bila diperhatikan, bentuk tajuk dan daunnya pun sangat menyerupai tanaman cengkih. Tumbuhan ini merupakan tanaman asli dari Bangladesh, Borneo, Jawa, semenanjung Malaya, Myanmar, Filipina, Sumatra, dan Thailand.
        </div>
        <div>
            <div class="font-bold">Klasifikasi dari tanaman Pucuk Merah:</div>
            <ul class="list-disc px-3">
                <li>Kingdom: Plantae</li>
                <li>Divisi: Tracheophyta</li>
                <li>Super divisi: magnoliophyta atau tumbuhan berbunga.</li>
                <li>Sub divisio: berbiji tertutup atau angiospermae.</li>
                <li>Kelas: magnoliopsida atau berkeping dua.</li>
                <li>Sub kelas: rosidae.</li>
                <li>Ordo: myrtale dan famili myrtaceae.</li>
                <li>Sub family: myrtoideae.</li>
                <li>Genus: Syzygium</li>
                <li>Spesies: Syzygium oleana.</li>
            </ul>
        </div>
        <div>
            Selain dimanfaatkan sebagai tanaman hias, ternyata tanaman pucuk merah memiliki manfaat lainnya seperti :
            <ul class="px-3 list-decimal">  
                <li>Menyerap Karbondioksida di Udara. Tanaman pucuk merah bisa menyerap karbondioksida pada udara jauh lebih besar ketimbang dengan tanaman lainnya. Hal ini sangat bermanfaat karena udara di sekitar rumah akan jauh lebih bersih serta segar.</li>
                <li>Menyimpan Cadangan Air di Musim Kemarau. Tanaman pucuk merah dapat menyerap air hujan dan menjadikan air hujan tersebut sebagai cadangan air ketika memasuki musim kemarau. Hal ini bisa terjadi karena struktur akar tunggang tanaman pucuk merah yang besar sehingga mampu menyerap dan menyimpan air dalam volume besar.</li>
                <li>Dapat Dijadikan Pewangi Ruangan. Tanaman pucuk merah mengandung minyak atsiri yang mana memiliki aroma yang khas sehingga tanaman pucuk merah dapat dijadikan pengharum ruangan. Agar aroma atsiri menyebar ke seluruh ruangan maka anda perlu meremas daun pucuk merah hingga hancur sehingga aromamya keluar dan dapat menyebar ke ruangan.</li>
                <li>Sebagai Pagar Tanaman Hidup. Tanaman pucuk merah apabila dirawat dengan benar maka bisa tumbuh hingga 7 meter dengan diameter mencapai 30 cm sehingga sangat cocok untuk dijadikan pagar tanaman hidup.</li>
                <li>Pewarna Makanan Alami. Warna daun tanaman pucuk merah yang orange kemeragan dapat dijadikan pewarna alami untuk makanan. Caranya pun sangat mudah yaitu daun pucuk merah harus direbus hingga air rebusannya berubah warna setelah itu air rebusan siap untuk dijadikan pewarna makanan yang tentunya alami.</li>
            </ul>
        </div>
        <div>
            Status konservasi pucuk merah (Syzygium oleana) adalah Least Concern (LC), yang berarti pohon ini tidak berisiko punah. Hal ini berdasarkan penilaian International Union for Conservation of Nature (IUCN) Red List, yang menunjukkan bahwa populasi pucuk merah masih stabil dan tidak terancam kepunahannya
        </div>
    </div>
</div>