<template>
  <form class="search-form">
    <input type="search" placeholder="Buscar" />
    <button>
      <img src="@/components/images/icons/search.svg" alt="Buscar" />
    </button>
  </form>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.search-form {
  position: relative;
  width: max-content;
  input {
    border: none;
    border-radius: 1rem;
    box-shadow: 0px 5px 5px rgba(#000000, 0.08);
    padding: 0.5rem 1rem;
    &::placeholder {
      color: #a9b0be;
    }
  }
  button {
    align-items: center;
    background: #ff895f;
    border: none;
    border-radius: 5rem;
    display: grid;
    height: 30px;
    justify-items: center;
    position: absolute;
    right: 3px;
    top: 50%;
    transform: translateY(-50%);
    width: 30px;
  }
}
</style>
