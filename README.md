# CURL
This is a command-line tool for Microsoft Windows which enables you to download files from websites via Command Prompt.

To use this tool, open Command Prompt and execute the following command:

    mshta https://javadbayat.github.io/curl <url> -o <DestPath>

where `<url>` is the direct URL of the file that you want to download, and `<DestPath>` is the path where the final downloaded file is to be stored on your computer. For example:

    mshta https://javadbayat.github.io/curl http://example.com/video.mp4 -o D:\MyVideo.mp4

After executing the command, you must patiently wait until the tool initializes and then downloads the given file. When the download is completed, you will get a message that lets you choose whether to open the downloaded file or its containing folder.

**Note:** If you want to close this app or abort the download for any particular reason, you can simply press **`Esc`** or **`Alt+F4`** key.