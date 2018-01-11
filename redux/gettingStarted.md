# What do we need?
## import:
* ```Provider``` from ```react-redux```
  * then put it into:
```
ReactDOM.render(
  <Provider store={store}>
  ```
  Route and so
  ```
  </Provider>
  ```

## create inside project:
* store.js
  * in store.js ```import```:
    * ```javascript import { compose, createStore, combineReducers } from 'redux'``` 
    and
    ```import persistState from 'redux-localstorage'```
    * and than create:
    ```javascript
    const composeEnhancers = window.__REDUX_DEVTOOLS_EXTENSION_COMPOSE__ || compose;
    ```
    and
    ```javascript
    const enhancer = composeEnhancers(
    persistState([], { key: 'jfdd8-app-v2'}),
    )
    ```
    we will probably also need:
    ```javascript
    const reducer = combineReducers({
    counter,
    tasks
    })
    ```
    and
    ```javascript
    const store = createStore(
    reducer,
    enhancer
    )
    ```
    * finally remember to: ```import store from './store'``` in ```index.js```
