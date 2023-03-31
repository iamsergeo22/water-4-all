<template>
    <div class="px-4 sm:px-6 lg:px-8 py-10 container">
        <h2 class="text-3xl text-indigo-600 font-bold uppercase text-center mb-4">Contact Us</h2>
        <p class="text-black mb-12 lg:text-center sm:text-justify">

            If you have discovered a new source of water in a community that is in need of clean and safe drinking  <br>
            water, Water4all would love to hear from you. 
            Our organization is committed to providing access to clean <br>
            water to communities in need, and we are always looking for new opportunities to make a positive impact.

        </p>
        <div class="grid grid-cols-1 md:grid-cols-2 gap-10">

            <div class="text-lg sm:text-lg mb-16">
                <form action="#" class="mb-12">
                    <div class="flex flex-wrap mb-6 -mx-4">
                        <div class="w-full md:w-1/2 mb-6 md:mb-0 px-4">
                            <label class="block mb-2 text-copy-primary" for="name">
                                Name
                            </label>

                            <input type="text" name="name" id="name" placeholder="Jon Snow"
                                class="block w-full bg-background-form border border-border-color-primary shadow rounded outline-none focus:border-green-700 mb-2 p-4"
                                required>
                        </div>

                        <div class="w-full px-4 md:w-1/2">
                            <label class="block text-copy-primary mb-2" for="email">
                                Email Address
                            </label>

                            <input type="email" name="email" id="email" placeholder="email@example.com"
                                class="block w-full bg-background-form border border-border-color-primary shadow rounded outline-none focus:border-green-700 mb-2 p-4"
                                required>
                        </div>
                    </div>

                    <div class="flex flex-wrap mb-6 -mx-4">
                        <div class="w-full md:w-1/2 mb-6 md:mb-0 px-4">
                            <label class="block mb-2 text-copy-primary" for="number">
                                Phone Number
                            </label>

                            <input type="number" name="number" id="number" placeholder="+228 90046079"
                                class="block w-full bg-background-form border border-border-color-primary shadow rounded outline-none focus:border-green-700 mb-2 p-4"
                                required>
                        </div>

                        <div class="w-full px-4 md:w-1/2">
                            <label class="block text-copy-primary mb-2" for="email">
                                Subject
                            </label>

                            <input type="email" name="email" id="email" placeholder="Project Proposal"
                                class="block w-full bg-background-form border border-border-color-primary shadow rounded outline-none focus:border-green-700 mb-2 p-4"
                                required>
                        </div>
                    </div>


                    <div class="w-full mb-8">
                        <label class="block text-copy-primary mb-2" for="message">
                            Message
                        </label>

                        <textarea id="message" rows="5" name="message"
                            class="block w-full bg-background-form border border-border-color-primary shadow rounded outline-none appearance-none focus:border-green-700 mb-2 px-4 py-4"
                            placeholder="Enter your message here." required></textarea>
                    </div>

                    <div class="flex justify-end w-full">
                        <input type="submit" value="Submit"
                            class="block bg-blue-600 hover:bg-blue-800 text-white text-sm font-semibold tracking-wide uppercase shadow rounded cursor-pointer px-6 py-3">
                    </div>
                </form>
            </div>

            <!-- Map section -->

            <div>
                <div class="bg-blue-500 rounded-lg shadow-lg px-4">
                    <h2 class="text-2xl font-bold text-white mb-4">Address</h2>
                    <p class="text-white italic mb-4">123 Main St</p>
                    <p class="text-white italic mb-4">Suite 500</p>
                    <p class="text-white italic mb-4">New York, NY 10001</p>
                </div>

                <div class="aspect-w-16 aspect-h-7 rounded-lg shadow-lg overflow-hidden">
                    <iframe
                        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3022.417412837234!2d-73.98579178521707!3d40.74844194225139!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x89c259d75c5f5c5d%3A0x93a74d47b46dbd65!2sEmpire%20State%20Building!5e0!3m2!1sen!2sus!4v1635024562182!5m2!1sen!2sus"
                        width="600" height="338" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
                </div>
            </div>


        </div>
    </div>
</template>