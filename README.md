# TextViewJustify

This is a custom library for android that can justify your textView... Amazing!

Step 1. Add the JitPack repository to your build file
Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  
  
Step 2. Add the dependency

	dependencies {
	        implementation 'com.github.iceboy1369:JustifyTextView:1.0'
	}
	


Step 3. Add TextViewJustify in your xml files like this:

	<icegroup.TextViewJustify
		android:id="@+id/txt_justify"
		android:layout_width="match_parent"
		android:layout_height="wrap_content"/>


Step 4. Then in your code use the 'true' after your text param to do justify that like below line:

	txt_justify.setText( "your text" , true );

in the below you can see the screenshot


