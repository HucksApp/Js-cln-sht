# Javascript Clean sheet




## Exports

* Default exports -> `export default <default_member> `
* Export non default member one by one -> `export <non_default_membes>`
* Export non default member as object members -> `export {<non_default_members>, ...}`
  * Export and alias members -> `export {<non_default_members>, .... as <alias_names>, ...}`


##  Imports
* Importing a module with a default member -> `import <default_member> from <module_name> `
  * Import and alias default member -> `import <default_member> as <alias_name> from <module_name>`
* Import non-default members -> `import {<non_default_members>, ...} from <module_name> `
* Importing all exported members -> `import * from <module_name>`



