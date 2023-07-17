A **tar.gz** file is a combination of a **.tar** file and a **.gz** file. It is an archive file with several other files inside it, which is then compressed.

You can unzip these files the same way you would unzip a regular zipped file:
```
tar –xvzf documents.tar.gz
```

The basic command is **`tar`**, followed by four options:

- **`x`** – instructs tar to extract the files from the zipped file
- **`v`** – means verbose, or to list out the files it’s extracting
- **`z`** – instructs **tar** to decompress the files – without this, you’d have a folder full of compressed files
- **`f`** – tells **tar** the filename you want it to work on

To list the contents of a **.tar** file before you extract it, enter:
```
tar –tzf documents.tar.gz
```

To instruct **tar** to put the extracted unzipped files into a specific directory, enter:

```
tar –xvzf documents.tar.gz –C /home/user/destination
```

To Read More about File Compression using tar, [click here](https://phoenixnap.com/kb/extract-tar-gz-files-linux-command-line)