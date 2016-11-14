# HololensAssets

Assets for the Hololens Research Project.

settings.txt describes the url of the images located in the subfolder.

Unity will be periodically checking this file.

settings.txt currently needs to be updated with additional links (or have them removed) when the corresponding image is moved. That's just because Unity doesn't parse Github as an actual directory...so the C# script can't crawl the subfolders itself. (May be possible with a private hosted server, meaning no settings.txt needed at all).

To add an image, add an image to the image subfolder and add the corresponding raw URL of that image to the settings.txt, under the corresponding name (names start with #). To delete an image, remove the url from settings.txt (technically doesn't even need to be actually removed from github).

If adding more subfolders in the future, be sure to follow the pattern:

/#name
url1
url2
url3

/#name2
url1
url2
