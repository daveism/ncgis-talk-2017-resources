
# No I.T. needed. (Dude where's my server)

## Things I am using

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

Note: Data can be anlyting on ArcGIS Online (AGOL) and could be published from anyone. Like your favorite City or Orginaztion. In this case [NEMAC](https://nemac.unca.edu/).

### Convience
[ArcGIS Online My Content](http://www.arcgis.com/home/content.html)
If your logged into ArcGIS Online (AGOL) go straight to your content page.  Because I never seem to go straight there.


# Step 1: Log into ArcGIS Online borrow a map and save it

Using this [Source Map](http://www.arcgis.com/home/webmap/viewer.html?webmap=7a1f7ebd8d7f429b94335e8890561c4d)

```
Do a save as: WNC Fires 2016
```

![Save as](https://docs.google.com/uc?id=0BykF_bN9fsvITXBKVWozUXRYRFk)

This saves the map to your AGOL account


# Step 2: Share

Share thehe map.

WNC Fires 2016 should now be listed in your [content](http://www.arcgis.com/home/content.html) section

```
Open the web map in map in the ArcGIS Online map viewer
```

```
Share with Every one
```

> Make a note about webmap id your going to need it later


# Step 3: Fork a viewer

We are going to use an ESRI template.  

```
Search ArcGIS Online for the Summary Map Viewer 
```


```
Then fork it directly in GitHub
```


Your can fork the [Summary Map Viewer](https://github.com/Esri/summary-viewer-template) it directly in GitHub


# Step 4: Rename

Rename the viewer:  WNC Fires 2016 

```
On GitHub go to settings >  
  In the rename text box type WNC Fires 2016 
  then click rename
```

# Step 3: Do some magic

GitHub Pages

```
On GitHub go to settings >
  Scroll down to the GitHub Pages section.
  Change the select source to master branch click save
```

```
Wait a few moments
```

```
When the url turns green it's ready.  
```

Click and see the magic.


# Step 4: Configure the viewer


you replace the file with the ```config/default.js``` with the contents of 
[config/default.js](https://gist.github.com/daveism/f05a1c146d9d3f41e31efb0757e7dfce)


or just edit the stuff that changed
[config/default.js changes](https://gist.github.com/daveism/f05a1c146d9d3f41e31efb0757e7dfce/revisions)


```
Do a hard refresh in your browser.
```

# Note

**No servers**

**No cost**


# Step 5: Customize
> Once  you customize a viewer, the viewer can no longer live on ArcGIS online. 
> You need a place to host it.


Let's change the viewer so the messages about count and acres actuall tell the user what they want.  Total Fires and Total Acres Burned. 

Replace the file ```js/main.js``` with the contents of 
[js/main.js](https://gist.github.com/daveism/981289ab2730a7f1f148e6b991ef7020)

or just edit the stuff that changed
[js/main.js changes](https://gist.github.com/daveism/981289ab2730a7f1f148e6b991ef7020/revisions)

# Step 6: Customize the look to match your branding

```
add this line to index.html
```

[index.html changes](https://gist.github.com/daveism/9d02902697ffc62f4ccc4f67b7ce011e#file-ncgis-2017-index-no-dns-html-L16)

```
just replace the whole file css/main.css with this one:
```

[CSS changes](https://gist.github.com/daveism/aa4af8c979021671d9ec6ab37d729a60)


Change the color scheme to #5091B2 in ```config/deafualt.js```

# Note

**Still No servers**

**Still No cost**

# Step 7: Using your own URL

Okay you caught me.  You might have to pay a few dollars, if you buy a domain. And you might need I.T.'s help. But it's easy I promise.


```
On GitHub go to settings >
 Scroll down to the GitHub Pages section.
 look for section - Custom domain
   in the blank box add a subdomain for me it's wncfires2016.nemac.org
   
   of course for your site the nemac.org will change

  click save
```

There should be a new file named CNAME.  It contains the text you entered as a subdomain.

The viewer has some hardcoding in it we need fix it

- [new code](https://gist.github.com/daveism/d9d2cf2d34c5ee9b540ec5ca8abf4dab/revisions)

no go to the URL in my case it's http://wncfires2016.nemac.org/

# Note

**Still No servers**

**Maybe some minimal cost**
