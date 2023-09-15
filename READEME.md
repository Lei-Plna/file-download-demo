# How to download a File ?

We can trigger download by \<a\/\> link directly when server set the response header 'Content-Disposition' as "attachment" with the property 'filename=[something]'.

Also we can trigger it by \<a\/\> tag with href to file path, meanwhile set the property 'download' with filename.

And we can trigger it by axios to get the file and load it into memory and create a temp URL by createObjectURL and then create link tag to trigger click function.