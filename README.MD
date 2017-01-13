## Type:
#### Shell script.
## Why did I write this?
#### Get out put to the tail of file, be sure convenient for generate comment by using the output of the writing script itself.
## Install:
#### Run this command in shell: sudo cp outail.sh to /usr/bin/ ;
## Use:
#### In vim view mod, type these words: ":!outail %" .
## Note:
#### The output of run of editting script would be temporatory in /tmp/vimming_script_outtemp.d,  so, maybe you must edit /etc/crontab to rm the temporatory file every month, unless your *nix will process it automatic.
#### If the '%' is redirect to the /usr/bin/outail (when you are calling it in 'vi[m]?', you will get a error, and exit code which is 11. )
#
# Enjoy it :)
