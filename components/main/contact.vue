<template>
  <section class="py-12 px-4">
    <h2 class="text-4xl mb-10 text-center font-semibold font-heading">Contact the Scranton team</h2>
    <div class="w-full max-w-2xl mx-auto mb-12">
      <form>
        <div class="flex mb-4 -mx-2">
          <div class="w-1/2 px-2">
            <input
              class="appearance-none block w-full py-3 px-4 leading-tight text-gray-700 bg-gray-50 focus:bg-white border border-gray-200 focus:border-gray-500 rounded focus:outline-none"
              type="email"
              placeholder="Email"
            />
          </div>
          <div class="w-1/2 px-2">
            <select
              class="appearance-none block w-full py-3 px-4 leading-tight text-gray-700 bg-gray-50 focus:bg-white border border-gray-200 focus:border-gray-500 rounded focus:outline-none"
            >
              <option>-- Select product --</option>
              <option>Product 1</option>
              <option>Product 2</option>
              <option>Product 3</option>
            </select>
          </div>
        </div>
        <div class="mb-4">
          <textarea
            class="appearance-none block w-full py-3 px-4 leading-tight text-gray-700 bg-gray-50 focus:bg-white border border-gray-200 focus:border-gray-500 rounded focus:outline-none"
            placeholder="Write something..."
            rows="5"
          ></textarea>
        </div>
        <div>
          <button
            class="inline-block w-full py-4 px-8 leading-none text-white bg-indigo-600 hover:bg-indigo-700 font-semibold rounded shadow"
          >
            Submit
          </button>
        </div>
      </form>
    </div>
    <div class="flex flex-col lg:flex-row lg:justify-center -mx-4">
      <div class="px-4 flex items-center">
        <svg
          class="inline-block w-6 h-6 mr-3 text-indigo-600"
          fill="none"
          stroke="currentColor"
          viewBox="0 0 24 24"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6"
          ></path>
        </svg>
        <span>1725 Slough Avenue, Scranton</span>
      </div>
      <div class="px-4 flex items-center">
        <svg
          class="inline-block w-6 h-6 mr-3 text-indigo-600"
          fill="none"
          stroke="currentColor"
          viewBox="0 0 24 24"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"
          ></path>
        </svg>
        <span>555-111-555</span>
      </div>
      <div class="px-4 flex items-center">
        <svg
          class="inline-block w-6 h-6 mr-3 text-indigo-600"
          fill="none"
          stroke="currentColor"
          viewBox="0 0 24 24"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
          ></path>
        </svg>
        <span>scranton@dundermifflin.com</span>
      </div>
    </div>
  </section>
</template>