<template>
  <Container class="px-6 py-16">
    <div class="grid md:grid-cols-2 items-center gap-12">
      <!-- Texto principal -->
      <div class="space-y-6">
        <h1 class="text-5xl md:text-6xl font-extrabold">
          ¡Descubre la movilidad eléctrica en Querétaro!
        </h1>
        <p class="text-lg text-gray-600">
          SEV Querétaro – Innovación, eficiencia y compromiso con el medio ambiente.
        </p>

      </div>
      <!-- Imagen principal -->
      <Card as="figure" class="overflow-hidden rounded-lg shadow-lg">
        <!-- Reemplaza con la ruta a la imagen real del E-Wan Cross azul metálico -->
        <img
          src="/banner.jpg"
          alt="E-Wan Cross en SEV Querétaro"
          class="w-full h-auto object-cover"
        />
      </Card>
    </div>

    <!-- Características Destacadas -->
    <div class="mt-16">
      <h2 class="text-3xl font-bold text-center mb-8">Características Destacadas</h2>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
        <Card class="p-6 rounded-lg shadow-md hover:shadow-lg transition-shadow">
          <Badge color="primary" class="mb-4">E-Wan Cross</Badge>
          <ul class="list-disc list-inside space-y-2 text-gray-700">
            <li>Autonomía: hasta 300 km por carga</li>
            <li>Espacio para 5 pasajeros</li>
            <li>Precio desde $299,300 MXN</li>
          </ul>
        </Card>
        <Card class="p-6 rounded-lg shadow-md hover:shadow-lg transition-shadow">
          <Badge color="primary" class="mb-4">E-Nat</Badge>
          <ul class="list-disc list-inside space-y-2 text-gray-700">
            <li>Autonomía: hasta 419 km por carga</li>
            <li>Ideal para la vida urbana</li>
            <li>Precio desde $615,900 MXN</li>
          </ul>
        </Card>
        <Card class="p-6 rounded-lg shadow-md hover:shadow-lg transition-shadow">
          <Badge color="primary" class="mb-4">E-Tus</Badge>
          <ul class="list-disc list-inside space-y-2 text-gray-700">
            <li>Autonomía: hasta 415 km por carga</li>
            <li>Confort y seguridad en cada viaje</li>
            <li>Precio desde $595,900 MXN</li>
          </ul>
        </Card>
      </div>
    </div>
    <div style="text-align:center; padding: 20px;"><img src="https://hitscounter.dev/api/hit?url=sevqro.mx&label=Visitantes&icon=person-raised-hand&color=%23b02a37"></div>
  </Container>
  
</template>

<script setup>
import { useHead } from '#app'

useHead({
  script: [
    {
      src: "https://umami-production-0033e.up.railway.app/script.js",
      async: true,
      'data-website-id': "618f5936-c621-49e5-94b9-05e6ebe8bd04"
    }
  ]
})
</script>

<style scoped>
/* Estilos específicos de la página */
</style>