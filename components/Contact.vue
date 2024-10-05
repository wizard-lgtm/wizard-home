<template>
    <div class="w-screen h-screen flex justify-between gap-4">
        <div class="flex flex-1 flex-col gap-3 pxW-4 sm:px-24 md:px-32">
            <h1 class="text-center text-4xl font-bold">Let's meet!</h1>
            <label class="text-lg font-semibold" for="name">Name</label>
            <input
                class="p-1 transition-all duration-300 ease-in-out focus:shadow-white focus:outline-none focus:shadow-sm bg-transparent border-[1px] border-white rounded-md"
                type="text"
            />
            <label class="text-lg font-semibold" for="email">Email</label>
            <input
                class="p-1 transition-all duration-300 ease-in-out focus:shadow-white focus:outline-none focus:shadow-sm bg-transparent border-[1px] border-white rounded-md"
                type="text"
            />

            <label class="text-lg font-semibold" for="email"
                >Your cute message</label
            >

            <textarea
                class="block mb-2 p-2.5 transition-all duration-300 ease-in-out focus:shadow-white focus:outline-none focus:shadow-sm bg-transparent border-[1px] border-white rounded-md"
                type="text"
                rows="6"
                placeholder="dear..."
            />
            <div class="flex w-full justify-end p-4">
                <button
                    class="p-3 transition-all duration-300 ease-in-out rounded-full hover:border-white border-transparent border-4 hover:bg-transparent hover:text-[#ECDFCC] bg-[#ECDFCC] text-[#222831]"
                >
                    Send it to birds!
                </button>
            </div>
        </div>
    </div>
</template>
