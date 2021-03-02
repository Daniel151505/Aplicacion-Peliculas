<template>
  <div id="filters">
      <h3>Filtros</h3>
      <p> Calificación más alta </p>
      <p> Calificación más baja </p>
      <p> Año mas nuevo </p>
      <p> Año mas viejo </p>
  </div>
</template>

<script>
export default {

}
</script>

<style lang='scss' scoped>
	#filters {
		text-align: left;
		color: rgb(143, 143, 143);
		cursor: pointer;

		p {
			margin-left: 10px;
		}
	}
</style>