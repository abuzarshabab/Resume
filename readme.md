# Abuzar Shabab Resume

A digital resume website built based on the content from my personal REAL [resume](./assets/resume.pdf) 


## Dark Mode Preview

<img src="assets\images\darkPreview.PNG">

## Light Mode Preview

<img src="assets\images\lightPreview.PNG">

## Switching between color themes

This website has no auto toggle theme switcher, therefor to change themes you must manual go into `/styles/main.css` and the css variables to use either theme. Default is dark, so do the following here:

```css
--mainTextColor:var(--mainTextColor-light); 
--secondaryTextColor:(--secondaryTextColor-light);
--mainLinkColor:var(--mainLinkColor-light);
--mainBorderColor:var(--mainBorderColor-light);
--mainBgColor:var(--mainBgColor-light);
```