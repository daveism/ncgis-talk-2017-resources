
## No It needed. (Dude where's my server)

#### Step 1: Log into ArcGIS Online Borrow a map and save it
```
For this example use this map and call it WNC Fires 2016
```
- [Source Map](http://www.arcgis.com/home/webmap/viewer.html?webmap=7a1f7ebd8d7f429b94335e8890561c4d)

#### Step 2: The map, WNC Fires 2016 should now be listed in your my content section
```
Make a note about webmap id
Click on details and when the map opens copy the web id. 
```
- [ArcGIS My Content](http://www.arcgis.com/home/content.html)

- [Source Layer](http://services1.arcgis.com/PwLrOgCfU0cYShcG/arcgis/rest/services/wnc_fires_2016/FeatureServer/1)

#### Step 3: Fork a viewer
```
We are going to for an ESRI template.  
Either search for it of fork it directly in GitHub
```
- [Summary Viewer](https://github.com/Esri/summary-viewer-template)


```
Rename the viewer:  WNC Fires 2016 
On GitHub go to settings, rename it, then click rename
```

#### Step 3: Say the magic words GitHub Pages

```
On GitHub scroll down to the GitHub Pages section.
Change the select source to master branch save
```

- Wait a few moments
- When the url turns green it's ready.  Click it

#### Step 4: Configure it

change the config/default.js to match this:
- [Config changes](https://gist.github.com/daveism/64c30b371a055f18bd20c52557d51d3a)

```
Do a hard refrerh in your browser.
```

****No servers yet.
****No cost.

#### Step 5: Customize
One customized it can no longer live on ArcGIS online. You need a place to host it.

- [main.js changes](https://gist.github.com/daveism/41a800fa6b7a1813ea621148dfa453d5)

- [index.html changes](https://gist.github.com/daveism/9d02902697ffc62f4ccc4f67b7ce011e)

- [CSS changes](https://gist.github.com/daveism/aa4af8c979021671d9ec6ab37d729a60)

- [index.html DNS changes](https://gist.github.com/daveism/2222a46bcd36db23b24bca85066bd155)