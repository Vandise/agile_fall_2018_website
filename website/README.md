## Github Class Assignment

In order to experience what happens when all team members have access to a single repository, you will, as a class, modify an existing web site so it has the following:

* index.html: contains a **list** of each class member with links to each team member's page.
* One page for each class member, called `username.html` where *username* is your CVTC username. It should be located under the `people` directory.

Use Git and Github to collaborate on this project:

1. On Github, clone the repository <https://github.com/vandise/agile_fall_2017_website>

2. Create a feature branch with *git checkout -b* to do your work.

3. Add your own page to the site under the `people` folder. Your page should be a basic web-based resume, listing your education, employment experience, and other experience.
    * Name your page `username.html` where `username` is your CVTC username
    * Add a link at the bottom of the page to return to the home page.
    * If necessary, add styles to the stylesheet. But be careful **not to interfere with other people's styles.** 
       * One suggestion would be to add an ID to the body of your page, and use that ID to scope your selectors. See my page.

4. Create a link to your page on the home page of the site. **Ensure your link is alphabetical**.

5. Commit when appropriate. **Part of your grade will be based on your use of commits and commit messages.**
5. Be sure to pull and push often to keep your local master fresh. Merge your changes into your feature branch often. 
    * You use the command `git pull origin master` to pull changes from master into your master branch. Then you'll merge those changes into your own branch.
    * `git merge master` merges master into your own branch.
6. When you're done, merge your changes into the master branch with `git merge`  and push to the origin (Github).
8. Class members should try to coordinate work to avoid merge conflicts. Merge conflicts happen when two people change the same line of the same file and attempt to merge the versions together. Think about how you can avoid that. Use communication tools as best as you can.

## HTML and CSS formatting

Everyone  must conform to the same coding style to avoid merge conflicts and to make the code look like a single person wrote it. For this class use the following standards:

* Set your editor to indent using spaces, not tabs.
* Set your editor to insert two spaces for indentation.
* HTML tags should be lowercase.
* HTML attributes should be lowercase.
* HTML should use the HTML5 doctype.

### HTML5 template

~~~
<!DOCTYPE html>
<html lang="en-US">
  <head>
    <meta charset="utf-8">
    <title>Your page</title>
  </head>
  <body>
  
  </body>
</html>
~~~

Note the indentation of child elements using spaces, not tabs.

### CSS

CSS should be formatted like this:

~~~
.selector{
  color: red;
  padding: 0;
}
~~~

* Selectors should have their contents indented.
* Semicolons should be at the end of each property/value pair.

This assignment is worth 50 points. Everyone will receive an individual score based on what I see in the Git logs. 

### Your performance will be successful when:

1. You contribute your own HTML page to the site in the `people` folder.
2. Your page is a resume-type page as described in the assessment instructions.
2. Your page links back to the `index.html` page
2. You link to your page on the `index.html` page. 
4. Your entry is listed as a bullet and is alphabetical.
3. Your HTML and CSS is valid.
4. Your HTML and CSS are professionally coded
    * HTML has an HTML5 doctype
    * HTML has the language specified
    * HTML has the charset defined
    * HTML tags use lowercase tags and attributes
    * HTML attributes have double-quoted values
    * HTML tags are properly indented using spaces, **not tabs**
    * CSS properties are indented within selectors
    * CSS properties are alphabetized.
5. Commit messages are clear and explain what the commit includes in the present tense. 

I will grade this after looking at your Git repository and its history. **I do not expect perfection. I simply expect your best effort.**
