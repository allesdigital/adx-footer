Anwedungsweise des ADX-Footers

Der Footer wird mit Hilfe folgendem Javascriptcode in die Website eingefügt:

`<script
async
src="http://localhost:3001/footer.js"
charset="utf-8">
</script>`

Falls der ADX-Footer einen bisherrigen Footer ersetzen soll, dieser aber als Backup erhalten bleiben soll, muss die zu ersetzende Div-Box einfach id="adx-footer" besitzen und sie wird mit dem ADX-Footer ersetzt.
Falls der Body keine Div-Box mit dieser ID besitzt wird der ADX-Footer automatisch am Ende des Bodys eingefügt.

---------- English Version----------

Usage of the ADX Footer

The footer is inserted into the website using the following JavaScript code:

`<script
async
src="http://localhost:3001/footer.js"
charset="utf-8">
</script>`

If the ADX-Footer is intended to replace an existing footer but the original footer should be kept as a backup, the div box to be replaced simply needs to have the id="adx-footer," and it will be replaced by the ADX-Footer.

If the body does not contain a div box with this ID, the ADX-Footer will be automatically inserted at the end of the body.
