This is an app for the [Elefant CMS](http://github.com/jbroadway/elefant)
that provides support for [Typekit](http://typekit.com/) custom font hosting
service.

## Usage

Step 1. Add the following to the `<head>` of your layout:

```html
{# typekit/XXXXXX #}
```

This will hard-code the necessary Javascript into your layout. Be sure to
change the XXXXXX value to the ID provided by Typekit. You can find it on
their website once you've registered.

Step 2. Add some fonts to your kit on [typekit.com](http://typekit.com/).

Step 3. Add the selectors for your chosen fonts to the elements you want to
style. For example:

```css
h1 {
	font-family: cody;
}
```

You should now see your `<h1>` elements styled using the
[Cody Web](http://typekit.com/fonts/cody-web) font from
[typekit.com](http://typekit.com/).
