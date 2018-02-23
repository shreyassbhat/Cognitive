# Cognitive

Detect, identify, analyze, and organize faces in photos


The Face API client library is a thin Java client wrapper for Microsoft Face API.

The easiest way to consume the client library is to add com.microsoft.projectoxford.face package from Maven Central Repository. To find the latest version of client library, go to http://search.maven.org, and search for "com.microsoft.projectoxford".

To add the client library dependency from build.gradle file, add the following line in dependencies.

dependencies {
    //
    // Use the following line to include client library from Maven Central Repository
    // Change the version number from the search.maven.org result
    //
    compile 'com.microsoft.projectoxford:face:1.1.0'

    // Your other Dependencies...
}



To do add the client library dependency from Android Studio:

From Menu, Choose File > Project Structure
Click on your app module
Click on Dependencies tab
Click "+" sign to add new dependency
Pick "Library dependency" from the drop down list
Type "com.microsoft.projectoxford" and hit the search icon from "Choose Library Dependency" dialog
Pick the Project Oxford client library that you intend to use.
Click "OK" to add the new dependency
