<template>
  <div id="app">
    <AddToDo />
    <ToDoList />
    <SelectedToDo />
    <DoneList />
  </div>
</template>

<script>
import AddToDo from './components/addToDo'
import ToDoList from './components/toDoList'
import SelectedToDo from './components/selectedToDo'
import DoneList from './components/doneList'

export default {
  name: 'App',
  components: {
    AddToDo,
    ToDoList,
    DoneList,
    SelectedToDo
  },
  data(){
    return{
      data: json
    }
  },
  beforeCreate() {
    console.log(this.data)
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
