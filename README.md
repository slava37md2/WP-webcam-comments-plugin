# WP-webcam-comments-plugin
With our plugin you can add video comments from webcam right on the Wordpress site.
Now you can not only read comments but you can see also who and how speaks.

Flash is not used.

Plugin works only on sites with ssl (https) and on the localhost without ssl.

The comand for cron:

45 0 * * * find /home/your_name/public_html/wp/wp-content/uploads -type f -mmin +60 -name “*.mp4” -exec rm -f {} \; #() Removes mp4-files older than 60 minute (each day) in folder uploads(temporary files)

Instead of “your_name” write your login in hosting. Instead of “wp” write the folder with wordpress script.

Attention: 30 sec mp4-file have a size 4MB.

Demo is <a href="https://wikimoldia.org/wp/2019/03/23/wordpress-plagin-golosovaniya-za-kommentarii/">here</a>
