# CircularImageViewTutorial

Steps to integrate:

1. Copy CircluarImageView class to your java packages folder.
2. Copy attr.xml to values folder under res.

How to use:
Wherever you use ImageView use CircularImageView, 

xml like:
'''
&lt;com.yourpackagename.filepathpackage.CircularImageView
android: layout_width = "wrap_content"
android: layout_height = "wrap_content"
android: src = "@drawable/profile"
android: id = "@id+/circular_image_view" /&gt;
'''

In java class like:

<!-- CircularImageView civProfile = (CircularImageView) findViewById(R.id.circular_image_view); -->


Now you can use this like ImageView.
