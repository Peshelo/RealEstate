<template>
    <div class="flex flex-col justify-between">
        <div class="flex flex-row justify-between mb-5">
            <h2 class="text-3xl font-bold">$147<sup><label class="text-gray-300 text-sm ml-1">/month</label></sup></h2>
        <div class="flex flex-row">
        <p class="m-2">Share</p>
        <p class="m-2">Like</p>
       </div>
        </div>
       
       <!-- Input -->
<form> 
<input type="text" placeholder="Name" class="outline-none p-1 bg-white border border-gray-400 my-1 px-3 py-2 rounded w-full">
<input type="text" placeholder="Email" class="outline-none p-1 bg-white border border-gray-400 my-1 px-3 py-2 rounded w-full">
<textarea type="text" placeholder="Comment" class="outline-none p-1 bg-white border border-gray-400 my-1 px-3 py-2 rounded w-full"></textarea>
<button class="bg-[var(--primary)] text-white w-full rounded p-2">Contact</button>
<p class="mt-4 text-sm text-center">By submiting this form you have agreed to the <a class="text-red-300">Terms and conditions</a></p>
</form>
       
    <!-- input end -->
        </div>
</template>

<script>
export default {

}
</script>

<style>

</style>