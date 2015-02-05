---
title: Settings
_fieldset: settings
email_address: leslie.strauss@gmail.com
copy_logo: Leslie Strauss
copy_tagline: Develop / Designer / Builder
copy_lined_list_separator: ':'
type_theme: type8
color_theme: color10
hide_captions: "1"
footer_html: |
  <li>© {{ current_date format="Y" }} <a href="/">Leslie Strauss</a>. All rights reserved.</li>
  <li><a href="mailto:{{ get_content from="/settings" }}{{ email_address|obfuscate }}{{ /get_content }}"><i class="fa fa-envelope-o"></i> {{ get_content from="/settings" }}{{ email_address|obfuscate }}{{ /get_content }}</a></li>
copy_site_title: LS
social_icons: |
  <a href="http://github.com/leslstrauss" target="_blank"><i class="fa fa-github-square fa-2x"></i></a>
  <a href="http://www.linkedin.com/in/leslstrauss" target="_blank"><i class="fa fa-linkedin-square fa-2x"></i></a>
analytics_code: |
  <script>
    (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
    (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
    m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
    })(window,document,'script','//www.google-analytics.com/analytics.js','ga');
    ga('create', 'UA-59180297-2', 'auto');
    ga('send', 'pageview');
  </script>
  <script>
    jQuery(document).ready(function() {
      setTimeout(function () {
        $('#main').load("test.php");
      }, 0);
    });
  </script>
---
















































































