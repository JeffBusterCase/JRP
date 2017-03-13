# JRP 0.1.1
Jruby Project Manager. Supports desktop libgdx and compiles to jar.

#### NOTE: multiple folders not implemented yet(`/src/way1/*.rb`, just `/src/*.rb`). but easy.
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
##### with the assets
`  jrp run -w assets`


##### Generate the final jar with ruby files as bootstrap.
`  jrp dist:rb`

##### Generate the final jar with ruby files as a class file.
`  jrp dist`
