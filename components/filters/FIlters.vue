<template>
  <div class="sticky bg-white py-2 flex flex-row items-center justify-center border-t border-b after:scroll-m-1:bg-red-200">
    <div class="flex flex-col my-4 mx-1">
        <label class="text-sm m-0 text-gray-500">Location:</label>  
        <div class="bg-white border border-gray-400 my-1  px-3 py-2 rounded-lg flex flex-row items-center">
            <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px"
width="20" height="20"
viewBox="0 0 50 50">
<path d="M 21 3 C 11.621094 3 4 10.621094 4 20 C 4 29.378906 11.621094 37 21 37 C 24.710938 37 28.140625 35.804688 30.9375 33.78125 L 44.09375 46.90625 L 46.90625 44.09375 L 33.90625 31.0625 C 36.460938 28.085938 38 24.222656 38 20 C 38 10.621094 30.378906 3 21 3 Z M 21 5 C 29.296875 5 36 11.703125 36 20 C 36 28.296875 29.296875 35 21 35 C 12.703125 35 6 28.296875 6 20 C 6 11.703125 12.703125 5 21 5 Z"></path>
</svg>
<input type="text" placeholder="Search Location.." class="border-none outline-none p-1">

    </div>
    </div>
<div class="flex flex-col my-4 mx-1">
        <label class="text-sm m-0 text-gray-500">Number of rooms:</label>  
        <div class="bg-white border border-gray-400 my-1  px-3 py-2 rounded-lg flex flex-row items-center">
            <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px"
width="20" height="20"
viewBox="0 0 50 50">
<path d="M 24.962891 1.0546875 A 1.0001 1.0001 0 0 0 24.384766 1.2636719 L 1.3847656 19.210938 A 1.0005659 1.0005659 0 0 0 2.6152344 20.789062 L 4 19.708984 L 4 46 A 1.0001 1.0001 0 0 0 5 47 L 18.832031 47 A 1.0001 1.0001 0 0 0 19.158203 47 L 30.832031 47 A 1.0001 1.0001 0 0 0 31.158203 47 L 45 47 A 1.0001 1.0001 0 0 0 46 46 L 46 19.708984 L 47.384766 20.789062 A 1.0005657 1.0005657 0 1 0 48.615234 19.210938 L 41 13.269531 L 41 6 L 35 6 L 35 8.5859375 L 25.615234 1.2636719 A 1.0001 1.0001 0 0 0 24.962891 1.0546875 z M 25 3.3222656 L 44 18.148438 L 44 45 L 32 45 L 32 26 L 18 26 L 18 45 L 6 45 L 6 18.148438 L 25 3.3222656 z M 37 8 L 39 8 L 39 11.708984 L 37 10.146484 L 37 8 z M 20 28 L 30 28 L 30 45 L 20 45 L 20 28 z"></path>
</svg>
<input type="number" placeholder="No. Rooms" class="border-none outline-none p-1">

</div>
</div>
<div class="flex flex-col my-4 mx-1">
        <label class="text-sm m-0 text-gray-500">Price:</label>  
        <div class="bg-white border border-gray-400 my-1  px-3 py-2 rounded-lg flex flex-row items-center">
            <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px"
width="20" height="20"
viewBox="0 0 50 50">
<path d="M 24.962891 1.0546875 A 1.0001 1.0001 0 0 0 24.384766 1.2636719 L 1.3847656 19.210938 A 1.0005659 1.0005659 0 0 0 2.6152344 20.789062 L 4 19.708984 L 4 46 A 1.0001 1.0001 0 0 0 5 47 L 18.832031 47 A 1.0001 1.0001 0 0 0 19.158203 47 L 30.832031 47 A 1.0001 1.0001 0 0 0 31.158203 47 L 45 47 A 1.0001 1.0001 0 0 0 46 46 L 46 19.708984 L 47.384766 20.789062 A 1.0005657 1.0005657 0 1 0 48.615234 19.210938 L 41 13.269531 L 41 6 L 35 6 L 35 8.5859375 L 25.615234 1.2636719 A 1.0001 1.0001 0 0 0 24.962891 1.0546875 z M 25 3.3222656 L 44 18.148438 L 44 45 L 32 45 L 32 26 L 18 26 L 18 45 L 6 45 L 6 18.148438 L 25 3.3222656 z M 37 8 L 39 8 L 39 11.708984 L 37 10.146484 L 37 8 z M 20 28 L 30 28 L 30 45 L 20 45 L 20 28 z"></path>
</svg>
<select class="border-none outline-none p-1 bg-white">
    <option selected disabled>Price</option>
    <option>$100 and below</option>
    <option>$100 and $200</option>
    <option>$200 and $500</option>
    <option>$500 and above</option>
</select>
</div>
</div>
<div class="flex flex-col my-4 mx-1">
        <label class="text-sm m-0 text-gray-500">Density</label>  
        <div class="bg-white border border-gray-400 my-1  px-3 py-2 rounded-lg flex flex-row items-center">
            <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px"
width="20" height="20"
viewBox="0 0 50 50">
<path d="M 24.962891 1.0546875 A 1.0001 1.0001 0 0 0 24.384766 1.2636719 L 1.3847656 19.210938 A 1.0005659 1.0005659 0 0 0 2.6152344 20.789062 L 4 19.708984 L 4 46 A 1.0001 1.0001 0 0 0 5 47 L 18.832031 47 A 1.0001 1.0001 0 0 0 19.158203 47 L 30.832031 47 A 1.0001 1.0001 0 0 0 31.158203 47 L 45 47 A 1.0001 1.0001 0 0 0 46 46 L 46 19.708984 L 47.384766 20.789062 A 1.0005657 1.0005657 0 1 0 48.615234 19.210938 L 41 13.269531 L 41 6 L 35 6 L 35 8.5859375 L 25.615234 1.2636719 A 1.0001 1.0001 0 0 0 24.962891 1.0546875 z M 25 3.3222656 L 44 18.148438 L 44 45 L 32 45 L 32 26 L 18 26 L 18 45 L 6 45 L 6 18.148438 L 25 3.3222656 z M 37 8 L 39 8 L 39 11.708984 L 37 10.146484 L 37 8 z M 20 28 L 30 28 L 30 45 L 20 45 L 20 28 z"></path>
</svg>
<select class="border-none outline-none p-1 bg-white">
    <option selected disabled>Density</option>
    <option>Low</option>
    <option>Medium</option>
    <option>High</option>
</select>
</div>
</div>
<div class="flex flex-col my-4 mx-1">
        <label class="text-sm m-0 text-gray-500">Click to search</label>  
        <div class="bg-[var(--secondaryblue)] text-white border-gray-400 my-1  px-3 py-2 rounded-lg flex flex-row items-center">
<button type="submit" placeholder="Search Location.." name="Search" class="border-none outline-none p-1 px-10">Search</button>

</div>
</div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.sticky{
    position: sticky;
    position: -webkit-sticky;
    top: 0;
    z-index: 2;
}
</style>