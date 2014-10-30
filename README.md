# zdk-panel

A panel web component

The panel is easily added to your page when added 

    <link rel="import" href="bower_components/zdk-panel/zdk-panel.html">
    
then add in your body

    <zdk-panel></zdk-panel>
    
The zdk-panel has no height set by default so it will adapt to your content 

an example :

<zdk-panel>Put some content here ...</zdk-panel>

## properties

__heading__ : title of the panel

__height__ : number of pixel to limit the height of the panel, ex `height="250"` for a panel of 250px

__collapsable__ : (boolean) the panel is collapsable, a arrow icon is displayed on the right of the title bar to expand/collapse the content panel  
eg : `collapasable="true"`

__collapsed__ : (boolean) depend of the collapsable attribute which must be true. if true the content panel is hidden by default.  
eg : `collased="true"`

__collapsecolor__ : allows to change the color of the arrow icon, white by default.  
eg : `collapsecolor="tomato"`

## methods

none

## events

none

## Compatibility

### Desktop

| OS           | Browser        | status  
|--------------|----------------|--------------
| osx 10.10    | Chrome 37.x    | OK
|              | Firefox 30.x   | OK
|              | Safari 8.X     | OK
| Ubuntu 14.04 | Chrome 37.x    | OK
|              | Firefox 30.x   | OK
| Win 7        | Chrome 37.x    | OK
|              | Firefox 30.x   | OK
|              | IExplorer 10   | OK
|              | IExplorer 11   | OK

### Mobile  

| OS     | Device      | Browser         | status
|--------|-------------|-----------------|----------------
| IOS7   | Ipad2       | Safari          | OK
| IOS8.1 | Ipad2       | Safari          | OK
| And4.4 | Nexus 7.2   | Chrome          | OK
|        |             | Firefox         | OK
|        | Nexus 4     | Chrome          | OK
|        |             | Firefox         | OK

