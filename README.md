Version 1
It should have a place to store todos
It should have a way to display todos
It should have a way to add new todos
It should have a way to change a todo
It should have a way to delete a todo 

Verson 2 

It should have a function to display todos
It should have a function to add todos
It should have a function to change todos
It should have a function to delete todos
		
*******FUNCTION TO DISPLAY TODO*********

var todos = ['item 1', 'item 2', 'item 3']

function displayTodos (){
	console.log('My todos:', todos);
}

then you need to call the function with:
displayTodos()

********FUNCTION TO ADD TODO****************
function addTodo(){
	todos.push('new todo');
}
addTodo() // to add "new todo"
displayTodo() //will show the new list of todos 

**********FUNCTION TO CHANGE TODOS************

function changeTodo(position, newValue){
	todos[position] = newValue;
	display(Todos);
}
changeTodo(0, 'changed')
displayTodos()

function deleteTodo(position){
	todos.splice(position, 1);
	displayTodos();
}

Version 9 

There should be an <li> element for every todo
Each <li> should contain .todoText
Each <li> should show .completed 

Version 10 

There should be a way to create delete buttons
There should be a delete button for each todo
Each li should have an id that has the todo position
Delete buttons should have access to the todo id
Clicking delete should update todoList.todos and the DOM
