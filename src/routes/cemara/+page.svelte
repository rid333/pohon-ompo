<script>
    import { ChevronDown } from 'lucide-svelte';
</script>

<div class="flex flex-col gap-y-2">
    <div class="flex flex-col gap-y-2">
        <div class="flex flex-col text-white font-bold relative">
            <img class="w-screen h-screen object-cover" src="https://www.smpn2cisaga.sch.id/upload/imagecache/48406315Tehnik-MENYETEK-Cemara-Norfolk-500x500.jpg" alt="Mangga">
            <div class="absolute pt-64 pl-5 pr-20 w-full h-full bg-black bg-opacity-35 ">
                <p class="text-4xl">Tanaman Cemara</p>
                <i class="text-lg font-normal">Casuarinaceae</i>
                <p class="text-sme font-normal">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consectetur molestias debitis dolore, rerum magni fugiat sed illo repudiandae aliquid voluptatem.</p>
            </div>
            <a href="#main" class="absolute bottom-0 left-1/2 transform -translate-x-1/2 animate-bounce">
                <ChevronDown size="48" />
            </a>
        </div>
    </div>

    <div id="main" class="p-5 text-justify flex flex-col gap-y-5">
        <div>
            Tanaman cemara merupakan tanaman yang cukup artistik, yang terbentuk dari gaya seni jepang bernama bonsai. Hal inilah mengapa pohon cemara juga seringkali digunakan dalam perayaan tertentu, salah satunya perayaan natal yang biasanya diikuti dengan berbagai macam hiasan ornamen pada pohonnya dan digunakan sebagai dekorasi untuk mempercantik suatu ruangan
        </div>
        <div>
            Tanaman cemara juga merupakan tanaman yang evergreen dimana daun-daun tanaman tersebut sangat jarang mengering dan rontok terlebih ketika musim gugur tiba.
        </div>
        <div>
            Tanaman cemara juga merupakan tanaman yang usianya bisa mencapai ratusan bahkan ribuan tahun. Tanaman cemara tersebar dibelahan bumi bagian selatan seperti Amerika Selatan, Afrika Selatan, Australia hingga Selandia Baru, di wilayah khatulistiwa, pohon cemara bisa ditemukan salah satunya di Indonesia. Tanaman cemara masuk dalam kelompok tanaman berbiji atau yang biasa dikenal dengan spermatophyte.
        </div>
        <div>
            <div class="font-bold">Klasifikasi dari tanaman Cemara:</div>
            <ul class="list-disc px-3">
                <li>Kingdom (Kerajaan): Plantae</li>
                <li>Division (Divisi : Magnoliophyta</li>
                <li>Class (Kelas : Magnoliopsida</li>
                <li>Ordo : Fagales</li>
                <li>Family : Casuarinaceae</li>
            </ul>
        </div>
        <div>
            Keberadaan pohon cemara dapat memberikan kontribusi positif dalam menjaga keseimbangan ekosistem. Cemara juga punya nilai ekonomi yang bisa dimanfaatkan oleh manusia.
        </div>
        <div>
            Berikut ini adalah beberapa manfaat pohon cemara untuk lingkungan yang perlu Anda ketahui : 
            <ul class="list-decimal px-3">
                <li> Menciptakan habitat makhluk hidup. Pohon ini menyediakan tempat berlindung dan makanan untuk makhluk hidup, seperti burung, serangga, mamalia, dan satwa lain, sehingga mendukung keanekaragaman hayati dan ekosistem yang sehat.</li>
                <li>Menyerap karbon dioksida. Cemara membantu menyaring udara dengan menyerap karbon dioksida dan melepaskan oksigen. Hal ini akan berkontribusi pada kualitas udara yang lebih baik.</li>
                <li>Mencegah erosi tanah. Berbekal akar tunggang yang strukturnya kuat, pohon cemara dapat membantu mencegah erosi dengan menjaga kepadatan tanah serta menahan air di dalamnya.</li>
                <li>Menahan angin. Pohon cemara banyak ditanam di sekitar kawasan pegunungan untuk mengurangi kecepatan angin. Hal ini membantu melindungi tanaman dan infrastruktur dari kerusakan akibat terpaan angin kencang.</li>
                <li>Menghias pekarangan. Cemara kerap menjadi pilihan tanaman untuk menghias taman atau pekarangan rumah. Pohon cemara juga sering digunakan sebagai dekorasi dalam perayaan Natal.</li>
                <li>Sumber bahan bakar. Kayu cemara memiliki tekstur padat, mudah terbakar, dan tidak menimbulkan banyak asap sehingga dapat dijadikan sebagai sumber kayu bakar bagi beberapa masyarakat Indonesia.</li>
            </ul>
        </div>
    </div>
</div>