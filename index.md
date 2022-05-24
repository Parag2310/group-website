---
layout: home
title: building websites
lesson-example: "https://github.com/carpentries/carpentries.org/blob/main/images/TheCarpentries-opengraph.png"
---

changed layout from default to home (image).
## Description
Add a new section ‘Description’ to file index.md and add some description.

title locally 
# building websites

From the GitHub interface, edit file index.md and add a new section called Description to it, with some text about the project.
View the changes on the website {{ site.Description }}
More details [About page](about)

see some [example]({{page.lesson-example}})

Have any questions about waht we do? [We'd love to hear from you!](mailto:{{site.Email}})

Navigation bar using html

{% include navigation.html %}

footer using html
{% include footer.html %}


