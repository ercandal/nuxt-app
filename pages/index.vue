<template>
    <div class="flex md:flex md:flex-row md:container md:mx-auto bg-orange-200">
        <div class="w-1/3 text-2xl">
            <button class="btn btn-primary text-black mb-2 hover:bg-orange-500 ml-10  text-4xl text-bold">Anasayfa</button>
        </div>
        <div class="w-1/3 text-2xl"> 
            <label class=""></label>
            <input type="text" for="search" placeholder="Ne Arıyorsunuz?" class="w-full text-black bg-orange-100">
        </div>
        <div class="w-1/3 flex justify-between text-2xl">
            <button class="btn btn-primary text-black mb-2 hover:bg-orange-500 ml-2  text-xl text-bold">Konum</button>
            <button class="btn btn-primary text-black mb-2 hover:bg-orange-500 ml-2  text-xl text-bold">Hesabım</button>
            <button class="btn btn-primary text-black mb-2 hover:bg-orange-500 ml-2  text-xl text-bold">Sepetim</button>
            
        </div>
        
    </div>
    <div class="md:container md:mx-auto md:flex md:flex-row bg-orange-200">
        <div class="w-1/3 pl-5">
            <NuxtLink to="/categoryPages" class="btn btn-primary text-black mb-2 hover:bg-orange-500 ml-2 text-3xl text-bold">Kategoriler</NuxtLink>
            <ul class="flex flex-col grid justify-items-start pl-2 ">
                <NuxtLink to="/categoryPages/electronicsPage" class="btn btn-primary text-black mb-2 hover:bg-orange-500 ml-2  text-xl text-bold">Elektronik</NuxtLink>
                <NuxtLink to="/categoryPages/computersPage" class="btn btn-primary text-black mb-2 hover:bg-orange-500 ml-2  text-xl text-bold">Bilgisayar</NuxtLink>
                <NuxtLink to="/categoryPages/whitegoodsPage" class="btn btn-primary text-black mb-2 hover:bg-orange-500 ml-2  text-xl text-bold">Beyaz Esya</NuxtLink>
                <NuxtLink to="/categoryPages/booksPage" class="btn btn-primary text-black mb-2 hover:bg-orange-500 ml-2  text-xl text-bold">Kitap</NuxtLink>
                <NuxtLink to="/categoryPages/smallhouseappliancesPage" class="btn btn-primary text-black mb-2 hover:bg-orange-500 ml-2  text-xl text-bold">Küçük Ev Aletleri</NuxtLink>
                <NuxtLink to="/categoryPages/outdoorandhobbyPage" class="btn btn-primary text-black mb-2 hover:bg-orange-500 ml-2  text-xl text-bold">Bahçe ve Hobiler</NuxtLink>
            </ul>
        </div>
        <div class="w-2/3">
            <div>
                <div class="grid grid-cols-3 justify-items-center place-items-center py-24">
                    <div class="card transition duration-300 hover:scale-105 mb-5">
                        <img src="https://picsum.photos/id/231/400/400" alt="">
                    </div>
                    <div class="card transition duration-300 hover:scale-105 mb-5">
                        <img src="https://picsum.photos/id/232/400/400" alt="">
                    </div>
                    <div class="card transition duration-300 hover:scale-105 mb-5">
                        <img src="https://picsum.photos/id/235/400/400" alt="">
                    </div>
                    <div class="card transition duration-300 hover:scale-105 mb-5">
                        <img src="https://picsum.photos/id/231/400/400" alt="">
                    </div>
                    <div class="card transition duration-300 hover:scale-105 mb-5">
                        <img src="https://picsum.photos/id/222/400/400" alt="">
                    </div>
                    <div class="card transition duration-300 hover:scale-105 mb-5">
                        <img src="https://picsum.photos/id/233/400/400" alt="">
                    </div>
                    <div class="card transition duration-300 hover:scale-105 mb-5">
                        <img src="https://picsum.photos/id/212/400/400" alt="">
                    </div>
                    <div class="card transition duration-300 hover:scale-105 mb-5">
                        <img src="https://picsum.photos/id/233/400/400" alt="">
                    </div>
                    <div class="card transition duration-300 hover:scale-105 mb-5">
                        <img src="https://picsum.photos/id/231/400/400" alt="">
                    </div>
                    <div class="card transition duration-300 hover:scale-105 mb-5">
                        <img src="https://picsum.photos/id/232/400/400" alt="">
                    </div>
                    <div class="card transition duration-300 hover:scale-105 mb-5">
                        <img src="https://picsum.photos/id/233/400/400" alt="">
                    </div>
                    <div class="card transition duration-300 hover:scale-105 mb-5">
                        <img src="https://picsum.photos/id/211/400/400" alt="">
                    </div>
                </div>
            </div>
            <div></div>
            <div></div>
        </div>
    </div>
    <div class="md:container md:mx-auto flex flex-row bg-orange-200">
        <div class="w-full">

        </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
.card {
    border: 2px solid white;
    max-width: 250px;
    height: auto;
    
}


input::placeholder {
    color: black;
}
</style>