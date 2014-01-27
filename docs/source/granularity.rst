Granularity
-------------

Version 1.0.0 introduced a new level of granularity by including template tags with a default value, which can be overriden in settings, which in turn can be overridden by passing the template tag an argument. This allows you to change default values within settings, while giving a template tag final word.

If you use an optional value other than the ones listed, you will have to add the files into the same directory structure as djfrontend.

+-----------------------------------+---------------------------------------+---------------+-------------------+
|Template tag                       |Setting                                |Default Value  |Optional Value(s)  |
+===================================+=======================================+===============+===================+
|                                   |DJFRONTEND_STATIC_URL                  |               |                   |
+-----------------------------------+---------------------------------------+---------------+-------------------+
|djfrontend_h5bp_html               |DJFRONTEND_H5BP_HTML                   |en             |ISO 639-1 codes    |
+-----------------------------------+---------------------------------------+---------------+-------------------+
|djfrontend_h5bp_css                |DJFRONTEND_H5BP_CSS                    |4.0.3          |                   |
+-----------------------------------+---------------------------------------+---------------+-------------------+
|djfrontend_normalize               |DJFRONTEND_NORMALIZE                   |2.1.3          |                   |
+-----------------------------------+---------------------------------------+---------------+-------------------+
|djfrontend_fontawesome             |DJFRONTEND_FONTAWESOME                 |4.0.3          |                   |
+-----------------------------------+---------------------------------------+---------------+-------------------+
|djfrontend_modernizr               |DJFRONTEND_MODERNIZR                   |2.7.1          |                   |
+-----------------------------------+---------------------------------------+---------------+-------------------+
|djfrontend_jquery                  |DJFRONTEND_JQUERY                      |1.11.0         |2.1.0              |
+-----------------------------------+---------------------------------------+---------------+-------------------+
|djfrontend_jqueryui                |DJFRONTEND_JQUERYUI                    |1.10.4         |                   |
+-----------------------------------+---------------------------------------+---------------+-------------------+
|                                   |DJFRONTEND_JQUERY_DATATABLES_VERSION   |               |                   |
+-----------------------------------+---------------------------------------+---------------+-------------------+
|djfrontend_jquery_datatables       |DJFRONTEND_JQUERY_DATATABLES           |1.9.4          |                   |
+-----------------------------------+---------------------------------------+---------------+-------------------+
|djfrontend_jquery_datatables_css   |DJFRONTEND_JQUERY_DATATABLES_CSS       |1.9.4          |                   |
+-----------------------------------+---------------------------------------+---------------+-------------------+
|djfrontend_jquery_formset          |DJFRONTEND_JQUERY_FORMSET              |1.2            |                   |
+-----------------------------------+---------------------------------------+---------------+-------------------+
|djfrontend_jquery_scrollto         |DJFRONTEND_JQUERY_SCROLLTO             |1.4.9          |                   |
+-----------------------------------+---------------------------------------+---------------+-------------------+
|djfrontend_jquery_smoothscroll     |DJFRONTEND_JQUERY_SMOOTHSCROLL         |1.4.13         |                   |
+-----------------------------------+---------------------------------------+---------------+-------------------+
|                                   |DJFRONTEND_TWBS_VERSION                |               |                   |
+-----------------------------------+---------------------------------------+---------------+-------------------+
|djfrontend_twbs_css                |DJFRONTEND_TWBS_CSS                    |3.0.3          |                   |
+-----------------------------------+---------------------------------------+---------------+-------------------+
|djfrontend_twbs_theme_css          |DJFRONTEND_TWBS_THEME_CSS              |3.0.3          |                   |
+-----------------------------------+---------------------------------------+---------------+-------------------+
|djfrontend_twbs_js                 |DJFRONTEND_TWBS_JS_VERSION             |3.0.3          |                   |
|                                   |DJFRONTEND_TWBS_JS_FILES               |all            |* affix            |
|                                   |                                       |               |* alert            |
|                                   |                                       |               |* button           |
|                                   |                                       |               |* carousel         |
|                                   |                                       |               |* collapse         |
|                                   |                                       |               |* dropdown         |
|                                   |                                       |               |* modal            |
|                                   |                                       |               |* popover          |
|                                   |                                       |               |* scrollspy        |
|                                   |                                       |               |* tab              |
|                                   |                                       |               |* tooltip          |
|                                   |                                       |               |* transition       |
+-----------------------------------+---------------------------------------+---------------+-------------------+
|djfrontend_ga                      |DJFRONTEND_GA                          |               |                   |
+-----------------------------------+---------------------------------------+---------------+-------------------+
|                                   |DJFRONTEND_GA_SETDOMAINNAME            |               |                   |
+-----------------------------------+---------------------------------------+---------------+-------------------+
|                                   |DJFRONTEND_GA_SETALLOWLINKER           |               |                   |
+-----------------------------------+---------------------------------------+---------------+-------------------+
|djfrontend_ios_fix                 |                                       |               |                   |
+-----------------------------------+---------------------------------------+---------------+-------------------+