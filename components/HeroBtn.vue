<template>
  <button class="header-btn">
    <slot>Button</slot>
  </button>
</template>

<style>
.header-btn {
  font-family: 'Roboto Regular';
  font-size: 20px;
  background-color: #0b77fa;
  height: 47px;
  width: 190px;
  outline: none;
  cursor: pointer;
  border-radius: 8px;
  border: none;
  text-transform: uppercase;
}
</style>
