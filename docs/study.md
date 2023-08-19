Nest lets you build apis and gives you a great architecture to work on

When we make a request, this is the path in the repository that it follows:
- requisição HTTP
- controller
- service

## Modules
We can think of the [app.module.ts](../src/app.module.ts) as the root of the application

Modules are a way to encapsulate a related set of capabilities
- Modules can depend on each other
![Modules example](modules_example.png)
- To create new modules, use `nest generate module <module_name>`, like follows:

![New module](new_module.png)