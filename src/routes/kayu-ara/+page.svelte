
<script>
    import { ChevronDown } from 'lucide-svelte';
</script>

<div class="flex flex-col gap-y-2">
    <div class="flex flex-col gap-y-2">
        <div class="flex flex-col text-white font-bold relative">
            <img class="w-screen h-screen object-cover" src="https://lindungihutan.com/blog/wp-content/uploads/2022/11/Foto-pohon-ara.png" alt="Mangga">
            <div class="absolute pt-64 pl-5 pr-20 w-full h-full bg-black bg-opacity-35 ">
                <p class="text-4xl">Kayu Ara</p>
                <i class="text-lg font-normal">Ficus Sp</i>
                <p class="text-sme font-normal">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consectetur molestias debitis dolore, rerum magni fugiat sed illo repudiandae aliquid voluptatem.</p>
            </div>
            <a href="#main" class="absolute bottom-0 left-1/2 transform -translate-x-1/2 animate-bounce">
                <ChevronDown size="48" />
            </a>
        </div>
    </div>

    <div id="main" class="p-5 text-justify flex flex-col gap-y-5">
        <div>
            Ficus (kayu ara) atau yang biasa disebut beringin adalah salah satu jenis tumbuhan dari famili moraceae (nangka-nangkaan) dan merupakan marga terbesar dalam famili ini. Masyarakat lokal biasa mengenalnya dengan sebutan “kayu ara” dan ada pula yang menyebutnya “beringin”. Ficus memiliki beragam habitus (bentuk hidup) diantaranya berupa pohon, semak, epifit dan pencekik. Menurut Berg (2005) Ficus umumnya tersebar didaerah tropis, setidaknya tercatat 735 spesies di seluruh Dunia, dan di Kalimantan tercatat mencapai 141 spesies. Beberapa jenis Ficus diantaranya adalah Ficus benjamina, Ficus racemosa, Ficus variegata, Ficus dubia, Ficus uncinata, Ficus sundaica, Ficus punctata, Ficus xylophylla, Ficus deltoidea, Ficus stupenda, Ficus rosulata  dan Ficus hemsleyana.
        </div>
        <div>
            Ficus merupakan tumbuhan yang memiliki kemampuan hidup dan adaptasi yang baik pada berbagai tipe habitat mulai dari hutan dataran rendah sampai dataran tinggi. Keberadaan Ficus juga disebut sebagai tumbuhan pioneer (perintis), sehingga pada hutan alami dapat digunakan sebagai indikator proses terjadinya suksesi hutan. Maka dari itu, sangat penting untuk mengenal dan mempelajari spesies kunci yang satu ini dalam upaya konservasi.
        </div>
    </div>
</div>