# JRP 0.1.7
Jruby Project Manager. Supports desktop libgdx and compiles to jar.

#### Important Information: 
 * multiple folders doesn't work: "`/src/way1/*.rb`". Yet will be in a future update.
 * As the program uses bash and common LINUX utilities, it is for LINUX.
 * The program supports jruby version ~1.7.9

#### Needs
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

##### leave runned file
`  jrp run -w assets -l`

##### Generate the final jar with ruby files as bootstrap.
`  jrp dist:rb`

##### Generate the final jar with ruby files as a class file.
`  jrp dist`
