# App Component

From now on we will focus on `src/app.tsx` file, where we'll implement most of the things for our app.

We have already some code within our `app.tsx`. Let's explore a bit.

```tsx
// custom helper to generate unique ID for our TODOS
import { uuidv4 } from './shared';
```

```tsx
// we're importing our app.css that consist all of our css definitions that we gonna leverage
import './app.css';
```

```tsx
// our initial data set of our TODOS. we'll use this later
const initialState = [{...}]
```

### 🙇‍♀️ Exercise

1. log into console `initialState`
2. try to change content of Hello World to check if everything still works!

Cool, let's implement input for adding new todo!

---

[🚀 Adding new Todo](./5-add-todo.md)
