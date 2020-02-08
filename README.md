# delfina

# Starting build
1. Download build, run 
2. Check out new branch, named according to feature working on, never push straight to master
3. Run $ theme watch to start the development server; note it doesn't sync automatically like webpack

 # Steps for deploying pages
 1. Pull from master and checkout a new branch called `whatever feature being worked on`
 2. Login to Shopify store admin 
  * https://delfina-swimwear.myshopify.com/admin
  * or partners store https://partners.shopify.com/1388545/stores?
  * or partners login https://delfina-test.myshopify.com/admin/themes
 3. Duplicate the published theme theme on app
 4. Rename the duplicated theme to the name of your branch
 5. Click 'Customise Theme' of your new branch theme
 6. Note the theme ID in the URL (e.g. /admin/themes/9542224/settings)
 7 .Edit the `theme_id` in `config.yml` to point to your branched theme
 8. `theme watch` and do your work
 9. Preview work by navigating to that theme in Shopify admin and clicking preview
 10. Pull request (can't on private free)
 11. Rebase onto master, push to master repo
 12. Delete your branch (local and server)
 13. Delete your branched theme in Shopify Admin

Note: will never be working on the live delfina theme in Shopify, it's live meaning changes reflect immediately


# Resources
* https://www.delfinasport.com/
* https://www.shopify.com.au/partners/blog/95401862-3-simple-steps-for-setting-up-a-local-shopify-theme-development-environment
* https://thoughtbot.com/blog/shopify-theme-development?fbclid=IwAR0ZUn1m_uEXkv1xKbmbbxth_ocemwp2rRJ4TmxEirGZ7PKs2YmWbvvLQy4


