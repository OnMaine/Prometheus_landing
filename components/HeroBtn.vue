<template>
  <button class="header-btn">
    <slot>Button</slot>
  </button>
</template>

<style>
.header-btn {
  font-family: 'Roboto', sans-serif;
  font-size: 20px;
  color: #FFFFFF;
  background-color: #0b77fa;
  height: 47px;
  width: 190px;
  outline: none;
  cursor: pointer;
  border-radius: 8px;
  border: none;
  text-transform: uppercase;
}

.header-btn:hover,
.header-btn:focus {
  box-shadow: inset 0 0 0 2em #a1a3a7;
  transition: 0.5s;
}

@media (min-width: 320px) and (max-width: 576px) {
  .header-btn {
    margin-top: 15px;
  }
}

</style>
