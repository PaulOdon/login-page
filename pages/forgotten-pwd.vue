<template>
  <section class="section">
    <div class="container">
      <div class="columns is-vcentered">
        <div class="column is-6 is-offset-one-quarter">
          <br /><br /><br />
          <h1 class="is-size-4">Récupération de votre mot de passe</h1>
          <br>
          <div class="container">
            <p>Entrer votre adresse email ci-dessous pour récupérer votre mot de passe.</p>

            <b-field>
              <b-input type="email" maxlength="40"> </b-input>
            </b-field>

            <div class="has-text-centered">
              <b-button type="is-primary" icon-left="check">Enoyer</b-button>
              <br>
              <p><a href="/"  class="is-size-7">Connexion?</a></p>
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