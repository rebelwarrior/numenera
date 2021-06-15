# READ ME

Link to site: https://rebelwarrior.github.io/numenera/

This is a Jekyll Website personal project to learn [Bulma CSS framework](https://bulma.io/) and play with CSVs in Jekyll.

Content from Numenera Core Books © Monte Cook Games
Original Content and Code © David Acevedo 

Learned:
1. Bulma doesn't work well with markdown
	1. Bulma has no list CSS
	2. Bulma has no blockquote CSS (WTF)
	3. Bulma doesn't style plain h1, h2, etc. by default
	4. Bulma's margin/padding to the top of titles is ___horrendous___. !!!!!!!
	5. Table footers seem to display at the top...?
2. Bulma __tables look good__ and you can use highlights to give a better look to the header. 
3. Hamburger menu requires a data-target which is not well documented in the Bulma examples. Looks good and simple to make. 
4. Learned how to add classes to elements in Kramdown. `{:.class-name}`
5. Jekyll hosted on GitHub needs two config files one for local development and one for GitHub due to url (site url) property. (see no. 9 below too)
6. Borrowed list styling from Zurb's Foundation. 
7. Ruby 3.0 requires explicit 'webbrick' call out in Gemfile.
8. Bulma requires some fiddling to look good on mobile for markdown files. [Spacing Helpers](https://bulma.io/documentation/helpers/spacing-helpers/)
9. Found a better way to use a dev config using the gem `yaml_extend`
10. Doesn't seem like you can do Markdown links at the bottom with Jekyll. 
11. How do I get that chevron on the dropdowns again? With `navbar-link`. 
12. Table of Contents **(TOC) can be done with Jekyll alone** and Bulma has an advantage because it doesn't require a header to give header css, you can remove a header from the TOC but have it look the same. See "Location" on the settings page. 

Exploring:
Bulma's spacing helpers: pretty cool 
Jekyll site-url with github: set `url` on the _config.yml to the github produced url. 
Alias: `jekyll serve --config _config.dev.yml`


## Conclussion 

Bulma is interesting but it's not ready. Documentation is not quite there particularly of the missing JS needed for many features to work and the complete lack of elements like blockquote and lists make it pretty weak for markdown. 

## License 
Code licensed on the MIT license. 
Bulma also licensed on the MIT license as well. 