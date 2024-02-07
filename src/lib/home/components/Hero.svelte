<script>
    import Icon from "@iconify/svelte";
    import Image from "../../../assets/illus1.svg";
</script>

<div class="mt-32 gap-12 flex items-center justify-center px-20 text-slate-700">
    <div class="text-center w-7/12">
        <p class="font-medium text-5xl mb-4 leading-tight">
            Buy And Sell your E-books for the best price
        </p>
        <p class="text-lg">
            Upload, Buy and Sell Your E-Book And Make Money on this website
        </p>
        <form action="" method="get" class="inline-flex items-center gap-2 p-1 mt-8 rounded-full border border-slate-300">
            <Icon icon="uil:search" width="48" height="48" class="ml-4 text-slate-300" />
            <input type="search" class="rounded-full py-4 w-full focus:outline-none placeholder-slate-400"
                placeholder="Search E-book" id="mysearchbar">
            <button class="py-4 px-12 rounded-full text-white bg-green-500">Search</button>
        </form>
    </div>
    <img src={Image} alt="" class="img-fluid" width="600" height="300">
 </div>