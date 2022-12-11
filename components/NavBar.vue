<template>
  <div onclick="document.querySelector('.navbar-menu').classList.toggle('is-active');">
    <nav class="navbar is-fixed-top" role="navigation" aria-label="main navigation">
  <div class="navbar-brand">
    <NuxtLink class="navbar-item" to="/">
      <img src="" alt="Oxygenix" width="112" height="28">
    </NuxtLink>

    <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
    </a>
  </div>

  <div id="navbarBasicExample" class="navbar-menu">
    <div class="navbar-start">
      <NuxtLink to="/" class="navbar-item">
        Clínica
      </NuxtLink>
      <div class="navbar-item has-dropdown is-hoverable">

      <a class="navbar-link">
        Indicações
      </a>

      <div class="navbar-dropdown">
          <NuxtLink to="/" class="navbar-item">
            Pós-cirurgia
          </NuxtLink>
          <a class="navbar-item">
            Diabetes
          </a>
          
          <hr class="navbar-divider">
          <a class="navbar-item">
            Lesões Actínicas
          </a>
        </div>

      </div>

      <div class="navbar-item has-dropdown is-hoverable">
        <a class="navbar-link">
          Mais
        </a>

        <div class="navbar-dropdown">
          <NuxtLink to="/about" class="navbar-item">
            Sobre Nós
          </NuxtLink>
          <a class="navbar-item">
            Trabalhe Conosco
          </a>
          
          <hr class="navbar-divider">
          <a class="navbar-item">
            Contato
          </a>
        </div>
      </div>
    </div>

    <div class="navbar-end">
      <div class="navbar-item">
        <div class="buttons">
          <a class="button is-info">
            <strong>Agendamento</strong>
          </a>
          
        </div>
      </div>
    </div>
  </div>
</nav>
</div>
</template>