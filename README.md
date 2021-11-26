<!-- ================
====First Commit====
=====Nov 24, 21====== -->

In this commit, I was able to put together the site in a rather plain way. There are many things wrong with this page. However, they are rather minor details. Most of the site is responsive, but not in the most elegant way possible. My CSS is also a giant mess.

x
Goals for next commit:

- Refactor CSS to make it much more clean.
    a. Learn about utility classes
    b. Learn about custom properties
    c. Review types of selectors

- Apply proper responsive design:
    a. Continue to take Kevin Powell's responsive CSS course (21 days)
    b. Learn about relative units
    c. Apply this information to TOP-landing-page



<!-- ================
====Second Commit====
=====Nov 26, 21====== -->

From the last commit:

1. I was able to learn about custom properties (variables) using the root pseudo class. This allowed me to make fonts and colors consistent across the whole page. 
2. I learned about relative units such as ems and rems. I tried to replace all instances of px with either em or rem. I'm still not sure if I used the right one in the right spot, but no ems blew up with compounding issues!
3. I learned about media queries and applied them to my page to make it significantly more responsive. I attempted to make this page mobile first so that queries responded to the page growing larger.
4. I reorganized my CSS into sections. Global Styles, Typography, Layout, and Components. I feel as though this method of organization helped me as I was cleaning everything up and fixing issues.
5. I attempted to rename everything using the BEM naming convention. I like that this naming convention allows me to select specific classes instead of having to combine selectors in some complicated way. I personally felt as though this made it extremely easy to identify which code belonged to what attributes. I think I will keep this until I find something better!

Remaining concerns:
    It still seems as though 400 lines of css is a little bit excessive for this project. 