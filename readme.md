# Mammoth Go-Live Checklist

## 1. Browser Testing

#### Desktop 

1. IE 8 
2. IE 9 
3. IE 10
4. Chrome  (latest build)
5. Firefox (latest build)
6. Safari (latest build)

#### Mobile 

1. iOS (latest build) 
2. Android 



## 2. Browser images 

1. Favicons - Reference a `.png` in the head, and also add a `.ico` in the root directory.
2. iOS Touchicon - Add a **152px x 152px** `.png` called `apple-touch-icon-precomposed.png` to the root directory.



## 3. Webfonts 

1. [Fonts.com](http://fonts.com) & [Typography.com](http://typography.com) – Switch project from development to live?
2. Typekit on IE8 – Make sure your type haven’t gone italic ([this is a thing](http://help.typekit.com/customer/portal/articles/6855-using-multiple-weights-and-styles))



## 4. Performance

1. Minify and combine all CSS files [with Grunt](http://gruntjs.com/). 
2. Minify and combine all ext. JS files (excl. [Modernizr](http://modernizr.com/)) [with Grunt](http://gruntjs.com/). 
3. Make sure all ext. JS files (excl. [Modernizr](http://modernizr.com/)) are at the bottom of the document. 
4. Run all images through an image optimiser (you can do this with [Grunt](http://gruntjs.com/), or [ImageOptim](http://imageoptim.com/)).



## 5. General

1. Add Google Analytics.
2. Ensure all web forms go to a valid client email. 
3. Test form validation. 
4. Run your HTML through the [W3 Validator](http://validator.w3.org/). 
5. Are there valid page titles?
6. Is there a valid meta description?
7. Are there valid meta keywords?
8. Have you tested forms work on IE8 & 9 (sometimes the form will submit the placeholder text and not the value)?
9. 404 page. 
10. Some sort of print CSS optimisation. 
11. Check content has been added to utility pages (Cookies, etc). 
12. Make sure there aren’t any `console.log` in your JavaScript. 



## 6. WordPress

Make sure search engine indexing is switched in – `Settings / Reading / Search Engine Visibility`