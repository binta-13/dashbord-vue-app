<template>
  <div class="grid grid-cols-2 -ml-20 border-b mt-4 mr-4">
    <div class="container">
      <h1 class="text-2xl">Customer</h1>
      <p class="text-gray-400 mt-1">
        Lorem ipsum dolor, sit amet consectetur adipisicing elit.
      </p>
    </div>
    <div class="container mt-10 mb-2">
      <ul class="flex justify-start space-x-32 text-lg">
        <li>
          <a href="#" class="text-blue-700">Customer</a>
        </li>
        <li>
          <a href="#" class="text-gray-400 hover:text-blue-700">Promo</a>
        </li>
        <li>
          <a href="#" class="text-gray-400 hover:text-blue-700">Voucher</a>
        </li>
      </ul>
    </div>
  </div>
  <div class="container text-white bg-blue-800 w-full rounded-md mt-4 -ml-20">
    <div class="m-3 pt-3">
      <h1 class="text-2xl">Customer</h1>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. <br />Fuga,
        illum animi iusto nisi .
      </p>
    </div>
    <div class="flex justify-start space-x-10 text-lg m-3">
      <button
        class="bg-opacity-40 bg-gray-400 text-white px-4 py-2 rounded-lg mb-3"
      >
        + Add New Customer
      </button>
      <label class="relative block mt-0">
        <input
          type="text"
          placeholder="Search Customer ..."
          class="border rounded-md px-4 py-2 "
        />
        <button
          class="bg-blue-500 text-white p-1 rounded-md absolute -ml-20 mt-1 mb-1"
        >
          Search
        </button>
      </label>
      <button
        class="bg-opacity-40 bg-gray-400 text-white px-4 py-2 rounded-lg mb-3"
      >
        + Filter
      </button>
      <button
        class="bg-opacity-40 bg-gray-400 text-white px-4 py-2 rounded-lg mb-3"
      >
        + Refresh
      </button>
      <button
        class="bg-opacity-40 bg-gray-400 text-white px-4 py-2 rounded-lg mb-3"
      >
        + Print
      </button>
    </div>
  </div>
</template>
