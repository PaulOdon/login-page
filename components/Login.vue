<template>
  <section>
    <div class="container">
      <div class="columns is-vcentered">
        <div class="column is-6 is-offset-one-quarter">
          <br /><br /><br />
          <h1 class="is-size-4 has-text-centered">Se connecter</h1>
          <br>
          <div class="container">
            <b-field label="Adresse email *">
              <b-input type="email" maxlength="40"> </b-input>
            </b-field>

            <b-field label="Mot de passe *">
              <b-input type="password" password-reveal> </b-input>
            </b-field>

            <div class="has-text-centered">
              <br>
              <b-button type="is-primary" icon-left="check">Valider</b-button>
              <p><a href="/nuxt-login-page/forgotten-pwd"  class="is-size-7">Mot de passe oublié?</a></p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style>
  .input, .button {
    border-radius: 0%;
  }
</style>