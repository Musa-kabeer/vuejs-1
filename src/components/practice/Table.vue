<template>
  <div>
    <input type="text" v-model="surname" />
    <input type="text" v-model="lastname" />
    <button @click="addData()">Click To Add</button>
    <table class="border-2">
      <tr class="border-2">
        <thead>
          Surname
        </thead>
        <thead>
          Lastname
        </thead>
      </tr>
      <tr v-for="data in dataStore" :key="data.id" class="border-2">
        <td class="border-2">{{ data.surname }}</td>
        <td class="border-2">{{ data.lastname }}</td>
      </tr>
    </table>
  </div>
</template>

<script>
export default {
  data() {
    return {
      count: 0,
      surname: "",
      lastname: "",
      dataStore: [],
    };
  },
  methods: {
    addData() {
      this.count++;
      this.dataStore.push({
        id: this.count,
        surname: this.surname,
        lastname: this.lastname,
      });
    },
  },
};
</script>

<style scoped></style>
