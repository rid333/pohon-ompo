<script>
    import Ketapang from '$lib/assets/ketapang.jpg';
    import { ChevronDown } from 'lucide-svelte';
</script>

<div class="flex flex-col gap-y-2">
    <div class="flex flex-col gap-y-2">
        <div class="flex flex-col text-white font-bold relative">
            <img class="w-screen h-screen object-cover" src={Ketapang} alt="Mangga">
            <div class="absolute pt-64 pl-5 pr-20 w-full h-full bg-black bg-opacity-35 ">
                <p class="text-4xl">Ketapang</p>
                <i class="text-lg font-normal">Terminalia Catappa</i>
                <p class="text-sme font-normal">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consectetur molestias debitis dolore, rerum magni fugiat sed illo repudiandae aliquid voluptatem.</p>
            </div>
            <a href="#main" class="absolute bottom-0 left-1/2 transform -translate-x-1/2 animate-bounce">
                <ChevronDown size="48" />
            </a>
        </div>
    </div>

    <div id="main" class="p-5 text-justify flex flex-col gap-y-5">
        <div>
            Ketapang atau katapang (Terminalia Catappa) adalah nama sejenis pohon tepi pantai yang rindang. Lekas tumbuh dan membentuk tajuk indah bertingkat-tingkat, ketapang kerap dijadikan pohon peneduh di taman-taman dan tepi jalan. Ketapang merupakan tumbuhan asli Asia Tenggara dan umum ditemukan di wilayah ini, kecuali di Sumatra dan Kalimantan yang agak jarang didapati di alam. Pohon ini biasa ditanam di Australia bagian utara dan Polinesia; demikian pula di India, Pakistan, Madagaskar, Afrika Timur dan Afrika Barat, Amerika Tengah, serta Amerika Selatan.
        </div>
        <div>
            <div class="font-bold">Klasifikasi dari tanaman Ketapang:</div>
            <ul class="list-disc px-3">
                <li>Kingdom: Plantae</li>
                <li>Kingdom: Plantae</li>
                <li>Sub-kingdom: Magnoliophyta</li>
                <li>Kelas: Magnoliopsida</li>
                <li>Sub-kelas: Rosidae</li>
                <li>Ordo: Myrtales</li>
                <li>Famili: Combretaceae</li>
                <li>Genus: Terminalia</li>
                <li>Spesies: Terminalia catappa</li>
            </ul>
        </div>
        <div>
            Daun ketapang dimanfaatkan orang untuk menyamak kulit, sebagai bahan pewarna hitam, dan juga untuk membuat tinta. Daun ketapang populer di kalangan penggemar ikan hias bahwa menaruh daun-daun ketapang kering di akuarium, khususnya ikan cupang (Betta spp.), dapat memperbaiki kesehatan dan memperpanjang umur ikan. Daun ketapang dapat menurunkan kadar Ph air, menyerap racun dalam air, mencerahkan warna ikan cupang dan juga mengobati luka pada ikan cupang setelah pemijahan.
        </div>
        <div>
            Biji ketapang dapat dimakan mentah atau dimasak, konon lebih enak dari biji kenari, dan digunakan sebagai pengganti biji amandel (almond) dalam kue-kue. Inti bijinya yang kering jemur menghasilkan minyak berwarna kuning hingga setengah dari bobot semula. 
        </div>
        <div>
            Pohon ketapang mempunyai beragam manfaat dan kegunaan dari segi ekologis (lingkungan), sosial dan kesehatan. Ketapang dapat dimanfaatkan untuk mendukung kehidupan manusia.
        </div>
        <div>
            Manfaat ketapang yang paling umum adalah sebagai pohon peneduh di jalanan atau di taman. Sebab ketapang dapat tumbuh besar dan bentuk kanopinya sepeti payung lebar. Sehingga cukup rindang dan memberikan kesan teduh.Tapi saat musim kemarau, pohon ketapang akan menggugurkan banyak daun, yang terkadang membuat lingkungan sekitar pohon tumbuh menjadi kotor. Ketapang memiliki sistem akar tunggang yang mampu menahan erosi dan pergerakan tanah di pegunungan dan pesisir pantai. Namun, akarnya yang kuat juga dapat merusak konstruksi jalanan dan bangunan.
        </div>
        <div>
            Menurut International Union for Conservation of Nature (IUCN) Red List, ketapang berstatus Least Concern (LC). Artinya, pohon ketapang termasuk jenis flora yang aman dan tidak terancam kepunahannya. Status LC ditetapkan pada tahun 2018 dan telah diperbarui pada tahun 2019. Karena jumlah populasi ketapang masih stabil. Hal ini seimbang dengan tingkat persebaran tumbuhan ini yang hampir dapat ditemui di seluruh dunia.
        </div>
    </div>
</div>