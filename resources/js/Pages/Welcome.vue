<script setup>
import Footer from '@/Components/Footer.vue';
import Header from '@/Components/Header.vue';
import { Head } from '@inertiajs/vue3';


</script>

<template>

    <Head title="Teste" />
    <Header />
    <main class="container mx-auto max-w-3xl p-8 grow">

        <div>
            <div class="mb-8 border-dotted border-b pb-8 border-gray-300">
                <h2>
                    <a class="block" href="https://reeseschultz.github.io/11r/post/deadbeef-decrementation/">Deadbeef
                        Decrementation</a>
                </h2>

                <p class="excerpt">How to decrement from a magic debug value to zero.</p>

                <a class="tag spirituality" href="https://reeseschultz.github.io/11r/tag/spirituality">spirituality</a>

                <span class="block md:inline md:float-right md:pt-4 pt-2 created-date"
                    datetime="Sat Oct 08 2016 19:00:00 GMT-0500 (Central Daylight Time)">
                    October 9, 2016
                </span>
            </div>



            <div class="mb-8 border-dotted border-b pb-8 border-gray-300">
                <h2>
                    <a class="block" href="https://reeseschultz.github.io/11r/interior-crocodile-alligator/">Interior
                        Crocodile Alligator, I Drive a Chevrolet Movie Theater</a>
                </h2>

                <p class="excerpt">♫ Interior Crocodile Alligator, I Drive a Chevrolet Movie Theater ♫</p>

                <a class="tag cats" href="https://reeseschultz.github.io/11r/tag/cats">cats</a>

                <span class="block md:inline md:float-right md:pt-4 pt-2 created-date"
                    datetime="Thu Sep 18 2008 19:00:00 GMT-0500 (Central Daylight Time)">
                    September 19, 2008
                </span>
            </div>



            <div class="mb-8 border-dotted border-b pb-8 border-gray-300">
                <h2>
                    <a class="block"
                        href="https://reeseschultz.github.io/11r/post/why-my-practice-of-thelema-makes-me-better-at-world-of-warcraft/">Why
                        My Practice of Thelema Makes Me Better at World of Warcraft</a>
                </h2>

                <p class="excerpt">"Do what thou wilt" shall be the whole of the Law.</p>

                <a class="tag enchiladas" href="https://reeseschultz.github.io/11r/tag/enchiladas">enchiladas</a>

                <span class="block md:inline md:float-right md:pt-4 pt-2 created-date"
                    datetime="Sun Sep 08 1974 19:00:00 GMT-0500 (Central Daylight Time)">
                    September 9, 1974
                </span>
            </div>





            <div class="mb-8 border-dotted border-b pb-8 border-gray-300">
                <h2>
                    <a class="block"
                        href="https://reeseschultz.github.io/11r/post/shrek-predicted-the-covid-19-pandemic/">Shrek
                        Predicted the COVID-19 Pandemic</a>
                </h2>

                <p class="excerpt">Find out how Shrek is disrupting astrology.</p>

                <a class="tag orcas" href="https://reeseschultz.github.io/11r/tag/orcas">orcas</a><a class="tag beer"
                    href="https://reeseschultz.github.io/11r/tag/beer">beer</a>

                <span class="block md:inline md:float-right md:pt-4 pt-2 created-date"
                    datetime="Fri Apr 15 1921 19:00:00 GMT-0500 (Central Daylight Time)">
                    April 16, 1921
                </span>
            </div>



            <div class="mb-8 border-dotted border-b pb-8 border-gray-300">
                <h2>
                    <a class="block" href="https://reeseschultz.github.io/11r/post/lorem-ipsum/">Lorem Ipsum</a>
                </h2>

                <p class="excerpt">You know what time it is: lorem ipsum time.</p>

                <a class="tag stoicism" href="https://reeseschultz.github.io/11r/tag/stoicism">stoicism</a>

                <span class="block md:inline md:float-right md:pt-4 pt-2 created-date"
                    datetime="Sun Nov 03 1918 18:00:00 GMT-0600 (Central Standard Time)">
                    November 4, 1918
                </span>
            </div>


        </div>

        <div>
            <div class="md:flex justify-evenly mb-6">
                <div class="flex justify-between mx-auto w-full">



                    <div class="mx-auto mb-4">
                        <a class="next-page md:mb-2" href="https://reeseschultz.github.io/11r/page/2/">Previous Page</a>
                    </div>

                </div>

                <div class="flex justify-between mx-auto w-full">



                    <div class="mx-auto">
                        <a class="last-page" href="https://reeseschultz.github.io/11r/page/2/">Last Page</a>
                    </div>

                </div>
            </div>

            <p class="text-center text-sm italic mb-10">(On page
                1
                of
                2.)</p>
        </div>

        <div class="grid grid-flow-row grid-cols-3 gap-4 mb-2">
            <a class="tag cats mx-auto" href="https://reeseschultz.github.io/11r/tag/cats">cats</a>
            <a class="tag enchiladas mx-auto" href="https://reeseschultz.github.io/11r/tag/enchiladas">enchiladas</a>
            <a class="tag beer mx-auto" href="https://reeseschultz.github.io/11r/tag/beer">beer</a>
            <a class="tag spirituality mx-auto"
                href="https://reeseschultz.github.io/11r/tag/spirituality">spirituality</a>
            <a class="tag orcas mx-auto" href="https://reeseschultz.github.io/11r/tag/orcas">orcas</a>
            <a class="tag stoicism mx-auto" href="https://reeseschultz.github.io/11r/tag/stoicism">stoicism</a>
        </div>
    </main>
    <Footer />
</template>
