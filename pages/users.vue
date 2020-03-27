<template>
  <div>
    <h1>Users</h1>
    <div v-for="user in users" :key="user.id">
      {{ user.name }}
    </div>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        users: [
          {
            id: '1',
            name: 'Nitya'
          },
          {
            id: '2',
            name: 'Arav'
          },
          {
            id: '3',
            name: 'Heli'
          },
          {
            id: '4',
            name: 'Het'
          }
        ]
      }
    }

  }
</script>

<style lang="scss" scoped></style>
