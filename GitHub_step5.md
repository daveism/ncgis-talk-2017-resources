[[Back to start]](github.md)&nbsp;&nbsp;&nbsp;&nbsp;[[Got to previous step]](GitHub_step4.md)
&nbsp;&nbsp;&nbsp;&nbsp;[ArcGIS Online My Content](http://www.arcgis.com/home/content.html)

&nbsp;


# Step 5: Customize

After [step 4](GitHub_step4.md) is complete, we will start to customize the map viewer.

> Once  you customize a viewer, the viewer can no longer live on ArcGIS online. 
> You need a place to host it.

## Configuration 

First, we need to update the configuration of the viewer.

Replace the file `config/default.js` with the contents of 
[config/default.js](https://gist.github.com/daveism/64c30b371a055f18bd20c52557d51d3a).  

**You can do this by**
- Copying everything in this [linked file].(https://gist.github.com/daveism/64c30b371a055f18bd20c52557d51d3a).  
- Edit the `config/default.js` file on GitHub. 
- Select and delete all existing text in the file `config/default.js`.
- Paste into  `config/default.js`.

![editing config/default.js](https://docs.google.com/uc?id=0BykF_bN9fsvIaExtbGE3UEgxS3c)

or just edit the stuff that [changed](https://gist.github.com/daveism/185dbc903a9f3755cf241700ef8374d7/revisions?diff=split)


## Code 

Next let's change the viewer so the messages about count and sum are tell the user exactly what the data represents.  In this case the number of fires and the acres burned.

Replace the file `js/main.js` with the contents of 
[js/main.js](https://gist.github.com/daveism/185dbc903a9f3755cf241700ef8374d7)

**You can do this by**
- Copying everything in the the [linked file](https://gist.github.com/daveism/185dbc903a9f3755cf241700ef8374d7).  
- Edit the `js/main.js` file on GitHub. 
- Select and delete all existing text in the file `js/main.js`.
- Paste into  `js/main.js`.

![js/main.js](https://docs.google.com/uc?id=0BykF_bN9fsvIOXdMQmVKLVZULVU)

or just edit the stuff that changed
[js/main.js changes](https://gist.github.com/daveism/981289ab2730a7f1f148e6b991ef7020/revisions?diff=split))


[[Go to next step]](GitHub_step6.md)
