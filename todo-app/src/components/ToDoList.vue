<template>
  <div>
    <ul>
        <li> Todo A </li>
        <li> Todo B </li>
        <li> Todo C </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'ToDoList',
  data() {
    return {
      todos: [{
        title: 'Todo A',
        project: 'Project A',
        done: false,
      }, {
        title: 'Todo B',
        project: 'Project B',
        done: true,
      }, {
        title: 'Todo C',
        project: 'Project C',
        done: false,
      }, {
        title: 'Todo D',
        project: 'Project D',
        done: false,
      }],
    };
  },
};
</script>
<style>
</style>
