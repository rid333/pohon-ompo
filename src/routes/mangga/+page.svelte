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
                <p class="text-base font-normal">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consectetur molestias debitis dolore, rerum magni fugiat sed illo repudiandae aliquid voluptatem.</p>
            </div>
            <a href="#main" class="absolute bottom-0 left-1/2 transform -translate-x-1/2 animate-bounce">
                <ChevronDown size="48" />
            </a>
        </div>
    </div>

    <div id="main" class="p-5 text-justify">
        Mangga merupakan salah satu tanaman yang biasanya disebut sebagai mempelam 
        atau nama ilmiahnya ialah Mangifera indica. Nama tersebut merupakan salah satu 
        nama yang sekaligus dengan pohonnya. Mangga menjadi salah satu tanaman yang bermarga 
        Mangifera terdiri atas 35 sampai 40 anggota serta suku Anacardiaceae. Tanaman manga 
        ini berasal dari India dan juga Burma yang telah tersebar pada Asia Tenggara kira-kira 
        1500 tahun yang lalu. Pada umumnya budidaya tanaman mangga banyak ditanamn di daerah 
        tropis, bahkan tak salah kalau mangga bertumbuh subur di negara Indonesia. Tanaman 
        mangga tersebut memiliki jenis-jenis buah yang berbeda rasanya.
    </div>
</div>