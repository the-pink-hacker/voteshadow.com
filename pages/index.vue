<template>
  <div class="content-wrapper">
    <p>SHADOW THE MOTHER FUCKING HEDGEHOG</p>
    <img class="shadow" src="/media/shadow.png" alt="Shadow the Hedgehog" />
    <img
      class="under-construction"
      src="https://web.archive.org/web/20091021124140/http://www.geocities.com/funnyleboproductions2/under-construction.gif"
      alt="website under construction"
    />
  </div>
</template>

<style lang="scss" scoped>
@keyframes spin {
  0% {
    transform: rotate(0);
  }
  50% {
    transform: rotate(180deg);
  }
  100% {
    transform: rotate(360deg);
  }
}

.content-wrapper {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.shadow {
  max-width: 67vw;
  max-height: 67vh;
  aspect-ratio: 1 / 1;
  object-fit: contain;
  animation: spin 5s infinite linear;
}

.under-construction {
  bottom: 0;
  position: absolute;
  height: 33%;
}
</style>
