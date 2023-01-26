
# [learning-angular](https://eeoooue.github.io/learning-angular/)

host repository for Angular apps

.js files for an app hosted in this repo are here: 
> https://eeoooue.github.io/learning-angular/docs

while the GitHub Pages setup means our app will look for them here:
> https://eeoooue.github.io/docs

when building an Angular app to host on GitHub Pages, we'll need to [change the base-href tag](https://stackoverflow.com/questions/50106156/)

---

**index.html**

```html
<html>
    <head>
        <base href="/learning-angular/">
        ...
    </head>

    <body>
        ...
    </body>
</html>
```

---

**Angular CLI**

```
ng build --base-href=/learning-angular/
```
