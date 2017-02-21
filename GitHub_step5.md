[[Back to main]](github.md)&nbsp;&nbsp;&nbsp;&nbsp;[[Got to last step]](GitHub_step4.md)
&nbsp;&nbsp;&nbsp;&nbsp;[ArcGIS Online My Content](http://www.arcgis.com/home/content.html)

&nbsp;


# Step 5: Customize

After [step 4](GitHub_step4.md) is complete we will start to customize the map viewer.

> Once  you customize a viewer, the viewer can no longer live on ArcGIS online. 
> You need a place to host it.

First we need to update the configuration of the viewer.

Replace the file `config/default.js` with the contents of 
[config/default.js]https://gist.github.com/daveism/64c30b371a055f18bd20c52557d51d3a)

or just edit the stuff that changed
[config/default.js changes](https://gist.github.com/daveism/185dbc903a9f3755cf241700ef8374d7/revisions?diff=split)

Let's change the viewer so the messages about count and sum are tell the user exactly what the data represents.  In this case the number of fires and the acres burned.

Replace the file `js/main.js` with the contents of 
[js/main.js](https://gist.github.com/daveism/185dbc903a9f3755cf241700ef8374d7)

or just edit the stuff that changed
[js/main.js changes](https://gist.github.com/daveism/981289ab2730a7f1f148e6b991ef7020/revisions)

[[Go to next step]](GitHub_step6.md)
