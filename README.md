# JRP
Jruby Project Manager. Supports desktop libgdx and compiles to jar.

### Currently in really deep dev. (multiple folders not implemented yet. but easy.)
### Only Linux yet!


##### Needs
 * `file-roller` installed (already installed on ubuntu)
 * jruby compiler `jrubyc` (comes with jruby).

##### Create a new Project
`  jrp new HelloWorld`

##### Create a new LibGDX desktop project 
`  jrp new -lgdx HelloWorld`

#### Inside project folder
##### Run project 
`  jrp run`

##### Generate the final jar with ruby files as bootstrap.
`  jrp dist:rb`

##### Generate the final jar with ruby files as a class file.
`  jrp dist`
