# HTML5 semantics

* make old IE deal with new tags:

        <!--[if lt IE 9]>
        <script src="http://html5shiv.googlecode.com/svn/trunk/html5.js">
        </script>
        <![endif]-->

(Must be in the `<HEAD>` element.)  Interestingly, `html5shim` also works.

See: https://remysharp.com/2009/01/07/html5-enabling-script

See: https://github.com/afarkas/html5shiv

* Start with `<!doctype html>`
* `<html lang="en">` never hurts.  Optional.
* In `<head>`, set character encoding with `<meta charset="utf-8">`  Note that the self-closing tag is not necessary.

## Design/workflow

* braindump all the content (types) that will be on your page;
navigation, copyright, etc. 
* categorize into primary and secondary
* Come up with a structure - what's the best way to organize these
contents?

* Very common to use `<article>` for a comment, since it can stand on
it's own, *at least* within the section it exists.
  
