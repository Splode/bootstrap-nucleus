# Bootstrap Nuclueus
Bootstrap Nucleus includes the essential core of Bootstrap v4 without the fluff. The core components include the following:
- CSS Reboot
- Bootstrap Grid
- Bootstrap Utilities

## Installation
### npm
````bash
npm install bootstrap-nucleus --save
````
### Direct
Download and unzip this repo. Copy the files from the `dist` directory and link to the boostrap-nucleus stylesheet of your choice.
````HTML
<link rel="stylsheet" href="bootstrap-nucleus.min.css">
````

## Usage
Use Bootstrap Nucleus the same way that you would use Bootstrap v4.
````html
<main class="container">
  <section class="row d-flex">
    <article class="col-md-8">
      ...
    </article>
    <aside class="col-md-4">
      ...
    </aside>
  </section>
</main>
````

### Custom Build
Bootstrap Nucleus uses node-sass to build project assets. 
````bash
npm run build
````