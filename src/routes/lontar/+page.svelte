<script>
    import Lontar from '$lib/assets/lontar.jpg';
    import { ChevronDown } from 'lucide-svelte';
</script>

<div class="flex flex-col gap-y-2">
    <div class="flex flex-col gap-y-2">
        <div class="flex flex-col text-white font-bold relative">
            <img class="w-screen h-screen object-cover" src={Lontar} alt="Mangga">
            <div class="absolute pt-64 pl-5 pr-20 w-full h-full bg-black bg-opacity-35 ">
                <p class="text-4xl">Tanaman Lontar</p>
                <i class="text-lg font-normal">Borassus Flabellifer</i>
                <p class="text-sme font-normal">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consectetur molestias debitis dolore, rerum magni fugiat sed illo repudiandae aliquid voluptatem.</p>
            </div>
            <a href="#main" class="absolute bottom-0 left-1/2 transform -translate-x-1/2 animate-bounce">
                <ChevronDown size="48" />
            </a>
        </div>
    </div>

    <div id="main" class="p-5 text-justify flex flex-col gap-y-5">
        <div>
            anaman Lontar (Borassus Flabellifer), yang juga dikenal sebagai siwalan, merupakan pohon yang banyak tumbuh di daerah kering di Indonesia dan beberapa negara di Asia Tenggara. Tanaman Lontar dapat ditemukan secara luas di berbagai wilayah di Indonesia. Tanaman ini tumbuh subur di daerah-daerah kering, seperti di Madura, Jawa, Bali, Nusa Tenggara, dan Sulawesi. Di luar negeri, penyebaran Lontar juga tercatat di negara-negara seperti Australia, India, Papua Nugini, dan beberapa negara di Asia Tenggara.
        </div>
        <div>
            <div class="font-bold">Klasifikasi dari tanaman Lontar:</div>
            <ul class="list-disc px-3">
                <li>Kingdom: Plantae</li>
                <li>Divisi: Angiospermae</li>
                <li>Kelas: Monokotiledonae</li>
                <li>Ordo: Arealea</li>
                <li>Famili: Palmaceae</li>
                <li>Genus: Borassus</li>
                <li>Spesies: Borassus Flabellifer</li>
            </ul>
        </div>
        <div>
            Pohon lontar (Borassus flabellifer) memiliki berbagai manfaat untuk lingkungan, termasuk:
            <ul class="list-decimal px-3">
                <li>Sumber Air: Pohon lontar dapat menyimpan air dalam akar dan batangnya, yang sangat berguna untuk memenuhi kebutuhan air di daerah yang sering mengalami kekurangan air.</li>
                <li>Habitat Hewan: Pohon lontar menyediakan habitat bagi berbagai jenis hewan, seperti burung, serangga, dan hewan lainnya, yang menggunakan pohon ini sebagai tempat berlindung dan mencari makanan.</li>
                <li>Mengurangi Erosi: Akar pohon lontar dapat menahan erosi tanah, terutama di daerah yang sering mengalami angin kencang atau hujan deras.</li>
                <li>Mengurangi Pemanasan Global: Pohon lontar dapat menyerap karbon dioksida dari atmosfer, yang membantu mengurangi pemanasan global.</li>
                <li>Menghasilkan Oksigen: Pohon lontar menghasilkan oksigen melalui proses fotosintesis, yang sangat penting untuk kesehatan lingkungan.</li>
                <li>Mengurangi Polusi Udara: Pohon lontar dapat menyerap polutan seperti nitrogen oksida dan sulfur dioksida dari udara, yang membantu mengurangi polusi udara.</li>
                <li>Menghasilkan Bahan Bangunan: Kayu pohon lontar dapat digunakan sebagai bahan bangunan, seperti untuk membuat rumah, perabotan, dan perahu.</li>
                <li>Mengurangi Banjir: Akar pohon lontar dapat menahan banjir, terutama di daerah yang sering mengalami banjir.</li>
            </ul>
        </div>
        <div>
            Pohon lontar (Borassus flabellifer) tidak termasuk dalam kategori langka secara global. Namun, status konservasi pohon lontar dapat bervariasi di berbagai daerah di Indonesia, tergantung pada tingkat eksploitasi dan kondisi lingkungan setempat.
        </div>
    </div>
</div>