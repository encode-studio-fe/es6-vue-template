<template>
  <main px-4 py-10 text="center gray-700 dark:gray-200">
    <RouterView />
    <TheCounter initial="1" />

    <TheFooter />
    <div mx-auto mt-5 text-center text-sm opacity-50>[Default Layout]</div>
  </main>
</template>
