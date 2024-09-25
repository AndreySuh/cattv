<template>
  <f7-page name="home">
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
      <div class="list inset list-strong list-dividers-ios">
        <ul>
          <f7-link class="list-button" href="/level/">Уровни</f7-link>
          <li><a class="list-button">Прописать mac</a></li>
          <li><a class="list-button">Логин пароль</a></li>
          <li><a class="list-button">Схема дома</a></li>
          <li><a class="list-button">Номер аббонента</a></li>
        </ul>
      </div>
      <div class="list inset list-strong">
        <ul>
          <f7-link href="/" class="list-button color-red">Выход</f7-link>
        </ul>
      </div>
    </div>
  </div>

  </f7-page>
</template>