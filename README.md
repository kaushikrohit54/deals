== Add Deal post to WordPress ===

Requirements
 - Wrdpress version above 4.9
 - Tested over twenty Sixteen theme
 - Advance Custom Fields Plugin (url: https://wordpress.org/plugins/advanced-custom-fields/)
 - Deal Post Plugin 
 
Procedure 
 - First Install & Activate Deal Post Plugin and ACF
 - Default field created in Deal post after activate of both plugin you will see under deal post.
   1. Field Name: Launch Year, Type: Date Picker, Name: launch_year
   2. Field Name: Founders, Type: Text, Name: founders
   3. Field Name: Funding Amount, Type: Number, Name: funding_amount
   4. Field Name: Invertors, Type: Text, Name: investors
   5. Field Name: Article Title, Type: Text, Name: article_title
   6. Field Name: Link to Article, Type: Url, Name: link_to_article
- Enter The 'Sectors' and 'Deal Stages' (created as texonomies/category)
- Single template and Archive template are created under plugiun template folder, if you don't get then please copy these files under your activated theme.

Shortcode
 - Use [deal-card id = DEAL_POST_ID] will show single grid of deal post
 - Use [all-deals] to show all deals cards under deafult post and pages. 

Archive
 - Shows all deals post url would be https://YOUR_url/deals
Single template
 - Show Single Deal post url would be https://YOUR_url/deals/POST_LINK
 
Uses cdns:
  -Bootstarp css and js
  - readMoreJS 


If you have any query or activation problem then please mail @ kaushikrohit54@gmail.com



    

 
