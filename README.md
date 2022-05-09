At my current job (as of the time of writing this) we do
a lot of business through Reverb. Reverb is an online
sales platform for new and used audio equipment and
instruments. As such, we're regularly adding new listings
to our Reverb shop. So I wrote a pair of scripts that
help automate each step in this process. The make_listing
script takes the blank template, copies it into the
current directory, and opens it for editting in
libreooffice. the reverb_post script takes the filled out
listing information along with every photo in the given
directory and uses that to generate a listing on Reverb.

In the future I'm going to be adding the option to write
out the description for the listing in a text file and
have the script read from that instead of from inside
the spreadsheet, as it's obnoxious trying to write a
detailed description in excel
