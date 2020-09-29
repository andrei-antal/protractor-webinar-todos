# Protractor workshop - Todos app

## 0. Initial setup

* Clone the repository:

```
git clone https://github.com/andrei-antal/protractor-webinar-todos.git
```

* Install dependencies:

```
cd protractor-webinar-todos
npm install
```

* Test app is running

```
ng serve
```

* Run e2e tests

```
npm run e2e-watch
```

## 1. Updating todo text

- Add input to the todo input
- Check if todo-text is updated accordingly
- Remove the input
- Check if todo-text is updated accordingly

## 2. Verify adding empty todos

- Add input
- Check button enabled
- Remove input
- Check button disabled

## 2. Add single todo

- Add input to the todo input
- Click the submit button
- Check todo list has correct length
- Check the text of the first item


## 3. Add multiple todos

- Add todo -> repeat a number of times
- Check todo list has correct length
- Check the texts of items

## 4. Delete single todo

- Add input to the todo input
- Click the submit button
- Check delete bulk is enabled
- Click on the delete button
- Check list is empty
- Check delete bulk is disabled

## 5. Complete todo

- Add todo
- Complete todo
- Check that correct class has been applied to element
- Check that element was not deleted
- CHeck no other elements have been affected

## 6. Delete completed todos

- Add a couple of todos
- Complete (check) a number of them
- Click on bulk delete
- Check list count updated accordingly
- Check correct items remained in list

## 7. E2e flow
- Correctly adds todos
- Correctly completes todos
- Correctly removes todos
- Check summary
