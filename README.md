# CircularImageViewTutorial

Steps to integrate:

1. Copy CircluarImageView class to your java packages folder.
2. Copy attr.xml to values folder under res.

How to use:
Wherever you use ImageView use CircularImageView, 

xml like:
	<br><br>
<code>
&lt;com.yourpackagename.filepathpackage.CircularImageView<br>
android: layout_width = "wrap_content"<br>
android: layout_height = "wrap_content"<br>
android: src = "@drawable/profile"<br>
android: id = "@id+/circular_image_view" /&gt;
</code>
<br><br>

In java class like:

<!-- CircularImageView civProfile = (CircularImageView) findViewById(R.id.circular_image_view); -->


Now you can use this like ImageView.
