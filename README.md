# CURL
Currently, this command-line tool is under active development.

For now, this tool can only download a file and display its text content in a window, but not save the downloaded file in your storage.  
To use it, open Command Prompt and execute the following:

    mshta https://javadbayat.github.io/curl <url>

where `<url>` is the absolute URL of the file that you want to download.

In the near future, we're going to upgrade this tool so that you can specify a path in the command line with the `-o <path>` parameter, so the downloaded file will be stored in the given path. For example:

    mshta https://javadbayat.github.io/curl http://example.com/video.mp4 -o D:\MyVideo.mp4
