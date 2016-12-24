# JRP
Jruby Project Manager. Supports desktop libgdx and compiles to jar.

### Currently in really deep dev. (yet just run with one file)
### Only Linux yet!


##### The command `jrp dist` requires
 * `file-roller` installed (already installed on ubuntu)
 * jruby compiler `jrubyc` (comes with jruby).

##### Create a new Project
`  jrp new HelloWorld`

##### Run project 
inside project folder
`  jrp run`

##### Generate final jar
`  jrp dist:rb`

##### Compile to jruby files to .class, Generate final jar
`  jrp dist`
