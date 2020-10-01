# grapX

<img src="images/grapX.jpg" width="150" height="150" />

**grapX** will iterate through the urls extracted from `waybackurls`,It will match and list the urls with possible 50+ extensions.Sometimes we can expect the unexpected and find some juicy information through this listing.

This is a simple script i recently created for my recon automation.if you can contribute on some extensions or on code,Great!!


Install:

```
▶ git clone https://github.com/kabilan1290/grapX.git
▶ chmod +x grapX
▶ cp grapX /usr/local/bin/grapX
```
Usage example:

```
▶ cat domains.txt | waybackurls > urls
▶ ./grapX urls output_filename

```
