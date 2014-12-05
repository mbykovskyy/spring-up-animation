# spring-up-animation
[Polymer][polymer] web component for a spring up effect.

## Install

```bash
bower install --save mbykovskyy/spring-up-animation
```

## Usage

```html
<link rel="import" href="spring-up-animation.html">

<div id="box"></div>
<spring-up-animation id="spring-up" duration="500" easing="ease-out"></spring-up-animation>

<script>
  document.addEventListener('polymer-ready', function() {
    var animation = document.getElementById('spring-up');
    animation.target = document.getElementById('box');
    animation.play();
  });
</script>
```

See [component page][spring-up-animation] for details and demo.

[polymer]: http://polymer-project.org "Polymer"
[spring-up-animation]: http://mbykovskyy.github.io/spring-up-animation "Component Page"
