# vue-property-decorator-snippets README

This extension adds Vue Property Decorator Code snippets into Visual Studio Code.

## Features

| Prefix               | Vue Property Decorator Snippet Content                                             | Doc                                                                                                                                                                  |
| -------------------- | ---------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `vuedec-import`      | `import { Vue, Component, Prop, Watch, Emit, Ref } from "vue-property-decorator";` |                                                                                                                                                                      |
| `vuedec-comp`        | `@Component export default class Compenent extends Vue {...}`                      |                                                                                                                                                                      |
| `vuedec-newComp`     | `Equivalent to vuedec-import and vuedec-comp`                                      |                                                                                                                                                                      |
| `vuedec-prop`        | `@Prop() readonly variable!: type;`                                                | [→](https://github.com/kaorun343/vue-property-decorator#-propoptions-propoptions--constructor--constructor---decorator)                                              |
| `vuedec-propsync`    | `@PropSync('name', { type: type }) variable!: type;`                               | [→](https://github.com/kaorun343/vue-property-decorator#-propsyncpropname-string-options-propoptions--constructor--constructor---decorator)                          |
| `vuedec-data`        | `variable: type = defaultValue;`                                                   |                                                                                                                                                                      |
| `vuedec-watch`       | `@Watch(variableToWatch) onVariableChanged(val: type, oldVal; type) {...}`         | [→](https://github.com/kaorun343/vue-property-decorator#-watchpath-string-options-watchoptions---decorator)                                                          |
| `vuedec-model`       | `@Model() readonly variable!: type;`                                               | [→](https://github.com/kaorun343/vue-property-decorator#-modelevent-string-options-propoptions--constructor--constructor---decorator)                                |
| `vuedec-prov`        | `@Provide() variable = value;`                                                     | [→](https://github.com/kaorun343/vue-property-decorator#-providekey-string--symbol--injectoptions--from-injectkey-default-any---injectkey-decorator)                 |
| `vuedec-provreact`   | `@ProvideReactive() variable = value;`                                             | [→](https://github.com/kaorun343/vue-property-decorator#-providereactivekey-string--symbol--injectreactiveoptions--from-injectkey-default-any---injectkey-decorator) |
| `vuedec-inject`      | `@Inject() readonly variable!: type;`                                              | [→](https://github.com/kaorun343/vue-property-decorator#-providekey-string--symbol--injectoptions--from-injectkey-default-any---injectkey-decorator)                 |
| `vuedec-injectreact` | `@InjectReactive() variable!: type;`                                               | [→](https://github.com/kaorun343/vue-property-decorator#-providereactivekey-string--symbol--injectreactiveoptions--from-injectkey-default-any---injectkey-decorator) |
| `vuedec-emit`        | `@Emit(event) myMethod() { ... }`                                                  | [→](https://github.com/kaorun343/vue-property-decorator#-emitevent-string-decorator)                                                                                 |
| `vuedec-ref`         | `@Ref() readonly aComponent!: AComponent`                                          | [→](https://github.com/kaorun343/vue-property-decorator#-refrefkey-string-decorator)                                                                                 |

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

Check [CHANGELOG.md](https://github.com/antsteyer/vscode-vue-decorator-snippets/blob/master/CHANGELOG.md)
