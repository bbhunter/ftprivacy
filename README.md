# FTPiHole.com

A growing, frequently updated, tested and researched set of Pi Hole blocklists, both generic and aimed at various products and services so as to be as flexible as possible - for example we have a generic mobile list and a generic computer list, but also one dedicated to Windows 10 "telemetry."

We also optionally have three separate lists for blocking one or all of: Facebook, Instagram, or WhatsApp entirely on your network or device. Of course we also have the common Facebook tracking scripts added in the general lists. But these are balanced to ensure the services still work. If you don't use FB and don't care if it's simply inaccessible, you can use the block all Facebook list ([GitHub](https://raw.githubusercontent.com/ftpmorph/ftpihole/master/blocklists/facebook-full-block.txt), [S3](https://ftpihole.s3.eu-west-2.amazonaws.com/blocklists/facebook-full-block.txt)) and have it gone from your network for good. As well as protecting your privacy this may even encourage guests to speak to each other :) 

If you have suggestions for appropriate additions to any of the lists or you have spotted any false positives please let us know here through GitHub. We recommend using pull requests for both, but raising an issue works too. We also strongly suggest giving a reason for your request. For example simply giving a domain and saying "this shouldn't be there" without an explanation or further detail is likely to be ignored.

Lists are hosted here on GitHub and in our S3 bucket. When adding the lists to your Pi Hole, either source will work (use the "raw" links from the repo), but we recommend using the S3 links found [on our website.](https://www.ftpihole.com/lists/) In theory the two should be always synced perfectly, but in case something happens, S3 links get priority. They should also be more reliable as they're served through a CDN. I'd also say faster but... well, they are raw txt files aren't they?

Finally, if you get the reference in the name you are my kind of human.

Fuck ads, fuck tracking, fuck privacy invasion... fuck the population.

**https://www.ftpihole.com/**
