<template>
    <f7-page name="level">
      <!-- Top Navbar -->
      <f7-navbar large>
        <f7-nav-title>CatTv7</f7-nav-title>
        <f7-nav-title-large>CatTv7</f7-nav-title-large>
      </f7-navbar>
      <!-- Toolbar-->
      <f7-toolbar bottom>
        <f7-link>Left Link</f7-link>
        <f7-link>Right Link</f7-link>
      </f7-toolbar>
      <!-- Page content-->
    
    <div class="page">
      <div class="navbar">
        <div class="navbar-bg"></div>
        <div class="navbar-inner sliding">
          <div class="title">List Button</div>
        </div>
      </div>
  
      <div class="page-content">
        <f7-block-title>Запрос уровня на ONU</f7-block-title>
        <div class="list inset list-strong">
            <ul>
                <f7-list-input
                    outline
                    label="Адресс дома"
                    floating-label
                    type="text"
                    placeholder="вводи сюда"
                    clear-button
                    v-model:value="street"
                >
                <template #media>
                  <f7-icon icon="demo-list-icon" />
                </template>
              </f7-list-input>
            </ul>
          </div>
          <div class="list inset list-strong">
          <ul>
            <f7-link @click="as" class="list-button color-green">Запросить</f7-link>
          </ul>
        </div>
        <div class="list inset list-strong">
          <ul>
            <f7-link href="/" class="list-button color-blue">Меню</f7-link>
          </ul>
        </div>
      </div>
    </div>
  
    </f7-page>
  </template>
<script setup>
import {ref} from 'vue'
 const street = ref('')
  function as(){
    street.value = ''
  }
</script>
<style scoped>

</style>
