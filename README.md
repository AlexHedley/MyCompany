# My Company extension

[![Build status](https://ci.appveyor.com/api/projects/status/t0a6fk2w5gxw5vx2?svg=true)](https://ci.appveyor.com/project/madskristensen/mycompany)

The easiest way to share links relevant to all developers in your team

Download the [CI build](https://www.vsixgallery.com/extension/61a7ba6e-0cd8-4912-a6c0-ff3f86d79c2e).

-----------------------------------------

Use this as the starting point for creating an extension for your team.

**Steps to customize**

* Fork the repo
* Modify and add buttons in *VSCommandTable.vsct*
* Modify and add URLs for the buttons in the *MyCompanyPackage.cs*

Update the link in [feed.pkgdef](https://github.com/AlexHedley/MyCompany/blob/master/src/feed.pkgdef) to match the [PrivateGalleryCreator](https://github.com/madskristensen/PrivateGalleryCreator) location.

- ["My Company" internal extension](https://www.youtube.com/watch?v=M1TodojlulY)
- [Writing Visual Studio Extensions with Mads](https://www.youtube.com/watch?v=iPf2oyJbADE&list=PLReL099Y5nRdG2n1PrY_tbCsUznoYvqkS)

## License
[Apache 2.0](LICENSE)
