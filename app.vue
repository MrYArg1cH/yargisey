<script setup>
useHead({
  bodyAttrs: {
    class: 'body'
  }
})
</script>

<template>
    <Header>
    </Header>

    <main class="min-h-[calc(100vh-32.5rem)] xl:min-h-[calc(100vh-21rem)]">
            <NuxtPage/>
    </main>

    <Footer>
    </Footer>
</template>

<style>
@font-face {
  font-family: 'Comfortaa';
  src: url('./assets/fonts/Comfortaa/Comfortaa-VariableFont_wght.ttf');
}
</style>