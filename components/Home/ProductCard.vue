<template>
  <div class="flex flex-col border border-gray-200 rounded-2xl hover:shadow-lg duration-300 max-md:flex-row max-md:h-fit">
    <div class="object-cover hover:opacity-90 duration-300 max-md:w-1/2">
        <img src="@/assets/images/house2.webp" class="rounded-t-lg h-64 object-cover max-md:h-full max-md:rounded-none max-md:rounded-l-md" alt="">
    </div>
    <div class="p-2 max-md:h-fit max-md:p-1">
        <p class="text-gray-300 text-sm">Renting</p>
        <div class="flex flex-row justify-between text-lg font-medium"><p>Emarald Hill, Harare</p><label>4.6</label></div>
        <p class="text-[var(--primary)] font-semibold text-lg">$145</p>
        <div class="flex flex-row mt-2">
            <label class="tags bg-green-100 text-green-300 p-2 rounded-lg py-1 px-2 mx-1">Wifi</label>
            <label class="tags bg-green-100 text-green-300 p-2 rounded-lg py-1 px-2 mx-1">Wifi</label>
            <label class="tags bg-green-100 text-green-300 p-2 rounded-lg py-1 px-2 mx-1">Wifi</label>
            <label class="tags bg-green-100 text-green-300 p-2 rounded-lg py-1 px-2 mx-1">Wifi</label>
        </div>
        <p class="text-red-300 text-sm mt-2">Host: ProperyMeme</p>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.tags{
    font-size: 12px;
}
</style>