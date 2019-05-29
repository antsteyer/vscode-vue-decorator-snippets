# vue-property-decorator-snippets README

This extension adds Vue Property Decorator Code snippets into Visual Studio Code.

## Features

| Prefix           | Vue Property Decorator Snippet Content                                        |
| ---------------- | ----------------------------------------------------------------------------- |
| `vuedec-import`  | `import { Vue, Component, Prop, Watch, Emit } from "vue-property-decorator";` |
| `vuedec-comp`    | `@Component export default class Compenent extends Vue {...}`                 |
| `vuedec-newComp` | `Equivalent to vuedec-import and vuedec-comp`                                 |
| `vuedec-prop`    | `@Prop() readonly variable!: type;`                                           |
| `vuedec-data`    | `variable: type = defaultValue;`                                              |
| `vuedec-watch`   | `@Watch(variableToWatch) onVariableChanged(val: type, oldVal; type) {...}`    |

<br />

| Prefix                  | Vuex Module Decorator Snippet Content                                                                                                                    |
| ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `vuexdec-module`        | `import {... } from "vuex-module-decorators"; @Module export default class MyModule extends VuexModule {...}`                                            |
| `vuexdec-dynamicModule` | `import {... } from "vuex-module-decorators"; @Module({ dynamic: true, store, name: "myModule"}) export default class MyModule extends VuexModule {...}` |
| `vuexdec-mutation`      | `@Mutation myMutation(payload: type) {...}`                                                                                                              |

## Requirements

- [Vue Property Decorator](https://github.com/kaorun343/vue-property-decorator) : to use all `vuedec-` snippets
- [Vuex Module Decorators](https://github.com/championswimmer/vuex-module-decorators) : to use all `vuexdec-` snippets

## Supported Languages

- `vue` (.vue)
- `typescript` (.ts)

## Known Issues

Not yet.

## Release Notes

### 1.0.0

Initial release of Vue Property Decorator Snippets
