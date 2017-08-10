<p align="center">
  <a href="https://github.com/splode/bootstrap-nucleus">
    <img src="bootstrap-nucleus.png" width=125px height=125px>
  </a>
</p>

<h1 align="center">Bootstrap Nucleus</h1>
<p align="center">Bootstrap Nucleus - the essential core of Bootstrap v4.</p>

## Installation
### npm
````bash
npm install bootstrap-nucleus --save
````

````scss
@import "/node_modules/bootstrap-nucleus/dist/boostrap-nucleus.css";
````

### Download
See [https://github.com/Splode/bootstrap-nucleus/blob/master/dist/bootstrap-nucleus.min.css](https://github.com/Splode/bootstrap-nucleus/blob/master/dist/bootstrap-nucleus.min.css)

## Usage

Bootstrap Nucleus includes the essential core of Bootstrap v4 without the fluff.

Core includes:
- CSS Reboot
- Bootstrap Grid
- Bootstrap Utilities

Use Bootstrap Nucleus the same way that you would use Bootstrap v4.
````html
<main class="container">
  <section class="row d-flex">
    <article class="col-md-8">
      ...
    </article>
    <aside class="col-md-4 p-3">
      ...
    </aside>
  </section>
</main>
````

### Custom Build
Use the following to rebuild project assets:
````bash
npm run build
```` 

Use the following to bundle and minify distribution files:
```bash
npm run dist
```

## Why Nucleus?
The Bootstrap framework is an excellent tool for prototyping. In production, however, I find myself overwriting the majority of the Bootstrap component styles and retaining only the core framework components, such as the grid. 

Instead of including the entire Bootstrap framework for projects, Bootstrap Nucleus allows a project to retain the essential Bootstrap components while shedding the fluff. At 52 KB minified, Bootstrap Nucleus is less than half the size of Bootstrap's CSS framework.
