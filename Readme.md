[![Build Status](https://travis-ci.org/GlobalFreightSolutions/gfs-selected-droppoint.svg?branch=master)](https://travis-ci.org/GlobalFreightSolutions/gfs-selected-droppoint)


# &lt;gfs-selected-droppoint&gt;

The `gfs-selected-droppoint` widget displays information on a droppoint. When used in conjuction with the checkout widget it will display the details of a droppoint selected from the map.

## Install

```bash
# via bower
$ bower install gfs-selected-droppoint
```

## Usage
```html
<link rel="import" href="path_to_bower_components/gfs-selected-droppoint/gfs-selected-droppoint.html" />
```

<!---
```
<custom-element-demo>
    <template>
        <script src="../webcomponentsjs/webcomponents-lite.js"></script>
        <link rel="import" href="gfs-selected-droppoint.html">
        <next-code-block></next-code-block>
    </template>
</custom-element-demo>
```
-->

```html
<gfs-selected-droppoint
    title="Your collection point"
    visible="true"
    droppoint-data='{"droppointId":"DPD-123","isStore":false,"providerName":"DPD","distanceInMeters":888,"localizedDistance":"888 meters","droppointDescription":"The Pharmacy at Mayfair (Numark)","geoLocation":{"addressLines":["Shepherd Market"],"town":"London","postCode":"W1J 7UD","countryCode":"GB","directions":"The Pharmacy at Mayfair (Numark)"},"collectionSlots":[{"collectionDate":"2016-11-10T00:00:00Z","timeSlots":[{"from":"09:30","to":"17:00"}]}]}'>
</gfs-selected-droppoint>
```

More info and all the available properties can be found at [GFS widget portal](http://gfsdeveloperportal.azurewebsites.net/info/documentation/gfs-checkout/the-gfs-checkout-widgets/selected-droppoint-widget/ "The GFS Selected Droppoint Widget")


### License

Apache License 2.0
