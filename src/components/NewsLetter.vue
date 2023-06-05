<!-- eslint-disable no-mixed-spaces-and-tabs -->
<template>
  <!-- <section class="text-gray-600 body-font relative">
    <div class="container px-5 py-24 mx-auto flex sm:flex-nowrap flex-wrap">
      <div
        class="lg:w-2/3 md:w-1/2 bg-gray-100 rounded-lg overflow-hidden sm:mr-10 p-10 flex items-end justify-start relative">
        <img class="object-cover object-center rounded" alt="hero" src="../assets/contact-image.png">
      </div>
      <div class="lg:w-1/3 md:w-1/2 bg-white flex flex-col md:ml-auto w-full md:py-8 mt-8 md:mt-0">
        <form name="contact" method="post" data-netlify="true" hidden>
          <input type="hidden" name="form-name" value="contact" />
          <h2 class="text-gray-900 text-2xl mb-1 font-bold title-font">Send us a Message now</h2>
          <p class="leading-relaxed mb-5 text-gray-600 text-md">You are only a few steps away from obtaining the
            information
            you
            require. However, if you send the message now, our team will contact you right away</p>
          <div class="relative mb-4">
            <label for="name" class="leading-7 text-sm text-gray-600">Name</label>
            <input type="text" id="name" name="name"
              class="w-full bg-white rounded border border-gray-300 focus:border-indigo-500 text-base outline-none text-gray-700 py-1 px-3 leading-8 "
              required>
          </div>
          <div class="relative mb-4">
            <label for="email" class="leading-7 text-sm text-gray-600">Email</label>
            <input type="email" id="email" name="email" placeholder="email@example.com"
              class="w-full bg-white rounded border border-gray-300 focus:border-indigo-500 text-base outline-none text-gray-700 py-1 px-3 leading-8"
              required>
          </div>
          <div class="relative mb-4">
            <label for="message" class="leading-7 text-sm text-gray-600">Message</label>
            <textarea id="message" type="textarea" name="message"
              class="w-full bg-white rounded border border-gray-300 focus:border-indigo-500 h-32 text-base outline-none text-gray-700 py-1 px-3 resize-none leading-6 transition-colors duration-200 ease-in-out"
              required></textarea>
          </div>
          <button type="submit"
            class="text-white border-0 py-2 px-6 focus:outline-none rounded text-lg btn-bg">Submit</button>
          <div class="flex items-center mt-4 ">
            <input type="checkbox" name="" id="" class=" px-6" required>
            <p class="text-lg text-gray-500 px-2 ">You agree to the terms and condition.</p>

          </div>
        </form>
      </div>

    </div>
  </section> -->

<!-- <form method="post" name="Contact Form" data-netlify="true">
  <input type="hidden" name="form-name" value="contact" />
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname" value="John"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname" value="Doe"><br><br>
  <input type="submit" value="Submit">
</form>  -->

<main class="body-bg min-h-screen pt-12 md:pt-20 pb-6 px-2 md:px-0">
		<section>
			<div class=" pt-24">
		<main class="bg-white max-w-lg mx-auto p-8 md:p-12 my-10 rounded-lg shadow-2xl">
			<section>
				<h3 class="font-bold text-2xl text-gray-600">Welcome to Signco</h3>
				<p class="text-gray-600 pt-2">Sign in to your account.</p>
			</section>
			<section class="mt-10">
				<form class="" netlify>
					<div class="mb-6 pt-3 rounded bg-gray-200">
						<label class="block text-gray-700 text-sm font-bold mb-2 ml-3" for="email">Email</label>
						<input type="text" id="email"
							class="bg-gray-200 rounded w-full text-gray-700 focus:outline-none border-b-4 border-gray-300 focus:border-orange-600 transition duration-500 px-3 pb-3" />
					</div>
					<div class="mb-6 pt-3 rounded bg-gray-200">
						<label class="block text-gray-700 text-sm font-bold mb-2 ml-3" for="name">Name</label>
						<input type="text" id="name"
							class="bg-gray-200 rounded w-full text-gray-700 focus:outline-none border-b-4 border-gray-300 focus:border-orange-600 transition duration-500 px-3 pb-3" />
					</div>
					<div class="flex justify-end">
						<label for="message" class="leading-7 text-sm text-gray-600">Message</label>
						<textarea id="message" type="textarea" name="message"
						  class="w-full bg-white rounded border border-gray-300 focus:border-indigo-500 h-32 text-base outline-none text-gray-700 py-1 px-3 resize-none leading-6 transition-colors duration-200 ease-in-out"
						  required></textarea>

					</div>
					<button
						class="bg-orange-600 hover:bg-purple-700 text-white font-bold py-2 px-8 rounded shadow-lg hover:shadow-xl transition duration-200"
						type="submit">
						Sign In
					</button>
				</form>
			</section>
		</main>
		</div>




		</section>
	</main>
</template>


<script>

export default {
  name: 'App',
  components: {},

};
</script>

<style>
.btn-sign {
  background-color: #3A54AA
}

.btn-bg {
  background-color: #1D1D1D;
}
</style>

