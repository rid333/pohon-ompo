<script>
    import Mangga from '$lib/assets/mangga.jpg';
    import { ChevronDown } from 'lucide-svelte';
</script>

<div class="flex flex-col gap-y-2">
    <div class="flex flex-col gap-y-2">
        <div class="flex flex-col text-white font-bold relative">
            <img class="w-screen h-screen object-cover" src={Mangga} alt="Mangga">
            <div class="absolute pt-64 pl-5 pr-20 w-full h-full bg-black bg-opacity-35 ">
                <p class="text-4xl">Ara Jejawi</p>
                <i class="text-lg font-normal">Ficus retusa</i>
                <p class="text-sme font-normal">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consectetur molestias debitis dolore, rerum magni fugiat sed illo repudiandae aliquid voluptatem.</p>
            </div>
            <a href="#main" class="absolute bottom-0 left-1/2 transform -translate-x-1/2 animate-bounce">
                <ChevronDown size="48" />
            </a>
        </div>
    </div>

    <div id="main" class="p-5 text-justify flex flex-col gap-y-5">
        <div>
            Ara Jejawi (Ficus Retusa) dan dalam bahasa bugis dikenal dengan istilah kajuara adalah spesies tumbuhan dalam genus Ficus, asli Kepulauan Melayu dan wilayah floristik Malesia. Ficus retusa tumbuh sebagai semak atau pohon besar dengan tajuk lebar, yang dapat mencapai ketinggian 10 meter.[5] Kulit batangnya halus, berwarna putih atau abu-abu muda, dengan diameter mencapai 1 meter. Daunnya berbentuk bulat telur yang biasanya memiliki panjang lebih dari 10 cm dan tersusun secara spiral. Buahnya berdiameter sekitar 1 cm, dan muncul di ujung cabang.
        </div>
        <div>
            <div class="font-bold">Klasifikasi dari tanaman Ara Jejawi:</div>
            <ul class="list-disc px-3">
                <li>Kingdom: Plantae</li>
                <li>Divisi: Tracheophyta</li>
                <li>Ordo: Rosales</li>
                <li>Famili: Moraceae</li>
                <li>Genus: Ficus</li>
                <li>Spesies: Ficus Retusa</li>
            </ul>
        </div>
        <div>
            Pohon mangga (Mangifera indica) memiliki berbagai fungsi ekologis yang penting bagi kenyamanan manusia dan lingkungan. Berikut adalah beberapa fungsi ekologis utamanya: 
            <ul class="px-3 list-decimal">  
                <li>Penyediaan Oksigen: Pohon mangga, seperti pohon lainnya, menghasilkan oksigen melalui proses fotosintesis. Ini sangat penting untuk kualitas udara di sekitar manusia.</li>
                <li>Penyerapan Karbon Dioksida: Pohon mangga menyerap karbon dioksida dari atmosfer, membantu mengurangi efek rumah kaca dan mengontrol kadar karbon dioksida di udara.</li>
                <li>Habitat Hewan: Pohon mangga menyediakan habitat bagi berbagai jenis hewan, termasuk burung, serangga, dan mamalia. Ini meningkatkan keragaman hayati di sekitar pohon.</li>
                <li>Pengendalian Erosi: Akar pohon mangga dapat menahan tanah dari erosi, mencegah terjadinya banjir dan meningkatkan kesuburan tanah.</li>
                <li>Penyediaan Tempat Tinggal: Pohon mangga dapat menjadi tempat tinggal bagi berbagai jenis hewan, seperti burung yang membuat sarang di celah-celah batang dan cabang pohon.</li>
                <li>Penyediaan Makanan: Buah mangga yang matang menjadi sumber makanan bagi berbagai hewan, seperti monyet, burung, dan serangga.</li>
            </ul>
        </div>
        <div>
            Tanaman Beringin ini mempunyai sebuah perakaran yang dalam serta banyak, hal tersebut mempunyai dampak positif yaitu untuk menambah titik mata air seiring dengan akan bertambahnya umur pohon. Beberapa jenis pohon beringin bisa digunakan untuk bisa mempertahankan kelestarian mata air, mengurangi erosi, serta tanah longsor..
        </div>
        <div>
            Pohon Beringin ini juga mampu untuk mengurangi proses dari penguapan yang akan terjadi di dalam tanah maupun yang ada di dalam pohonnya itu sendiri. Hal tersebut akan mengakibatkan Pohon Beringin bisa menjaga ketersediaan air yang biasanya terdapat di lingkungan sekitarnya. Buah dari tanaman beringin itu sendiri mempunyai kandungan saponin, flavonoid, dan polifenol.
        </div>
        <div>
            Pohon beringin (Ficus benjamina) memiliki berbagai cerita mistis yang berkembang di berbagai daerah di Indonesia seperti pohon beringin sering dianggap sebagai tempat tinggal makhluk halus. Hal ini membuat banyak orang enggan menanam pohon beringin, meskipun pohon ini memiliki manfaat kesehatan, seperti mengobati bronkitis. Selain itu pohon beringin dijadikan sebagai filosofi dan simbolisme. Pohon beringin memiliki filosofi yang melambangkan "manunggaling kawula Gusti" atau "bersatunya manusia dengan Tuhannya". Akar gantungnya yang menjuntai ke bawah ke permukaan tanah melambangkan bahwa manusia harus selalu mengingat asal usulnya, bahwa manusia diciptakan Tuhan dari tanah.
        </div>
        <div>
            Status konservasi pohon beringin (Ficus retusa) adalah Least Concern (LC), yang berarti pohon ini tidak berisiko punah. Hal ini berdasarkan penilaian International Union for Conservation of Nature (IUCN) dan beberapa studi lainnya yang menunjukkan bahwa pohon beringin memiliki populasi yang cukup stabil dan tidak terancam punah dalam jangka pendek
        </div>
    </div>
</div>