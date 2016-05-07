Pripomienky
Also, it's best to give your wrapper div a max-width so that it doesn't 
appear too wide in extra large devices. That can make your your site's content difficult to read.

Make sure you remove those empty class=' ' attributes from 
the skills-list unordered list items. :)

Well done! I like that you're also using flexbox in the site layout -- just be sure to 
include the vendor-prefixed flexbox properties too. 
For example, -webkit- for slightly older versions of Safari.
Also, consider using the :nth-of-type selector for clearing your "gallery" floats. 
That way you don't have to add extra classes to your HTML just to clear floats. 
Or, use flexbox for those, too. :)

And to enhance the performance of your site, write your CSS -- except for Normalize.css 
-- in one style sheet. That way the browser will load only one style sheet when/if you
 upload the site to a server.
