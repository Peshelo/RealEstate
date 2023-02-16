<template>
    <div class="flex flex-col justify-center items-center">
        <img src="@/static/logo.png" alt="" srcset="" width="200">
    <form @submit.prevent="handleSubmit()" class="mt-2 p-5 flex flex-col items-center">
        <p class="py-2 px-4 bg-red-200 text-red-400 border border-red-400 rounded-lg mb-2 w-full" v-if="this.errors.ERR">Error: {{this.errors.ERR}}</p>
        <input type="email" v-model="email" name="email" id="" placeholder="Email" class="py-2 px-4 border rounded-lg mb-2 w-full focus:outline-none focus:border-[var(--secondary)] duration-300">
        <p v-if="this.errors.email" class="text-sm text-red-600 text-left mb-2">*{{this.errors.email}}</p>
        <input type="password" v-model="password" name="password" id="" placeholder="Password" class="py-2 px-4 border rounded-lg mb-2 w-full focus:outline-none focus:border-[var(--secondary)] duration-300">
        <p v-if="this.errors.password" class="text-sm text-red-600 text-left mb-2">*{{this.errors.password}}</p>
        <button class="py-2 bg-[var(--primary)] text-white font-semibold rounded-md w-full">Login</button>
        <p class="text-sm text-gray-400 mt-5">Do not have an account? <a href="/auth/signup" class="text-red-300">Sign up</a></p>
    </form>
    </div>
</template>

<script>
export default {
    layout:'auth',
    data(){
        return{
            email: "",
            password: "",
            errors: {}
        }
    },
    methods:{
        handleSubmit(){
            this.errors = {};
            if(!this.email){
                this.errors.email = "Email is required";
            }
            if(!this.password){
                this.errors.password = "Enter password";
            }
            if(!this.errors){
                try{
                //Handle submit
                alert("Email" + this.email);
                }catch(err){
                    this.error.ERR = err;
                }
               
            }
        }
    }
    

}
</script>

<style>

</style>