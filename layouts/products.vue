<template>
  <div>
    <header>
      <nav>
        <NuxtLink to="/products">Nuxt Dojo Merch</NuxtLink>
      </nav>
    </header>
    <div>
      <slot></slot>
    </div>
    <footer>
      <DojoNavigation></DojoNavigation>
    </footer>
  </div>
</template>
