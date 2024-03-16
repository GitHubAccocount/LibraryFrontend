<template>
  <div class="min-h-screen flex items-center justify-center w-full">
    <div
      class="bg-white dark:bg-gray-400 shadow-md rounded-lg px-8 py-6 max-w-md"
    >
      <h1 class="text-2xl font-bold text-center mb-4 text-white">Biblioteka</h1>
      <form action="#">
        <div class="mb-4">
          <label for="email" class="block text-sm font-medium text-white mb-2"
            >Adres Email</label
          >
          <input
            type="email"
            id="email"
            class="shadow-sm rounded-md w-full px-3 py-2 border border-gray-300 focus:outline-none focus:ring-indigo-500 focus:border-indigo-500"
            placeholder="przykład@email.com"
            required
          />
        </div>
        <div class="mb-4">
          <label
            for="password"
            class="block text-sm font-medium text-white mb-2"
            >Hasło</label
          >
          <input
            type="password"
            id="password"
            class="shadow-sm rounded-md w-full px-3 py-2 border border-gray-300 focus:outline-none focus:ring-indigo-500 focus:border-indigo-500"
            placeholder="Wprowadź hasło"
            required
          />
          <a
            href="#"
            class="text-xs text-gray-200 hover:text-gray-50 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500"
            >Zapomniałeś hasła?</a
          >
        </div>
        <div class="flex items-center justify-between mb-4">
          <div class="flex items-center">
            <input
              type="checkbox"
              id="remember"
              class="h-4 w-4 rounded border-gray-300 text-indigo-600 focus:ring-indigo-500 focus:outline-none"
              checked
            />
            <label for="remember" class="ml-2 block text-sm text-white"
              >Zapamiętaj mnie</label
            >
          </div>
          <a
            href="#"
            class="text-xs text-slate-600 hover:text-slate-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-slate-500"
            >Stwórz konto</a
          >
        </div>
        <button
          type="submit"
          class="w-full flex justify-center py-2 px-4 border border-transparent rounded-md shadow-sm text-sm font-medium text-white bg-slate-600 hover:bg-slate-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500"
        >
          Zaloguj się
        </button>
      </form>
    </div>
  </div>
</template>

<script setup></script>
