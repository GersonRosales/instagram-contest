# Instagram-contest
This is a bash script you can run to auto comment a contest post.

 1. Go to the publicantion you want to put a comment.
 2. Using Chrome press the short-cut `command + option + i`, https://developer.chrome.com/docs/devtools/shortcuts/.
 3. Write the comment **Hello** and send it.
 4. Search in the **Network** section the request called `add/`.
 5. Click right button over the `add/` request and copy as curl.
 6. Go to the [magic page](https://gersonrosales.github.io/instagram-contest/) and paste in the curl field.
 7. Insert the time you want to sleep between each message.
 8. Click in the **Create Script** button.
 9. Create the file that will feed the script (If this file does not exist, copy and paste the following command)
     
    `echo $'This will be the 1st comment.\nThis will be the 2nd comment.' > comment_list.txt`
    
	*Note: Every line will represent every comment.*

 11. Run the script `./auto_comment.sh`
 12. Good Luck!

 ## Published page
https://gersonrosales.github.io/instagram-contest/
