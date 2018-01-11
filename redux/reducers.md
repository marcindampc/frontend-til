# Reducers 
* specify how the application's state changes in response to actions sent to the store
* actions only describe the fact that something happened, but don't describe how the application's state changes.

## sample reducer:
* let's handle SET_VISIBILITY_FILTER 1 All it needs to do is to change visibilityFilter on the state

```javascript
function todoApp(state = initialState, action) {
  switch (action.type) {
    case SET_VISIBILITY_FILTER:
      return Object.assign({}, state, {
        visibilityFilter: action.filter
      })
    default:
      return state
  }
}
```
Note that:

We don't mutate the state. We create a copy with ```Object.assign()```. ```Object.assign(state, { visibilityFilter: action.filter })``` is also wrong: it will mutate the first argument. You must supply an empty object as the first parameter. You can also enable the object spread operator proposal to write ```{ ...state, ...newState }``` instead.

We return the previous state in the default case. It's important to return the previous state for any unknown action.


* combineReducers
```jsx
const reducer = combineReducers({
  counter,
  tasks
})
```
