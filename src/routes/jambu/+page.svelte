<script>
    import Jambu from '$lib/assets/jambu.jpg';
    import { ChevronDown } from 'lucide-svelte';
</script>

<div class="flex flex-col gap-y-2">
    <div class="flex flex-col gap-y-2">
        <div class="flex flex-col text-white font-bold relative">
            <img class="w-screen h-screen object-cover" src={Jambu} alt="Mangga">
            <div class="absolute pt-64 pl-5 pr-20 w-full h-full bg-black bg-opacity-35 ">
                <p class="text-4xl">Pohon Jambu Biji</p>
                <i class="text-lg font-normal">Psidium Guajava</i>
                <p class="text-sme font-normal">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consectetur molestias debitis dolore, rerum magni fugiat sed illo repudiandae aliquid voluptatem.</p>
            </div>
            <a href="#main" class="absolute bottom-0 left-1/2 transform -translate-x-1/2 animate-bounce">
                <ChevronDown size="48" />
            </a>
        </div>
    </div>

    <div id="main" class="p-5 text-justify flex flex-col gap-y-5">
        <div>
            Jambu biji (Psidium guajava) atau sering disebut jambu biji, jambu siki dan jambu klutuk merupakan tanaman tropis asli Brazil, tersebar luas di Indonesia melalui Thailand.
        </div>
        <div>
            <div class="font-bold">Klasifikasi dari tanaman Jambu Biji:</div>
            <ul class="list-disc px-3">
                <li>Kingdom: Plantae</li>
                <li>Subkingdom: Tracheobionta</li>
                <li>Super Divisi: Spermatophyta</li>
                <li>Divisi: Magnoliophyta</li>
                <li>Kelas: Magnoliopsida</li>
                <li>Subkelas: Rosidae</li>
                <li>Ordo: Myrtales</li>
                <li>Famili: Myrtaceae</li>
                <li>Genus: Psidium</li>
                <li>Spesies: Psidium Guava</li>
            </ul>
        </div>
        <div>
            Daun jambu biji (Psidium guajava L.) mengandung berbagai senyawa metabolit sekunder. Antara lain, tanin, minyak asiri, flavonoid, dan saponin. Senyawa-senyawa tersebut berpotensi sebagai antioksidan dan bahan pengawet alami. Daun jambu biji dikenal sebagai bahan obat tradisional untuk batuk dan diare. Jus jambu biji "bangkok" juga dianggap berkhasiat untuk membantu penyembuhan penderita demam berdarah dengue. Daun jambu biji sudah dikenal sejak dahulu sebagai pencegah dan mengurangi diare. 3 helai daun jambu biji direbus dengan 2 gelas air putih lalu direbus, lalu disaring dan diminumkan pada orang yang terkena diare.
        </div>
        <div>
            Buah jambu biji mengandung banyak vitamin dan serat sehingga cocok dikonsumsi untuk menjaga kesehatan. Warna daging jambu biji yang merah mengindikasikan jambu biji kaya akan vitamin A untuk kesehatan mata dan antioksidan. Buah jambu biji cocok dikonsumsi di siang hari karena buahnya segar dan mendinginkan badan.
        </div>
        <div>
            Status konservasi jambu biji (Psidium guajava) adalah risiko rendah. Ini berdasarkan penilaian dari International Union for Conservation of Nature (IUCN)
        </div>
    </div>
</div>