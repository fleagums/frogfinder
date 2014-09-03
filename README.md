frogfinder
==========

Drupal Assignment: Frog Finder Site

Create a new Drupal site (you can use the Bear profile so that you don’t have to add as many modules) called Frog Finder (machine name: frogfinder).

Frog Finder will be a site like PetFinder where visitors can come and find the perfect frog (for a pet? for their pond? for dinner? whatever you like)

Don’t worry about the theme of the site as we will add that on Wednesday.

Features of Frog Finder:

A frog content type which includes fields for Title, Description and Species. Species should be a term reference field to a Species taxonomy vocabulary, which lets you pick a species with free tagging (autocomplete).

Any site visitor should be allowed to add a new frog, but the frog content should not be published.

Provide an administrative View at /admin/content/frog-approval which only administrators can view. It should be a table of all unpublished frogs, showing the title, created date, edit and delete links. Order it by date created descending.

Create a frog gallery page at /frogs. Show a grid there of medium-sized images of each frog on the site which link to the frog content. Provide an exposed filter above the grid so that visitors can filter the gallery for a species. Add /frogs to the main menu.

Add at least 5 frogs to the site with frog images. Include the correct species for each image.

Change the URL path settings so that frog content pages have a path of frogs/[node:title]

Challenge Exercises
If the above was not a challenge to you, please try some challenge exercises:

Latest Frogs
Add a block view that shows the 5 latest frogs added to the site. Show the block on the right sidebar.

Favorite Frogs

Use the https://www.drupal.org/project/flag module and create a bookmarking/favoriting system so that users can favorite some frogs. Provide a “Favorite” link on each frog node by configuring the flag module. Also provide a view that lists a user’s favorited frogs. This can be a view of path user/%/favorites that is a menu tab, which uses the user id from the URL as a contextual filter. It should filter for frog content that the user has favorited.



