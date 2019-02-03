# NClassifier

This is a fork of NClassifier v0.1 by Ryan Whitaker, available at [http://nclassifier.sourceforge.net/](http://nclassifier.sourceforge.net/).

It has been modified to target netstandard2.0 and .Net Core 2.2 with the most minimal of changes, mainly:

- Updating .sln and .csproj formats
- Updating test method attributes for the current NUnit version
- Adding some minor type checks to get tests passing
- Commenting out ODBC functionality (not available in netstandard2.0)

This is for reference purposes only - originally written in 2004, the limitations of c# and standard libraries at the time required code that would not be considered efficient or ideal today.