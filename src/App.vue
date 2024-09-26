<script setup lang="ts">
import AddTransaction from './components/AddTransaction.vue';
import Balance from './components/Balance.vue';
import Header from './components/Header.vue';
import IncomeExpenses from './components/IncomeExpenses.vue';
import TransactionList from './components/TransactionList.vue';
</script>

<template>
  <div class="container mx-auto p-16 min-h-screen">
    <Header />
    <Balance />
    <IncomeExpenses />
    <TransactionList />
    <AddTransaction />
  </div>
</template>

<style scoped></style>
