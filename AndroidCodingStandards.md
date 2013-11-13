# EPAM Mobile Competency Center Android Code Style Guidelines
###### Revision 1.0

This style guide describes the coding conventions suggested by EPAM Mobile Competency Center for any Android project developed by EPAM.

This guide consist of references to community-accepted best practices and it might be used in the next two ways:

* Use this document "as is" to define coding guidelines on your project
* Use this document as a template or a checklist to define your own coding guidelines by overriding/removing/adding rules in the most suitable and appropriate way that fits your project needs and your personal preferences

Some rules in the referenced documents have reasoning that explain why the particular rule exist and why it is defined this way. But there are a lot of rules that are contractual by their nature, we just need to define these rules to keep our code consistent. The authors of this document are more concerned whether you have some coding guidelines on your project, than whether you use this particular document as your coding guidelines.


## Table of Contents

1. [Java Language](#1java-language)
2. [Android](#2android)
    1. [Memory Leaks](#21memory-leaks)
3. [Secure Coding](#3secure-coding)

## 1.Java Language

1. Follow Geosoft's [Java Programming Style Guidelines](http://geosoft.no/development/javastyle.html).

## 2.Android
1. Follow Google's [Android Code Style Guidelines](http://source.android.com/source/code-style.html). To setup corresponding eclipse formatting, download file with formatting rules from [here](https://github.com/android/platform_development/blob/master/ide/eclipse/android-formatting.xml) and follow instructions from [here](http://source.android.com/source/using-eclipse.html#eclipse-formatting).

### 2.1.Memory Leaks
1. Follow the recommendations described in Google's [Avoiding Memory Leaks](http://android-developers.blogspot.com/2009/01/avoiding-memory-leaks.html) blog post.


## 3.Secure Coding
1. Follow Oracle's [Secure Coding Guidelines](http://www.oracle.com/technetwork/java/seccodeguide-139067.html).


# Other Style Guides

The list of other solid and popular coding guides that you may want to use together/instead of the guides provided above:

1. Sun's [Code Conventions for the Java Programming Language](http://www.oracle.com/technetwork/java/codeconv-138413.html). This is widely adopted code conventions document, but it is pretty old and has been criticized: [Java Coding Conventions considered harmful](http://www.javacodegeeks.com/2012/10/java-coding-conventions-considered-harmful.html).
2. AmbySoft's [Writing Robust Java Code](http://www.ambysoft.com/downloads/javaCodingStandards.pdf)
