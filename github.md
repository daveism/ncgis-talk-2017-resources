
# No I.T. needed. (Dude where's my server)

## Resources I am using

### Services
[ArcGIS Online](http://www.arcgis.com/)
You can create a FREE account!

[GitHub](https://github.com/)
You can create a FREE account!


### Data

 [Source Map](http://www.arcgis.com/home/webmap/viewer.html?webmap=7a1f7ebd8d7f429b94335e8890561c4d)
 Source map.  A source map that I created and shared with everyone
 
[Source Layer](http://services1.arcgis.com/PwLrOgCfU0cYShcG/arcgis/rest/services/wnc_fires_2016/FeatureServer/1)
Source Data I created and shared with everyone for getting field names

Note: Data can be anlyting on ArcGIS Online (AGOL) and could be published from anyone. Like your favorite City or Organization. In this case it's [NEMAC](https://nemac.unca.edu/).

### Convience
[ArcGIS Online My Content](http://www.arcgis.com/home/content.html)
If you're logged into ArcGIS Online (AGOL) go straight to my content page.  Because I never seem to go straight there and sometimes the link to my content is not available.

[Got to next step](GitHub_step1.md)





# Note

**No servers**

**No cost**


# Step 5: Customize
> Once  you customize a viewer, the viewer can no longer live on ArcGIS online. 
> You need a place to host it.


Let's change the viewer so the messages about count and sum are more accurate.

Replace the file `js/main.js` with the contents of 
[js/main.js](https://gist.github.com/daveism/981289ab2730a7f1f148e6b991ef7020)

or just edit the stuff that changed
[js/main.js changes](https://gist.github.com/daveism/981289ab2730a7f1f148e6b991ef7020/revisions)

# Step 6: Customize the look to match your branding


add this [line](https://gist.github.com/daveism/9d02902697ffc62f4ccc4f67b7ce011e#file-ncgis-2017-index-no-dns-html-L16) to ```index.html```

just replace the whole file ```css/main.css``` with this [file](https://gist.github.com/daveism/aa4af8c979021671d9ec6ab37d729a60)


Change the color scheme to #5091B2 in ```config/deafualt.js```

# Note

**Still No servers**

**Still No cost**

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

# Note

**Still No servers**

**Maybe some minimal cost**
