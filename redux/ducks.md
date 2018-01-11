# Ducks - explenation
* https://github.com/erikras/ducks-modular-redux
## Actions
* put the into variables as i.e.:
```
const DELETE = 'tasks/DELETE';
const ADD = 'tasks/ADD_TASK';
```
## Action creators
* we're exporting them
```
export const addTask = taskName => ({
  type: ADD,
  taskName
});
```
or
```
export function loadWidgets() {
  return {
  type: LOAD };
}
```
