[[Back to start]](github.md)&nbsp;&nbsp;&nbsp;&nbsp;[[Got to last step]](step6.md)
&nbsp;&nbsp;&nbsp;&nbsp;[ArcGIS Online My Content](http://www.arcgis.com/home/content.html)

&nbsp;

# Step 7: Using your Domain or Subdomain

After completing [step 6](GitHub_step6.md) lets go one step further and add our web domain to web site. This will make this page appear to be part of overall webpage.

Okay you caught me.  You might have to pay a few dollars, if you need to buy a domain I will assume you already did this so the cost remains 0.  You might need I.T.'s help. But it's easy I promise.


**On GitHub go to settings**

![Settings](https://docs.google.com/uc?id=0BykF_bN9fsvIU0hBWE52ZTBjWUE)

- Scroll down to the GitHub Pages section.
- look for the section - `Custom Domain`.
- in the Custom Domain text box add the text for a subdomain.  I am using `wncfires2016.nemac.org`.
> For your site, the `nemac.org` will change.

- click `save`.


There should be a new file in your repository named `CNAME`.  It contains the text you entered as a subdomain `wncfires2016.nemac.org`.

Add a cname record according to DNS providers directions.  There are just too many providers to go over each one.  Here is an example of what the cname looks like using Amazons Route 53.

![rename](dns.png)

Finally, the viewer has some hardcoding we need fix it change this [line](https://gist.github.com/daveism/d9d2cf2d34c5ee9b540ec5ca8abf4dab/revisions?diff=split) in the file `index.html`.

no go to the URL in my case it's http://wncfires2016.nemac.org/

**DONE** 

[boom](boom.md)
