<script>
    import Mangga from '$lib/assets/mangga.jpg';
    import { ChevronDown } from 'lucide-svelte';

</script>

<div class="flex flex-col gap-y-2">
    <div class="flex flex-col gap-y-2">
        <div class="flex flex-col text-white font-bold relative">
            <img class="w-screen h-screen object-cover" src={Mangga} alt="Mangga">
            <div class="absolute pt-64 pl-5 pr-20 w-full h-full bg-black bg-opacity-35 ">
                <p class="text-4xl">Pohon Mangga</p>
                <i class="text-lg font-normal">Mangifera indica</i>
                <p class="text-sm font-normal">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consectetur molestias debitis dolore, rerum magni fugiat sed illo repudiandae aliquid voluptatem.</p>
            </div>
            <a href="#main" class="absolute bottom-0 left-1/2 transform -translate-x-1/2 animate-bounce">
                <ChevronDown size="48" />
            </a>
        </div>
    </div>

    <div id="main" class="p-5 text-justify flex flex-col gap-y-5">
        <div>
            Mangga merupakan salah satu tanaman yang biasanya disebut sebagai mempelam 
            atau nama ilmiahnya ialah Mangifera indica. Nama tersebut merupakan salah satu 
            nama yang sekaligus dengan pohonnya. Mangga menjadi salah satu tanaman yang bermarga 
            Mangifera terdiri atas 35 sampai 40 anggota serta suku Anacardiaceae. Tanaman manga 
            ini berasal dari India dan juga Burma yang telah tersebar pada Asia Tenggara kira-kira 
            1500 tahun yang lalu. Pada umumnya budidaya tanaman mangga banyak ditanamn di daerah 
            tropis, bahkan tak salah kalau mangga bertumbuh subur di negara Indonesia. Tanaman 
            mangga tersebut memiliki jenis-jenis buah yang berbeda rasanya.
        </div>
        <div>
            <div class="font-bold">Klasifikasi dari tanaman Mangga:</div>
            <ul class="list-disc px-3">
                <li>Kingdom: Plantae</li>
                <li>Infra Kingdom: Streptophyta</li>
                <li>Sub Kingdom: Viridiplantae</li>
                <li>Divisi: Tracheophyta</li>
                <li>Super Divisi: Embryophyta</li>
                <li>Sub Divisi: Spermatophytina</li>
                <li>Kelas: Magnoliopsida</li>
                <li>Ordo: Sapindales</li>
                <li>Super Ordo: Rosanae</li>
                <li>Famili: Anacardiaceae</li>
                <li>Genus: Mangifera L</li>
                <li>Spesies:  Mangifera Indica</li>
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
            Buah mangga (Mangifera indica) memiliki berbagai manfaat ekonomis yang signifikan. Berikut adalah beberapa manfaat ekonomis utamanya:
            <ul class="list-disc px-3">
                <li>Nilai Ekonomi Tinggi: Mangga memiliki nilai ekonomi yang tinggi, yang dapat meningkatkan pendapatan petani dan menguntungkan para pedagang. Ini disebabkan oleh permintaan yang tinggi dan harga yang kompetitif di pasar internasional.</li>
                <li>Produksi Berkelanjutan: Peningkatan produktivitas mangga dapat meningkatkan produksi dan mengurangi ketergantungan pada impor. Ini penting untuk memastikan keamanan pangan dan stabilitas ekonomi.</li>
                <li>Pengolahan Produk Olahan: Mangga dapat diolah menjadi berbagai produk seperti selai, manisan, sirup, permen, dan esen. Pengolahan ini tidak hanya memperpanjang masa simpan buah mangga tetapi juga meningkatkan nilai ekonominya</li>
            </ul>
        </div>
        <div>
            Status konservasi pohon mangga (Mangifera indica) adalah berisiko rendah. Mangga memiliki jenis yang cukup banyak, dan Mangifera indica sendiri masuk kategori jenis mangga yang berisiko rendah.
        </div>
    </div>

    <swiper-container
        slides-per-view={1}
        space-between=10
        centered-slides={true}
        autoplay={{
            delay:10000,
            disableOnInteraction: false,
        }}
        pagination={{
            clickable: true,
        }}
        navigation={{
            clickable: true,
        }}
        breakpoints={{
            640: {
                slidesPerView: 1,
                spaceBetween: 20,
            },
            768: {
                slidesPerView: 2,
                spaceBetween: 40,
            },
            1024: {
                slidesPerView: 3,
                spaceBetween: 50,
            },
        }}
        effect='fade'
    >
        <swiper-slide>
            <img class="w-screen h-screen object-cover" src={Mangga} alt="Mangga">
        </swiper-slide>
        <swiper-slide>
            <img class="w-screen h-screen object-cover" src="https://akcdn.detik.net.id/visual/2021/10/12/tanaman-buah-mangga_169.jpeg?w=650" alt="Mangga">
        </swiper-slide>
        <swiper-slide>
            <img class="w-screen h-screen object-cover" src="https://www.blibli.com/friends-backend/wp-content/uploads/2023/08/B700524-Cover-Panduan-Merawat-Tanaman-Pohon-Mangga.jpg" alt="Mangga">
        </swiper-slide>
    </swiper-container>
</div>