<template>
  <div>
    <b-table striped hover :items="items" :fields="fields"></b-table>
  </div>
</template>

<script>
export default {
  data() {
    return {
      fields: [
        { key: 'full_name', label: 'Nombre' },
        { key: 'nickname', label: 'Apodo' },
        { key: 'email', label: 'Correo Electónico' },
      ],
      items: [

      ],
    };
  },
};
</script>
