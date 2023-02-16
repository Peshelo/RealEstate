<template>
  <div class="w-full max-md:p-5">
    <h1 class="text-4xl font-bold max-md:text-2xl">No 122 Emarald Hill, Harare</h1>
    <div class="text-gray-400 flex flex-row justify-between mb-5">
        <div>
        <label>Hosted by: PropertyMe</label>
        <label>4.5</label>
        <label>Reviews</label>
        </div>
       <div class="flex flex-row">
        <p class="m-2">Share</p>
        <p class="m-2">Like</p>
       </div>
    </div>
    <div class="grid grid-cols-2 gap-2 mx-20 max-md:grid-cols-1 max-md:mx-5">
        <img src="@/assets/images/house2.webp" alt="" class="rounded-lg h-full object-cover">
        <div class="grid grid-cols-2 gap-2 gap-y-1 object-cover h-full">
            <img src="@/assets/images/house5.webp" alt="" class="rounded-lg object-cover max-md:rounded">
            <img src="@/assets/images/house1.webp" alt="" class="rounded-lg object-cover max-md:rounded">
            <img src="@/assets/images/house3.webp" alt="" class="rounded-lg object-cover max-md:rounded">
            <img src="@/assets/images/house4.webp" alt="" class="rounded-lg object-cover max-md:rounded">
        </div>
    </div>
    <div class="flex flex-row mt-10">
        <!-- Contact Info -->
        <div class="contactinfo w-2/3 mx-20 max-md:mx-5 max-md:w-full">
<div class="flex flex-row justify-between">
    <div class="flex flex-col">
            <h1 class="text-2xl font-bold">No 122 Emarald Hill, Harare</h1>
            <p class="text-sm bg-red-200 text-red-400 p-1 px-3 rounded-lg w-fit">5 Rooms . Wifi . Borewater</p>
    </div>
    <img src="@/static/logo.png" alt="" class="rounded-4xl w-20 h-20 object-contain" srcset="">
</div>
<div class="border-t border-b p-2 py-5">
    <div class="flex flex-row items-center py-2">
    <img src="@/static/logo.png" alt="" class="rounded-4xl w-20 h-20 object-contain" srcset="">
    <div class="flex flex-col">
        <h1 class="text-xl font-bold">Great for remote work</h1>
        <p class="text-md text-gray-400">Fast wifi at 540 Mbps, plus a dedicated workspace in a common area.</p>
    </div>
    </div>
    <div class="flex flex-row items-center py-2">
    <img src="@/static/logo.png" alt="" class="rounded-4xl w-20 h-20 object-contain" srcset="">
    <div class="flex flex-col">
        <h1 class="text-xl font-bold">Great for remote work</h1>
        <p class="text-md text-gray-400">Fast wifi at 540 Mbps, plus a dedicated workspace in a common area.</p>
    </div>
    </div>
    <div class="flex flex-row items-center py-2">
    <img src="@/static/logo.png" alt="" class="rounded-4xl w-20 h-20 object-contain" srcset="">
    <div class="flex flex-col">
        <h1 class="text-xl font-bold">Great for remote work</h1>
        <p class="text-md text-gray-400">Fast wifi at 540 Mbps, plus a dedicated workspace in a common area.</p>
    </div>
    </div>

</div>
<div class="mt-5">
    <h1 class="text-black text-xl">About Property</h1>
    <p class="text-sm text-gray-400 text-justify">Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium corrupti eaque error maxime, nulla nostrum similique voluptates neque, impedit facere asperiores magnam itaque laborum veritatis nemo aliquam? Repellendus, ut adipisci? Lorem ipsum dolor sit, amet consectetur adipisicing elit. Aperiam et soluta ab veniam aliquam, quod accusantium repellat voluptates fugiat at consequatur dolore animi odit adipisci blanditiis quae nulla beatae voluptatem?</p>
</div>
<div class="mt-5">
    <h1 class="text-black text-xl">What this place offers</h1>
    <ul class="text-sm text-gray-400 grid grid-cols-4 gap-3">
        <li>Wifi</li>
        <li>Wifi</li>
        <li>Wifi</li>
        <li>Wifi</li>
        <li>Wifi</li>
    </ul>
</div>
<div class="mt-5">
    <h1 class="text-black text-xl">More Infomation</h1>
    <Table/>h
</div>
<div>
    <Map/>
</div>

        </div>
        <!-- Ending Contact Info -->
        <!-- <div class="sticky contact w-1/3 border rounded-lg p-5 flex flex-col shadow-lg h-fit">
      <ContactForm/>
        </div> -->
    </div>
  </div>
</template>

<script>
import ContactForm from './ContactForm.vue'
import Table from './Table.vue'
import Map from './Map.vue'

export default {
components:{
    Table,
    ContactForm,
    Map
}
}
</script>

<style>

</style>