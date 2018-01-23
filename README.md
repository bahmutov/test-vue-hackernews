## End to end testing is fun

In this blog post I will show how to test a HackerNews clone without pulling out hair.

There is an elegant and fast Vue.js 2 HackerNews clone made by the framework's author himself: [vuejs/vue-hackernews-2.0](https://github.com/vuejs/vue-hackernews-2.0) with live demo hosted at [https://vue-hn.now.sh/](https://vue-hn.now.sh/). The clone has all the bells and whistles one can expect from a modern progressive application: includes server-side rendering, inlined CSS, routing, single file components, etc. There is only one thing the code is missing - tests! Hmm.

![HackerNews with Vue](images/hn.png)

What would it take to quickly confirm that this project is working? Would you need to jump through hoops if you wanted to add tests? Would you write unit tests or would end-to-end tests be better? Would the tests work in a modern browser or using JavaScript DOM emulation? Would the entire experience be full of pain and misery?

I will show you can _quickly_ write lots of end-to-end tests without any pain. These tests are most important ones - because they ensure that the deployed application is actually usable by the end user. My tool of choice is [Cypress](https://www.cypress.io) - our open source free test runner.

I start testing by forking the repository and getting a local copy.

```shell

```
