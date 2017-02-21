[Back to Start](github.md)

[Back to step 7](GitHub_step7.md)


# Step 7: Using your Domain or Subdomain

Okay you caught me.  You might have to pay a few dollars, if you buy a domain. And you might need I.T.'s help. But it's easy I promise.


On GitHub go to settings >

 &nbsp;&nbsp;&nbsp;&nbsp;Scroll down to the GitHub Pages section.
 
 &nbsp;&nbsp;&nbsp;&nbsp;look for section - `Custom Domain` 
 
 &nbsp;&nbsp;&nbsp;&nbsp;in the Custom Domain text box add the text for a subdomain.  I am using `wncfires2016.nemac.org`
 
 > of course for your site, the `nemac.org` will change
 
 &nbsp;&nbsp;&nbsp;&nbsp;click `save`

There should be a new file in your repository named `CNAME`.  It contains the text you entered as a subdomain `wncfires2016.nemac.org`.

Add a cname record according to DNS providers directions.  There are just too many providers to go over each one.  Here is an example of what the cname looks like using Amazons Route 53.


Finally, the viewer has some hardcoding we need fix it change this:

- [new code](https://gist.github.com/daveism/d9d2cf2d34c5ee9b540ec5ca8abf4dab/revisions)

no go to the URL in my case it's http://wncfires2016.nemac.org/

** [boom](boom.md)** 
