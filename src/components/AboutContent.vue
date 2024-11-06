<script setup>

</script>

<template>
  <div class="about-content">
    <div class="description">
      <h1>Paróquia Santa Teresinha do Menino Jesus</h1>
      <p>
        A Paróquia Santa Teresinha do Menino Jesus é uma comunidade católica
        localizada no bairro Doroteia, em São Paulo. Fundada em 1992, a
        paróquia é dedicada a Santa Teresinha do Menino Jesus, uma santa francesa
        que viveu no século XIX e é conhecida por sua devoção à Virgem Maria e ao
        Menino Jesus.
      </p>
    </div>
    <div class="events-container">
      <h2>Eventos recentes</h2>
      <span id="events-horizontal-line">-</span>
      <img id="events-rose-icon" src="" alt="Rosa"/>
      <br/>
      <div class="events">
        <span>&lt;</span>
        <div class="event">
          <h1>Novena de Santa Teresinha</h1>
          <p>
            A novena de Santa Teresinha é uma tradição anual da paróquia, que
            acontece durante os nove dias que antecedem a festa da santa, em 1º de
            outubro. Durante a novena, os fiéis se reúnem para rezar e pedir a
            intercessão de Santa Teresinha em suas vidas.
          </p>
        </div>
        <span>&gt;</span>
      </div>
    </div>
  </div>
</template>

<style scoped>

@import url('https://fonts.googleapis.com/css2?family=Kaushan+Script&display=swap');

.about-content .description {
  margin: 0 auto;
  max-width: 800px;
  padding: 20px;
  border-left: 1px solid #A6813D;
  margin: 20px;
}

.about-content .description h1 {
  font-family: "Kaushan Script", cursive;
  font-weight: 400;
  font-style: normal;
  color: #A6813D;
}

.about-content .events h1 {
  font-family: "Roboto", sans-serif;
  font-weight: 400;
  font-style: normal;
  color: #A6813D;
}

.about-content .events-container h2 {
  color: #2D2D2D;
  text-align: center;
}

p {
  font-family: "Roboto", sans-serif;
  font-weight: 300;
  font-style: normal;
  color: #1E1E1E;
  font-size: 16px;
}

</style>
