# volley
volley fork from https://android.googlesource.com/platform/frameworks/volley/

Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url "https://jitpack.io" }
		}
	}
Step 2. Add the dependency

	dependencies {
	        compile 'com.github.alexnavratil:volley:v1.0'
	}
