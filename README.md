Anwedungsweise des ADX-Footers

Der Footer wird mit Hilfe folgendem Javascriptcode in den Head der Website eingefügt:
`<script
async
src="https://embed.allesdigital.io/footer.js"
charset="utf-8">
</script>`

Wenn es sich um ein Projekt mit Nuxt und Vue.js handelt, wird folgender Javascriptcode in das passende Template gepackt:
`<script setup>
useHead({
  script: [
    {
      async: true,
      src: "https://embed.allesdigital.io/footer.js",
      type: "text/javascript",
    },
  ],
});
</script>`

Falls der ADX-Footer einen bisherrigen Footer ersetzen soll, dieser aber als Backup erhalten bleiben soll, muss die zu ersetzende Div-Box einfach `id="adx-footer"` besitzen und sie wird mit dem ADX-Footer ersetzt.
Falls der Body keine Div-Box mit dieser ID besitzt wird der ADX-Footer automatisch am Ende des Bodys eingefügt.

Besten Falls sollte aber mindestens immer folgende Div-Box vorhanden sein, damit ein Backup vorhanden ist, falls das javascript nicht geladen werden kann.
`<div id="adx-footer">Made with ♥ by
          <a href="https://www.allesdigital.io">allesdigital</a></div>`

---------- English Version----------
Usage of the ADX Footer

The footer is inserted into the websites head using the following JavaScript code:

`<script
async
src="https://embed.allesdigital.io/footer.js"
charset="utf-8">
</script>`

When dealing with a project using Nuxt and Vue.js, the following JavaScript code is placed in the appropriate template:
`<script setup>
useHead({
  script: [
    {
      async: true,
      src: "https://embed.allesdigital.io/footer.js",
      type: "text/javascript",
    },
  ],
});
</script>`

If the ADX-Footer is intended to replace an existing footer but the original footer should be kept as a backup, the div box to be replaced simply needs to have the `id="adx-footer"` and it will be replaced by the ADX-Footer.

If the body does not contain a div box with this ID, the ADX-Footer will be automatically inserted at the end of the body.

Ideally, however, at a minimum, the following div box should always be present to ensure a backup in case the JavaScript cannot be loaded.
`<div id="adx-footer">Made with ♥ by
          <a href="https://www.allesdigital.io">allesdigital</a></div>`
