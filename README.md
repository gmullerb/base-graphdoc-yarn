# Base project for GraphQL schema HTML documentation generation

__________________

Base project for GraphQL schema HTML documentation generation using [`graphdoc`](https://www.npmjs.com/package/@2fd/graphdoc) and [graphdoc plugins](https://graphdoc-plugins.github.io/) with yarn.

It used [Pokemon GraphQL schema](https://github.com/lucasbento/graphql-pokemon).

Take a look to the [Online generated documentation](https://gmullerb.gitlab.io/base-graphdoc-yarn).

(for npm go to [base-graphdoc-npm](https://github.com/gmullerb/base-graphdoc-npm))

__________________

## Prerequisites

* [Node](https://nodejs.org/en)/[Yarn](https://yarnpkg.com/).
* [Git](https://git-scm.com/downloads) (only if the project is going to be cloned).

## Getting it

In the desired folder, clone the project[1] executing:

```sh
git clone https://github.com/gmullerb/base-graphdoc-yarn
```

or

```sh
git clone https://gitlab.com/gmullerb/base-graphdoc-yarn
```

> [1] [Cloning a repository](https://help.github.com/articles/cloning-a-repository/)

## Running it

[`package.json`](../package.json) script:

* `doc`: generates GraphQL schema HTML documentation using:
  * [`graphdoc`](https://www.npmjs.com/package/@2fd/graphdoc).
  * [`graphdoc-plugin-flexible`](https://graphdoc-plugins.github.io/docs/graphdoc-plugin-flexible.html).
  * [`graphdoc-plugin-operations`](https://graphdoc-plugins.github.io/docs/graphdoc-plugin-operations.html).
  * [`graphdoc-plugin-erase`](https://graphdoc-plugins.github.io/docs/graphdoc-plugin-erase.html).
  * [`graphdoc-plugin-schema`](https://graphdoc-plugins.github.io/docs/graphdoc-plugin-schema.html).

```sh
  yarn run doc
```

Generated HTMLs will be in folder `docs`.

(Take a look to the [Online generated documentation](https://gmullerb.gitlab.io/base-graphdoc-yarn))

__________________

## Contributing

* **Use it**.
* **Share it**.
* [Give it a Star](https://github.com/gmullerb/base-graphdoc-yarn).
* [Propose changes or improvements](https://github.com/gmullerb/base-graphdoc-yarn/issues).
* [Report bugs](https://github.com/gmullerb/base-graphdoc-yarn/issues).

## License

[MIT License](LICENSE.txt)

__________________

## Remember

* Use code style verification tools => Encourages Best Practices, Efficiency, Readability and Learnability.
* Code Review everything => Encourages Functional suitability, Performance Efficiency and Teamwork.
* If viable, Start testing early => Encourages Reliability and Maintainability.

## Additional words

Don't forget:

* **Love what you do**.
* **Learn everyday**.
* **Learn yourself**.
* **Share your knowledge**.
* **Think different!**.
* **Learn from the past, dream on the future, live and enjoy the present to the max!**.
* **Enjoy and Value the Quest** (It's where you learn and grow).

At life:

* Let's act, not complain.
* Be flexible.

At work:

* Let's give solutions, not questions.
* Aim to simplicity not intellectualism.
