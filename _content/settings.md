---
title: Settings
_fieldset: settings
email_address: hello@example.com
copy_logo: Hawthorne
copy_tagline: 'Design & Art Direction'
copy_lined_list_separator: ':'
type_theme: type1
color_theme: color1
hide_captions: "1"
footer_html: |
  <li>&copy; {{ current_date format="Y" }} <a href="/">Your Name Here</a>. All rights reserved.</li>
  <li><a href="mailto:{{ get_content from="/settings" }}{{ email_address|obfuscate }}{{ /get_content }}"><i class="fa fa-envelope-o"></i> {{ get_content from="/settings" }}{{ email_address|obfuscate }}{{ /get_content }}</a></li>
copy_site_title: Hawthorne
main_nav_link_grid: ""
social_icons: |
  <a href="http://www.twitter.com/typewolf" target="_blank"><i class="fa fa-twitter-square fa-2x"></i></a>
  <a href="http://www.linkedin.com" target="_blank"><i class="fa fa-linkedin-square fa-2x"></i></a>
analytics_code:
---












































































