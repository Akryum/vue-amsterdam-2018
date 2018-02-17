# vue-amsterdam-2018

Demo sources of my talk at [Vue Amsterdam 2018](http://www.vuejs.amsterdam/)

Slides of the talk: [Vue, Apollo and GraphQL: the Ultimate Stack](http://slides.com/akryum/vue-amsterdam-2018#/)

**Step 1**

:star: Create a new vue-cli 3 project and invoke the apollo plugin:

```bash
yarn global add @vue/cli
vue create my-app
cd my-app
yarn add -D vue-cli-plugin-apollo
vue invoke apollo
# ? Add a GraphQL API Server? Yes
```

**Step 2**

:pencil: Edit the `App.vue` file to try the `ApolloExample.vue` component:

```js
import HelloWorld from './components/HelloWorld.vue'
```

To:

```js
import HelloWorld from './components/ApolloExample.vue'
```

**Step 3**

👾 You can play with the GraphQL API at [http://localhost:4000/](http://localhost:4000/).

:ok_hand: Enjoy! :cat2: (Also, [read the docs](https://github.com/Akryum/vue-apollo).)
