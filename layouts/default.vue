<template>
  <div>
    <nav>
      <NuxtLink to="/">Home</NuxtLink>
      <NuxtLink to="/about">About</NuxtLink>
      <NuxtLink to="/benefits">Benefits</NuxtLink>
      <NuxtLink to="/careers">Careers</NuxtLink>
      <NuxtLink to="/products">Products</NuxtLink>
      <NuxtLink to="/services">Services</NuxtLink>
      <NuxtLink to="/contact">Contact</NuxtLink>
    </nav>
    <slot></slot>
    <footer>My Website Footer</footer>
  </div>
</template>
