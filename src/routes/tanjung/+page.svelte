<script>
    import Tanjung from '$lib/assets/tanjung.jpg';
    import { ChevronDown } from 'lucide-svelte';
</script>

<div class="flex flex-col gap-y-2">
    <div class="flex flex-col gap-y-2">
        <div class="flex flex-col text-white font-bold relative">
            <img class="w-screen h-screen object-cover" src={Tanjung} alt="Mangga">
            <div class="absolute pt-64 pl-5 pr-20 w-full h-full bg-black bg-opacity-35 ">
                <p class="text-4xl">Pohon Tanjung</p>
                <i class="text-lg font-normal">Mimusops Elengi</i>
                <p class="text-sme font-normal">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consectetur molestias debitis dolore, rerum magni fugiat sed illo repudiandae aliquid voluptatem.</p>
            </div>
            <a href="#main" class="absolute bottom-0 left-1/2 transform -translate-x-1/2 animate-bounce">
                <ChevronDown size="48" />
            </a>
        </div>
    </div>

    <div id="main" class="p-5 text-justify flex flex-col gap-y-5">
        <div>
            Pohon tanjung (Mimusops Elengi) adalah sejenis pohon yang berasal dari India, Sri Lanka, dan Burma dan telah masuk ke Nusantara sejak berabad-abad yang silam. Pohon ini memiliki bunga yang harum dan sering digunakan sebagai bahan dalam industri parfum dan kosmetik. Selain itu, kayu tanjung juga digunakan sebagai bahan konstruksi dan ukiran karena kekuatan dan keindahannya.
        </div>
        <div>
            <div class="font-bold">Klasifikasi dari tanaman Tanjung:</div>
            <ul class="list-disc px-3">
                <li>Kingdom: Plantae (Tumbuhan)</li>
                <li>Subkingdom: Tracheobionta (Tumbuhan berpembuluh)</li>
                <li>Super Divisi: Spermatophyta (Menghasilkan biji)</li>
                <li>Divisi: Magnoliophyta</li>
                <li>Kelas: Magnoliopsida</li>
                <li>Subkelas: Dilleniidae</li>
                <li>Ordo: Ebenales</li>
                <li>Famili: Sapotaceae</li>
                <li>Genus: Mimusops</li>
                <li>Spesies: M. Elengi</li>
            </ul>
        </div>
        <div>
            Di Indonesia, pohon tanjung dapat ditemukan di berbagai daerah seperti Jawa, Sumatra, Kalimantan, Sulawesi, dan Bali. Pohon tanjung biasanya dimanfaatkan sebagai pohon peneduh pinggir jalan raya, taman, hutan kota, pekarangan, serta lingkungan sarana umum lainnya. Masyarakat Jawa mengagungkan pohon tanjung sama halnya dengan pohon beringin. Hal ini terjadi karena dalam etimologi Jawa, makna kata tanjung berarti menjunjung tinggi ajaran agama.
        </div>
        <div>
            Pohon tanjung memiliki berbagai manfaat di setiap bagiannya. Bunga pada pohon tanjung, dapat dikumpulkn untuk mengharumkan pakaian, ruangan atau untuk hiasan. Bunga ini, dan aneka bagian tumbuhan lainnya, juga memiliki khasiat obat. Buahnya dapat dimakan.
        </div>
        <div>
            Kulit kayu pada pohon ini dapat digunakan sebagai obat penguat dan obat demam dengan cara di rebus. Rebusan pepagan beserta bunganya digunakan untuk mengatasi murus yang disertai demam. Daun segar yang digerus halus digunakan sebagai tapal obat sakit kepala; daun yang dirajang sebagaimana tembakau, dicampur sedikit serutan kayu secang dan dilinting dengan daun pisang, digunakan sebagai rokok untuk mengobati seriawan mulut.
        </div>
        <div>
            Status konservasi pohon tanjung (Mimusops elengi) menurut International Union for Conservation of Nature (IUCN) Red List. Pohon ini memiliki populasi yang stabil dan tidak berisiko punah dalam jangka pendek
        </div>
    </div>
</div>