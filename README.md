<!DOCTYPE html>
<head>    
    <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
    
        <script>
            L_NO_TOUCH = false;
            L_DISABLE_3D = false;
        </script>
    
    <script src="https://cdn.jsdelivr.net/npm/leaflet@1.5.1/dist/leaflet.js"></script>
    <script src="https://code.jquery.com/jquery-1.12.4.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/js/bootstrap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/leaflet@1.5.1/dist/leaflet.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap-theme.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.6.3/css/font-awesome.min.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.css"/>
    <link rel="stylesheet" href="https://rawcdn.githack.com/python-visualization/folium/master/folium/templates/leaflet.awesome.rotate.css"/>
    <style>html, body {width: 100%;height: 100%;margin: 0;padding: 0;}</style>
    <style>#map {position:absolute;top:0;bottom:0;right:0;left:0;}</style>
    
            <meta name="viewport" content="width=device-width,
                initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
            <style>
                #map_2b09cbfb923147c0b2d49acb4399a6e6 {
                    position: relative;
                    width: 100.0%;
                    height: 100.0%;
                    left: 0.0%;
                    top: 0.0%;
                }
            </style>
        
    <script src="https://cdn.jsdelivr.net/npm/leaflet-polylineoffset@1.1.1/leaflet.polylineoffset.min.js"></script>
    
                <style>
                    #float_image_8a9b60a6c54345c7b4397664966daea0 {
                        position:absolute;
                        bottom:5%;
                        left:86%;
                        }
                </style>
            
</head>
<body>    
    
            <div class="folium-map" id="map_2b09cbfb923147c0b2d49acb4399a6e6" ></div>
        
    
            <img id="float_image_8a9b60a6c54345c7b4397664966daea0" alt="float_image"
                 src="https://i.ibb.co/VxT9386/legend-01.png"
                 style="z-index: 999999">
            </img>
            
</body>
<script>    
    
            var map_2b09cbfb923147c0b2d49acb4399a6e6 = L.map(
                "map_2b09cbfb923147c0b2d49acb4399a6e6",
                {
                    center: [-24.25, 133.42],
                    crs: L.CRS.EPSG3857,
                    zoom: 4,
                    zoomControl: true,
                    preferCanvas: false,
                }
            );

            

        
    
            var tile_layer_0e361733a70740b8bbc7ba3a324d0c8b = L.tileLayer(
                "https://cartodb-basemaps-{s}.global.ssl.fastly.net/dark_all/{z}/{x}/{y}.png",
                {"attribution": "\u0026copy; \u003ca href=\"http://www.openstreetmap.org/copyright\"\u003eOpenStreetMap\u003c/a\u003e contributors \u0026copy; \u003ca href=\"http://cartodb.com/attributions\"\u003eCartoDB\u003c/a\u003e, CartoDB \u003ca href =\"http://cartodb.com/attributions\"\u003eattributions\u003c/a\u003e", "detectRetina": false, "maxNativeZoom": 18, "maxZoom": 18, "minZoom": 0, "noWrap": false, "opacity": 1, "subdomains": "abc", "tms": false}
            ).addTo(map_2b09cbfb923147c0b2d49acb4399a6e6);
        
    
            var feature_group_1e99830b659146f19e4de9fbf52339ba = L.featureGroup(
                {}
            ).addTo(map_2b09cbfb923147c0b2d49acb4399a6e6);
        
    
            var poly_line_offset_8230b29263974e25bd8f126acdc68a71 = L.polyline(
                [[-33.8678513, 151.2073212], [-32.9271507, 151.776474]],
                {"bubblingMouseEvents": true, "color": "#FFC000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#FFC000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_8230b29263974e25bd8f126acdc68a71.bindTooltip(
                `<div>
                     Departing: Sydney Arriving: Newcastle Aircraft Model: A320-232 Engine Model: V2527-5A Price: $90.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_e738c47cf825420698cd58043fe89900 = L.polyline(
                [[-32.9271507, 151.776474], [-33.8678513, 151.2073212]],
                {"bubblingMouseEvents": true, "color": "#FFC000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#FFC000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_e738c47cf825420698cd58043fe89900.bindTooltip(
                `<div>
                     Departing: Newcastle Arriving: Sydney Aircraft Model: A320-232 Engine Model: V2527-5A Price: $90.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_9042ff60a21d453bad7c1f6ef100fd4b = L.polyline(
                [[-33.8678513, 151.2073212], [-31.953913500000002, 141.45393959999998]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_9042ff60a21d453bad7c1f6ef100fd4b.bindTooltip(
                `<div>
                     Departing: Sydney Arriving: Broken Hill Aircraft Model: A320-232 Engine Model: V2527-5A Price: $130.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_47b84256d4274136853f97d6602439df = L.polyline(
                [[-31.953913500000002, 141.45393959999998], [-33.8678513, 151.2073212]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_47b84256d4274136853f97d6602439df.bindTooltip(
                `<div>
                     Departing: Broken Hill Arriving: Sydney Aircraft Model: A320-232 Engine Model: V2527-5A Price: $130.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_2374659da8af445897df8f0bd188d49d = L.polyline(
                [[-37.813999200000005, 144.9633179], [-35.283458700000004, 149.128067]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_2374659da8af445897df8f0bd188d49d.bindTooltip(
                `<div>
                     Departing: Melbourne Arriving: Canberra Aircraft Model: A320-232 Engine Model: V2527-5A Price: $140.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_c630c439d0a3409eb5c53f4302baec3d = L.polyline(
                [[-35.283458700000004, 149.128067], [-37.813999200000005, 144.9633179]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_c630c439d0a3409eb5c53f4302baec3d.bindTooltip(
                `<div>
                     Departing: Canberra Arriving: Melbourne Aircraft Model: A320-232 Engine Model: V2527-5A Price: $140.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_20ca51499cfb43e487933f6bb9c73108 = L.polyline(
                [[-37.813999200000005, 144.9633179], [-42.8793602, 147.3294067]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_20ca51499cfb43e487933f6bb9c73108.bindTooltip(
                `<div>
                     Departing: Melbourne Arriving: Hobart Aircraft Model: A320-232 Engine Model: V2527-5A Price: $130.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_e16f6573e0634b9c8c361cad2f87483d = L.polyline(
                [[-34.928661299999995, 138.59863280000002], [-31.953913500000002, 141.45393959999998]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_e16f6573e0634b9c8c361cad2f87483d.bindTooltip(
                `<div>
                     Departing: Adelaide Arriving: Broken Hill Aircraft Model: A320-232 Engine Model: V2527-5A Price: $100.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_dfb049f58b4a48a1993642a6555a6140 = L.polyline(
                [[-31.953913500000002, 141.45393959999998], [-34.928661299999995, 138.59863280000002]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_dfb049f58b4a48a1993642a6555a6140.bindTooltip(
                `<div>
                     Departing: Broken Hill Arriving: Adelaide Aircraft Model: A320-232 Engine Model: V2527-5A Price: $100.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_bff1b6c8b931481e9ddd417d4897837b = L.polyline(
                [[-31.952240000000003, 115.8613968], [-35.0269203, 117.8836899]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_bff1b6c8b931481e9ddd417d4897837b.bindTooltip(
                `<div>
                     Departing: Perth Arriving: Albany Aircraft Model: A320-232 Engine Model: V2527-5A Price: $100.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_13516de20bf74ddba4f569a39915e6aa = L.polyline(
                [[-31.952240000000003, 115.8613968], [-30.7461395, 121.47419740000002]],
                {"bubblingMouseEvents": true, "color": "#FFC000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#FFC000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_13516de20bf74ddba4f569a39915e6aa.bindTooltip(
                `<div>
                     Departing: Perth Arriving: Kalgoorlie Aircraft Model: A320-232 Engine Model: V2527-5A Price: $80.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_5665c148cf0e4df3b48755a1d56d95de = L.polyline(
                [[-31.952240000000003, 115.8613968], [-17.955379500000003, 122.23921969999999]],
                {"bubblingMouseEvents": true, "color": "#FFC000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#FFC000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_5665c148cf0e4df3b48755a1d56d95de.bindTooltip(
                `<div>
                     Departing: Perth Arriving: Broome Aircraft Model: A320-232 Engine Model: V2527-5A Price: $90.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_eb446be2655c47aaaa3165727fa37407 = L.polyline(
                [[-35.0269203, 117.8836899], [-31.952240000000003, 115.8613968]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_eb446be2655c47aaaa3165727fa37407.bindTooltip(
                `<div>
                     Departing: Albany Arriving: Perth Aircraft Model: A320-232 Engine Model: V2527-5A Price: $100.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_4292acb8dc8141dfb94578933161443d = L.polyline(
                [[-30.7461395, 121.47419740000002], [-31.952240000000003, 115.8613968]],
                {"bubblingMouseEvents": true, "color": "#FFC000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#FFC000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_4292acb8dc8141dfb94578933161443d.bindTooltip(
                `<div>
                     Departing: Kalgoorlie Arriving: Perth Aircraft Model: A320-232 Engine Model: V2527-5A Price: $80.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_b03dc90649ab440d95d0e457afd24d94 = L.polyline(
                [[-41.438758899999996, 147.13467409999998], [-42.8793602, 147.3294067]],
                {"bubblingMouseEvents": true, "color": "#FFC000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#FFC000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_b03dc90649ab440d95d0e457afd24d94.bindTooltip(
                `<div>
                     Departing: Launceston Arriving: Hobart Aircraft Model: A320-232 Engine Model: V2527-5A Price: $80.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_7d3dd18869ea4d1d8997a8957faebe84 = L.polyline(
                [[-42.8793602, 147.3294067], [-41.438758899999996, 147.13467409999998]],
                {"bubblingMouseEvents": true, "color": "#FFC000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#FFC000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_7d3dd18869ea4d1d8997a8957faebe84.bindTooltip(
                `<div>
                     Departing: Hobart Arriving: Launceston Aircraft Model: A320-232 Engine Model: V2527-5A Price: $80.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_79c9a649e75f4d418a1e6ba62f9143fd = L.polyline(
                [[-33.8678513, 151.2073212], [-32.9271507, 151.776474]],
                {"bubblingMouseEvents": true, "color": "#FFC000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#FFC000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_79c9a649e75f4d418a1e6ba62f9143fd.bindTooltip(
                `<div>
                     Departing: Sydney Arriving: Newcastle Aircraft Model: A320-232 Engine Model: V2527-5A Price: $90.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_63d406a7e0904ae39858c7e65ff26c9f = L.polyline(
                [[-32.9271507, 151.776474], [-33.8678513, 151.2073212]],
                {"bubblingMouseEvents": true, "color": "#FFC000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#FFC000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_63d406a7e0904ae39858c7e65ff26c9f.bindTooltip(
                `<div>
                     Departing: Newcastle Arriving: Sydney Aircraft Model: A320-232 Engine Model: V2527-5A Price: $90.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_32f381c8a1cb40af894cb35b76b1439e = L.polyline(
                [[-33.8678513, 151.2073212], [-31.953913500000002, 141.45393959999998]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_32f381c8a1cb40af894cb35b76b1439e.bindTooltip(
                `<div>
                     Departing: Sydney Arriving: Broken Hill Aircraft Model: A320-232 Engine Model: V2527-5A Price: $130.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_8835c19cbca24b6db11c7e8d4b73eb7f = L.polyline(
                [[-31.953913500000002, 141.45393959999998], [-33.8678513, 151.2073212]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_8835c19cbca24b6db11c7e8d4b73eb7f.bindTooltip(
                `<div>
                     Departing: Broken Hill Arriving: Sydney Aircraft Model: A320-232 Engine Model: V2527-5A Price: $130.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_ccc358db62a64dc9bc3037d27105ebc7 = L.polyline(
                [[-37.813999200000005, 144.9633179], [-35.283458700000004, 149.128067]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_ccc358db62a64dc9bc3037d27105ebc7.bindTooltip(
                `<div>
                     Departing: Melbourne Arriving: Canberra Aircraft Model: A320-232 Engine Model: V2527-5A Price: $140.00 Space Class: B 
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_f91fd59951334a58b01a6e4ca959d768 = L.polyline(
                [[-35.283458700000004, 149.128067], [-37.813999200000005, 144.9633179]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_f91fd59951334a58b01a6e4ca959d768.bindTooltip(
                `<div>
                     Departing: Canberra Arriving: Melbourne Aircraft Model: A320-232 Engine Model: V2527-5A Price: $140.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_ca5ee70e831345d7a3a2bad8f8982d48 = L.polyline(
                [[-37.813999200000005, 144.9633179], [-42.8793602, 147.3294067]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_ca5ee70e831345d7a3a2bad8f8982d48.bindTooltip(
                `<div>
                     Departing: Melbourne Arriving: Hobart Aircraft Model: A320-232 Engine Model: V2527-5A Price: $130.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_41ce754c05bf42f1b854ea9ba94709c7 = L.polyline(
                [[-34.928661299999995, 138.59863280000002], [-31.953913500000002, 141.45393959999998]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_41ce754c05bf42f1b854ea9ba94709c7.bindTooltip(
                `<div>
                     Departing: Adelaide Arriving: Broken Hill Aircraft Model: A320-232 Engine Model: V2527-5A Price: $100.00 Space Class: C
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_1020ddbab73144a093b45887a6110979 = L.polyline(
                [[-31.953913500000002, 141.45393959999998], [-34.928661299999995, 138.59863280000002]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_1020ddbab73144a093b45887a6110979.bindTooltip(
                `<div>
                     Departing: Broken Hill Arriving: Adelaide Aircraft Model: A320-232 Engine Model: V2527-5A Price: $100.00 Space Class: C
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_6de143d31c964d6aab31fc2cb7cf4064 = L.polyline(
                [[-31.952240000000003, 115.8613968], [-35.0269203, 117.8836899]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_6de143d31c964d6aab31fc2cb7cf4064.bindTooltip(
                `<div>
                     Departing: Perth Arriving: Albany Aircraft Model: A320-232 Engine Model: V2527-5A Price: $100.00 Space Class: C
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_ddedf491b8304d02b0f5717fbf65b186 = L.polyline(
                [[-31.952240000000003, 115.8613968], [-30.7461395, 121.47419740000002]],
                {"bubblingMouseEvents": true, "color": "#FFC000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#FFC000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_ddedf491b8304d02b0f5717fbf65b186.bindTooltip(
                `<div>
                     Departing: Perth Arriving: Kalgoorlie Aircraft Model: A320-232 Engine Model: V2527-5A Price: $80.00 Space Class: C
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_161d5188c0484e98bca66e726640d809 = L.polyline(
                [[-31.952240000000003, 115.8613968], [-17.955379500000003, 122.23921969999999]],
                {"bubblingMouseEvents": true, "color": "#FFC000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#FFC000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_161d5188c0484e98bca66e726640d809.bindTooltip(
                `<div>
                     Departing: Perth Arriving: Broome Aircraft Model: A320-232 Engine Model: V2527-5A Price: $90.00 Space Class: C
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_5848320081d44c509f9b6ce19032d34a = L.polyline(
                [[-35.0269203, 117.8836899], [-31.952240000000003, 115.8613968]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_5848320081d44c509f9b6ce19032d34a.bindTooltip(
                `<div>
                     Departing: Albany Arriving: Perth Aircraft Model: A320-232 Engine Model: V2527-5A Price: $100.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_d76432ca48914c4281b8a42a27f9ac45 = L.polyline(
                [[-30.7461395, 121.47419740000002], [-31.952240000000003, 115.8613968]],
                {"bubblingMouseEvents": true, "color": "#FFC000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#FFC000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_d76432ca48914c4281b8a42a27f9ac45.bindTooltip(
                `<div>
                     Departing: Kalgoorlie Arriving: Perth Aircraft Model: A320-232 Engine Model: V2527-5A Price: $80.00 Space Class: C
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_4664760937eb407095e4b04733800ebf = L.polyline(
                [[-41.438758899999996, 147.13467409999998], [-42.8793602, 147.3294067]],
                {"bubblingMouseEvents": true, "color": "#FFC000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#FFC000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_4664760937eb407095e4b04733800ebf.bindTooltip(
                `<div>
                     Departing: Launceston Arriving: Hobart Aircraft Model: A320-232 Engine Model: V2527-5A Price: $80.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_e540354a9b6544c49b7d896520de2442 = L.polyline(
                [[-42.8793602, 147.3294067], [-41.438758899999996, 147.13467409999998]],
                {"bubblingMouseEvents": true, "color": "#FFC000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#FFC000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_e540354a9b6544c49b7d896520de2442.bindTooltip(
                `<div>
                     Departing: Hobart Arriving: Launceston Aircraft Model: A320-232 Engine Model: V2527-5A Price: $80.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_2a2481dd1f3b43c8900879a8688293a3 = L.polyline(
                [[-33.8678513, 151.2073212], [-32.9271507, 151.776474]],
                {"bubblingMouseEvents": true, "color": "#FFC000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#FFC000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_2a2481dd1f3b43c8900879a8688293a3.bindTooltip(
                `<div>
                     Departing: Sydney Arriving: Newcastle Aircraft Model: A320-232 Engine Model: V2527-5A Price: $90.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_06d0177b1cd74411b3609074c93037d6 = L.polyline(
                [[-32.9271507, 151.776474], [-33.8678513, 151.2073212]],
                {"bubblingMouseEvents": true, "color": "#FFC000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#FFC000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_06d0177b1cd74411b3609074c93037d6.bindTooltip(
                `<div>
                     Departing: Newcastle Arriving: Sydney Aircraft Model: A320-232 Engine Model: V2527-5A Price: $90.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_65905a005f1f40c49a637956e5327db6 = L.polyline(
                [[-33.8678513, 151.2073212], [-31.953913500000002, 141.45393959999998]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_65905a005f1f40c49a637956e5327db6.bindTooltip(
                `<div>
                     Departing: Sydney Arriving: Broken Hill Aircraft Model: A320-232 Engine Model: V2527-5A Price: $130.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_3ff47a2f84e94b7b84c3603309f2b1b5 = L.polyline(
                [[-31.953913500000002, 141.45393959999998], [-33.8678513, 151.2073212]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_3ff47a2f84e94b7b84c3603309f2b1b5.bindTooltip(
                `<div>
                     Departing: Broken Hill Arriving: Sydney Aircraft Model: A320-232 Engine Model: V2527-5A Price: $130.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_c02676e7e0194134a69d1caf62634613 = L.polyline(
                [[-37.813999200000005, 144.9633179], [-35.283458700000004, 149.128067]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_c02676e7e0194134a69d1caf62634613.bindTooltip(
                `<div>
                     Departing: Melbourne Arriving: Canberra Aircraft Model: A320-232 Engine Model: V2527-5A Price: $140.00 Space Class: B 
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_a8705b4087b04f218587235ce522b3c7 = L.polyline(
                [[-35.283458700000004, 149.128067], [-37.813999200000005, 144.9633179]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_a8705b4087b04f218587235ce522b3c7.bindTooltip(
                `<div>
                     Departing: Canberra Arriving: Melbourne Aircraft Model: A320-232 Engine Model: V2527-5A Price: $140.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_8bebd706c5054269aac6b7f41f0c92d5 = L.polyline(
                [[-37.813999200000005, 144.9633179], [-42.8793602, 147.3294067]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_8bebd706c5054269aac6b7f41f0c92d5.bindTooltip(
                `<div>
                     Departing: Melbourne Arriving: Hobart Aircraft Model: A320-232 Engine Model: V2527-5A Price: $130.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_5fa30d01672f478ca6fbe2db43bac70b = L.polyline(
                [[-34.928661299999995, 138.59863280000002], [-31.953913500000002, 141.45393959999998]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_5fa30d01672f478ca6fbe2db43bac70b.bindTooltip(
                `<div>
                     Departing: Adelaide Arriving: Broken Hill Aircraft Model: A320-232 Engine Model: V2527-5A Price: $100.00 Space Class: C
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_6108d1722d2041de94b75be703d83d30 = L.polyline(
                [[-31.953913500000002, 141.45393959999998], [-34.928661299999995, 138.59863280000002]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_6108d1722d2041de94b75be703d83d30.bindTooltip(
                `<div>
                     Departing: Broken Hill Arriving: Adelaide Aircraft Model: A320-232 Engine Model: V2527-5A Price: $100.00 Space Class: C
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_c61430897d15415a9ece92adaa174c4c = L.polyline(
                [[-31.952240000000003, 115.8613968], [-35.0269203, 117.8836899]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_c61430897d15415a9ece92adaa174c4c.bindTooltip(
                `<div>
                     Departing: Perth Arriving: Albany Aircraft Model: A320-232 Engine Model: V2527-5A Price: $100.00 Space Class: C
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_9dd4a7c546384a399eddcc9d49213a44 = L.polyline(
                [[-31.952240000000003, 115.8613968], [-30.7461395, 121.47419740000002]],
                {"bubblingMouseEvents": true, "color": "#FFC000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#FFC000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_9dd4a7c546384a399eddcc9d49213a44.bindTooltip(
                `<div>
                     Departing: Perth Arriving: Kalgoorlie Aircraft Model: A320-232 Engine Model: V2527-5A Price: $80.00 Space Class: C
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_c5cecbb95c134830a7750b881d4d94d2 = L.polyline(
                [[-31.952240000000003, 115.8613968], [-17.955379500000003, 122.23921969999999]],
                {"bubblingMouseEvents": true, "color": "#FFC000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#FFC000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_c5cecbb95c134830a7750b881d4d94d2.bindTooltip(
                `<div>
                     Departing: Perth Arriving: Broome Aircraft Model: A320-232 Engine Model: V2527-5A Price: $90.00 Space Class: C
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_419720ea218142fb986b1ec6a3840b89 = L.polyline(
                [[-35.0269203, 117.8836899], [-31.952240000000003, 115.8613968]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_419720ea218142fb986b1ec6a3840b89.bindTooltip(
                `<div>
                     Departing: Albany Arriving: Perth Aircraft Model: A320-232 Engine Model: V2527-5A Price: $100.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_7f66b2b74d784d01b480873ca0f26a0e = L.polyline(
                [[-30.7461395, 121.47419740000002], [-31.952240000000003, 115.8613968]],
                {"bubblingMouseEvents": true, "color": "#FFC000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#FFC000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_7f66b2b74d784d01b480873ca0f26a0e.bindTooltip(
                `<div>
                     Departing: Kalgoorlie Arriving: Perth Aircraft Model: A320-232 Engine Model: V2527-5A Price: $80.00 Space Class: C
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_166b5ceba7c1451bbc7483719d4d2823 = L.polyline(
                [[-41.438758899999996, 147.13467409999998], [-42.8793602, 147.3294067]],
                {"bubblingMouseEvents": true, "color": "#FFC000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#FFC000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_166b5ceba7c1451bbc7483719d4d2823.bindTooltip(
                `<div>
                     Departing: Launceston Arriving: Hobart Aircraft Model: A320-232 Engine Model: V2527-5A Price: $80.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_7fa8acbe48c94db6bc07e3d149a7f0fb = L.polyline(
                [[-42.8793602, 147.3294067], [-41.438758899999996, 147.13467409999998]],
                {"bubblingMouseEvents": true, "color": "#FFC000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#FFC000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_7fa8acbe48c94db6bc07e3d149a7f0fb.bindTooltip(
                `<div>
                     Departing: Hobart Arriving: Launceston Aircraft Model: A320-232 Engine Model: V2527-5A Price: $80.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_1f3910622a294e59ab4cc6231096b254 = L.polyline(
                [[-33.8678513, 151.2073212], [-32.9271507, 151.776474]],
                {"bubblingMouseEvents": true, "color": "#FFC000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#FFC000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_1f3910622a294e59ab4cc6231096b254.bindTooltip(
                `<div>
                     Departing: Sydney Arriving: Newcastle Aircraft Model: A320-232 Engine Model: V2527-5A Price: $90.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_ba2daecb0386460fbc87c4abe2e83f87 = L.polyline(
                [[-32.9271507, 151.776474], [-33.8678513, 151.2073212]],
                {"bubblingMouseEvents": true, "color": "#FFC000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#FFC000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_ba2daecb0386460fbc87c4abe2e83f87.bindTooltip(
                `<div>
                     Departing: Newcastle Arriving: Sydney Aircraft Model: A320-232 Engine Model: V2527-5A Price: $90.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_541a87fb6bf14621900935c7f63fda07 = L.polyline(
                [[-33.8678513, 151.2073212], [-31.953913500000002, 141.45393959999998]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_541a87fb6bf14621900935c7f63fda07.bindTooltip(
                `<div>
                     Departing: Sydney Arriving: Broken Hill Aircraft Model: A320-232 Engine Model: V2527-5A Price: $130.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_1a3fe4c9d8f04caabd4eeb101150c042 = L.polyline(
                [[-31.953913500000002, 141.45393959999998], [-33.8678513, 151.2073212]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_1a3fe4c9d8f04caabd4eeb101150c042.bindTooltip(
                `<div>
                     Departing: Broken Hill Arriving: Sydney Aircraft Model: A320-232 Engine Model: V2527-5A Price: $130.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_05a89934b632467ebcda8237ddde69a6 = L.polyline(
                [[-37.813999200000005, 144.9633179], [-35.283458700000004, 149.128067]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_05a89934b632467ebcda8237ddde69a6.bindTooltip(
                `<div>
                     Departing: Melbourne Arriving: Canberra Aircraft Model: A320-232 Engine Model: V2527-5A Price: $140.00 Space Class: B 
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_95ac82683b524eb29850bdfd1c67cd5f = L.polyline(
                [[-35.283458700000004, 149.128067], [-37.813999200000005, 144.9633179]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_95ac82683b524eb29850bdfd1c67cd5f.bindTooltip(
                `<div>
                     Departing: Canberra Arriving: Melbourne Aircraft Model: A320-232 Engine Model: V2527-5A Price: $140.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_e98171e7f4df473ead0a0c430a0cc672 = L.polyline(
                [[-37.813999200000005, 144.9633179], [-42.8793602, 147.3294067]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_e98171e7f4df473ead0a0c430a0cc672.bindTooltip(
                `<div>
                     Departing: Melbourne Arriving: Hobart Aircraft Model: A320-232 Engine Model: V2527-5A Price: $130.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_e11a1a03a17b48b9b075456e2112d55e = L.polyline(
                [[-34.928661299999995, 138.59863280000002], [-31.953913500000002, 141.45393959999998]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_e11a1a03a17b48b9b075456e2112d55e.bindTooltip(
                `<div>
                     Departing: Adelaide Arriving: Broken Hill Aircraft Model: A320-232 Engine Model: V2527-5A Price: $100.00 Space Class: C
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_385c2af3f880457382eacc78a62f2319 = L.polyline(
                [[-31.953913500000002, 141.45393959999998], [-34.928661299999995, 138.59863280000002]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_385c2af3f880457382eacc78a62f2319.bindTooltip(
                `<div>
                     Departing: Broken Hill Arriving: Adelaide Aircraft Model: A320-232 Engine Model: V2527-5A Price: $100.00 Space Class: C
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_a777a3469d9243968c4db1a55fc26e79 = L.polyline(
                [[-31.952240000000003, 115.8613968], [-35.0269203, 117.8836899]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_a777a3469d9243968c4db1a55fc26e79.bindTooltip(
                `<div>
                     Departing: Perth Arriving: Albany Aircraft Model: A320-232 Engine Model: V2527-5A Price: $100.00 Space Class: C
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_ef5cae9df61a4041ba1ddb1f2223e5ec = L.polyline(
                [[-31.952240000000003, 115.8613968], [-30.7461395, 121.47419740000002]],
                {"bubblingMouseEvents": true, "color": "#FFC000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#FFC000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_ef5cae9df61a4041ba1ddb1f2223e5ec.bindTooltip(
                `<div>
                     Departing: Perth Arriving: Kalgoorlie Aircraft Model: A320-232 Engine Model: V2527-5A Price: $80.00 Space Class: C
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_bcc70f549f184f9bac71ba64253beb3c = L.polyline(
                [[-31.952240000000003, 115.8613968], [-17.955379500000003, 122.23921969999999]],
                {"bubblingMouseEvents": true, "color": "#FFC000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#FFC000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_bcc70f549f184f9bac71ba64253beb3c.bindTooltip(
                `<div>
                     Departing: Perth Arriving: Broome Aircraft Model: A320-232 Engine Model: V2527-5A Price: $90.00 Space Class: C
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_1d6f762aab9448a597a0b2f6a2e11370 = L.polyline(
                [[-35.0269203, 117.8836899], [-31.952240000000003, 115.8613968]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_1d6f762aab9448a597a0b2f6a2e11370.bindTooltip(
                `<div>
                     Departing: Albany Arriving: Perth Aircraft Model: A320-232 Engine Model: V2527-5A Price: $100.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_17417f9ad1b542d19bb4f3ccfc428f36 = L.polyline(
                [[-30.7461395, 121.47419740000002], [-31.952240000000003, 115.8613968]],
                {"bubblingMouseEvents": true, "color": "#FFC000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#FFC000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_17417f9ad1b542d19bb4f3ccfc428f36.bindTooltip(
                `<div>
                     Departing: Kalgoorlie Arriving: Perth Aircraft Model: A320-232 Engine Model: V2527-5A Price: $80.00 Space Class: C
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_e8ef9f4d0a3d43af8d076ec61fa9ed16 = L.polyline(
                [[-41.438758899999996, 147.13467409999998], [-42.8793602, 147.3294067]],
                {"bubblingMouseEvents": true, "color": "#FFC000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#FFC000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_e8ef9f4d0a3d43af8d076ec61fa9ed16.bindTooltip(
                `<div>
                     Departing: Launceston Arriving: Hobart Aircraft Model: A320-232 Engine Model: V2527-5A Price: $80.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_6bf7bc0fc12b4ffe9c9027365f3ddbf6 = L.polyline(
                [[-42.8793602, 147.3294067], [-41.438758899999996, 147.13467409999998]],
                {"bubblingMouseEvents": true, "color": "#FFC000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#FFC000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_1e99830b659146f19e4de9fbf52339ba);
        
    
            poly_line_offset_6bf7bc0fc12b4ffe9c9027365f3ddbf6.bindTooltip(
                `<div>
                     Departing: Hobart Arriving: Launceston Aircraft Model: A320-232 Engine Model: V2527-5A Price: $80.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var feature_group_8581070929d640f782a848959b6812e9 = L.featureGroup(
                {}
            ).addTo(map_2b09cbfb923147c0b2d49acb4399a6e6);
        
    
            var poly_line_offset_e4eeec9e36944501ab2429067caa603d = L.polyline(
                [[-33.8678513, 151.2073212], [-27.4679394, 153.02809140000002]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_8581070929d640f782a848959b6812e9);
        
    
            poly_line_offset_e4eeec9e36944501ab2429067caa603d.bindTooltip(
                `<div>
                     Departing: Sydney Arriving: Brisbane Aircraft Model: A330-202 Engine Model: CF6-80E142 Price: $180.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_84aec7a5d3b740448c35b89c1cc63dc7 = L.polyline(
                [[-20.7255748, 139.4927085], [-27.4679394, 153.02809140000002]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_8581070929d640f782a848959b6812e9);
        
    
            poly_line_offset_84aec7a5d3b740448c35b89c1cc63dc7.bindTooltip(
                `<div>
                     Departing: Mt Isa Arriving: Brisbane Aircraft Model: A330-202 Engine Model: CF6-80E142 Price: $170.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_07118ffc5bc54bd78672904723403510 = L.polyline(
                [[-23.380319600000004, 150.50595090000002], [-27.4679394, 153.02809140000002]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_8581070929d640f782a848959b6812e9);
        
    
            poly_line_offset_07118ffc5bc54bd78672904723403510.bindTooltip(
                `<div>
                     Departing: Rockhampton Arriving: Brisbane Aircraft Model: A330-202 Engine Model: CF6-80E142 Price: $180.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_9f573960ddc5411f8b1fb4326cbbb222 = L.polyline(
                [[-33.8678513, 151.2073212], [-27.4679394, 153.02809140000002]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_8581070929d640f782a848959b6812e9);
        
    
            poly_line_offset_9f573960ddc5411f8b1fb4326cbbb222.bindTooltip(
                `<div>
                     Departing: Sydney Arriving: Brisbane Aircraft Model: A330-202 Engine Model: CF6-80E142 Price: $180.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_5bc35fd5709347f69d6763704af3dca3 = L.polyline(
                [[-20.7255748, 139.4927085], [-27.4679394, 153.02809140000002]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_8581070929d640f782a848959b6812e9);
        
    
            poly_line_offset_5bc35fd5709347f69d6763704af3dca3.bindTooltip(
                `<div>
                     Departing: Mt Isa Arriving: Brisbane Aircraft Model: A330-202 Engine Model: CF6-80E142 Price: $170.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_fe4445f727dd4a458aa93e97d7bebce3 = L.polyline(
                [[-23.380319600000004, 150.50595090000002], [-27.4679394, 153.02809140000002]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_8581070929d640f782a848959b6812e9);
        
    
            poly_line_offset_fe4445f727dd4a458aa93e97d7bebce3.bindTooltip(
                `<div>
                     Departing: Rockhampton Arriving: Brisbane Aircraft Model: A330-202 Engine Model: CF6-80E142 Price: $180.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_c67da8ab0270432fa76683b7cb3f99e3 = L.polyline(
                [[-33.8678513, 151.2073212], [-27.4679394, 153.02809140000002]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_8581070929d640f782a848959b6812e9);
        
    
            poly_line_offset_c67da8ab0270432fa76683b7cb3f99e3.bindTooltip(
                `<div>
                     Departing: Sydney Arriving: Brisbane Aircraft Model: A330-202 Engine Model: CF6-80E142 Price: $180.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_1f4eda9c644d427c85c42f911d5331b2 = L.polyline(
                [[-20.7255748, 139.4927085], [-27.4679394, 153.02809140000002]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_8581070929d640f782a848959b6812e9);
        
    
            poly_line_offset_1f4eda9c644d427c85c42f911d5331b2.bindTooltip(
                `<div>
                     Departing: Mt Isa Arriving: Brisbane Aircraft Model: A330-202 Engine Model: CF6-80E142 Price: $170.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_149ca3b34c2d414d84814469304ec9bb = L.polyline(
                [[-23.380319600000004, 150.50595090000002], [-27.4679394, 153.02809140000002]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_8581070929d640f782a848959b6812e9);
        
    
            poly_line_offset_149ca3b34c2d414d84814469304ec9bb.bindTooltip(
                `<div>
                     Departing: Rockhampton Arriving: Brisbane Aircraft Model: A330-202 Engine Model: CF6-80E142 Price: $180.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_d0cd593c49c444ec962f85e37cb913fc = L.polyline(
                [[-33.8678513, 151.2073212], [-27.4679394, 153.02809140000002]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_8581070929d640f782a848959b6812e9);
        
    
            poly_line_offset_d0cd593c49c444ec962f85e37cb913fc.bindTooltip(
                `<div>
                     Departing: Sydney Arriving: Brisbane Aircraft Model: A330-202 Engine Model: CF6-80E142 Price: $180.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_2e089e33d73c4b95904d95f9e2cdc59a = L.polyline(
                [[-20.7255748, 139.4927085], [-27.4679394, 153.02809140000002]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_8581070929d640f782a848959b6812e9);
        
    
            poly_line_offset_2e089e33d73c4b95904d95f9e2cdc59a.bindTooltip(
                `<div>
                     Departing: Mt Isa Arriving: Brisbane Aircraft Model: A330-202 Engine Model: CF6-80E142 Price: $170.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_678c87c291c24f5a83897e0b47befe2e = L.polyline(
                [[-23.380319600000004, 150.50595090000002], [-27.4679394, 153.02809140000002]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_8581070929d640f782a848959b6812e9);
        
    
            poly_line_offset_678c87c291c24f5a83897e0b47befe2e.bindTooltip(
                `<div>
                     Departing: Rockhampton Arriving: Brisbane Aircraft Model: A330-202 Engine Model: CF6-80E142 Price: $180.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var feature_group_5045b6969442493abcc8e49e0c9313a7 = L.featureGroup(
                {}
            ).addTo(map_2b09cbfb923147c0b2d49acb4399a6e6);
        
    
            var poly_line_offset_9d7ff83da5ca49a79a06a5543d8ff096 = L.polyline(
                [[-33.8678513, 151.2073212], [-37.813999200000005, 144.9633179]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_5045b6969442493abcc8e49e0c9313a7);
        
    
            poly_line_offset_9d7ff83da5ca49a79a06a5543d8ff096.bindTooltip(
                `<div>
                     Departing: Sydney Arriving: Melbourne Aircraft Model: A330-203 Engine Model: CF6-80E142 Price: $180.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_b877376702d646a98c6a131c68c12d96 = L.polyline(
                [[-34.928661299999995, 138.59863280000002], [-31.952240000000003, 115.8613968]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_5045b6969442493abcc8e49e0c9313a7);
        
    
            poly_line_offset_b877376702d646a98c6a131c68c12d96.bindTooltip(
                `<div>
                     Departing: Adelaide Arriving: Perth Aircraft Model: A330-203 Engine Model: CF6-80E142 Price: $200.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_757f572a028940cfb51d5d6dbaf65e62 = L.polyline(
                [[-34.928661299999995, 138.59863280000002], [-12.4611301, 130.8418427]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_5045b6969442493abcc8e49e0c9313a7);
        
    
            poly_line_offset_757f572a028940cfb51d5d6dbaf65e62.bindTooltip(
                `<div>
                     Departing: Adelaide Arriving: Darwin Aircraft Model: A330-203 Engine Model: CF6-80E142 Price: $230.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_c2ce7181fe35425792b8cfd69d69c1b3 = L.polyline(
                [[-12.4611301, 130.8418427], [-34.928661299999995, 138.59863280000002]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_5045b6969442493abcc8e49e0c9313a7);
        
    
            poly_line_offset_c2ce7181fe35425792b8cfd69d69c1b3.bindTooltip(
                `<div>
                     Departing: Darwin Arriving: Adelaide Aircraft Model: A330-203 Engine Model: CF6-80E142 Price: $230.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_dee69593fbbe41e5a99773135bcd2563 = L.polyline(
                [[-31.952240000000003, 115.8613968], [-34.928661299999995, 138.59863280000002]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_5045b6969442493abcc8e49e0c9313a7);
        
    
            poly_line_offset_dee69593fbbe41e5a99773135bcd2563.bindTooltip(
                `<div>
                     Departing: Perth Arriving: Adelaide Aircraft Model: A330-203 Engine Model: CF6-80E142 Price: $220.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_f52bfd00d65041efa4aed9ce31ec4c64 = L.polyline(
                [[-27.4679394, 153.02809140000002], [-33.8651, 151.2099]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_5045b6969442493abcc8e49e0c9313a7);
        
    
            poly_line_offset_f52bfd00d65041efa4aed9ce31ec4c64.bindTooltip(
                `<div>
                     Departing: Brisbane Arriving: Sydney Aircraft Model: A330-203 Engine Model: CF6-80E142 Price: $170.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_b2a9ed09acc340baa09de26cfd4ca069 = L.polyline(
                [[-27.4679394, 153.02809140000002], [-16.923040399999998, 145.7662506]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_5045b6969442493abcc8e49e0c9313a7);
        
    
            poly_line_offset_b2a9ed09acc340baa09de26cfd4ca069.bindTooltip(
                `<div>
                     Departing: Brisbane Arriving: Cairns Aircraft Model: A330-203 Engine Model: CF6-80E142 Price: $230.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_3b7d68c069e243509b42d5ea3d4ce61f = L.polyline(
                [[-27.4679394, 153.02809140000002], [-12.4611301, 130.8418427]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_5045b6969442493abcc8e49e0c9313a7);
        
    
            poly_line_offset_3b7d68c069e243509b42d5ea3d4ce61f.bindTooltip(
                `<div>
                     Departing: Brisbane Arriving: Darwin Aircraft Model: A330-203 Engine Model: CF6-80E142 Price: $240.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_b80aa8e8bf564796bd8d19b6ea5bf928 = L.polyline(
                [[-16.923040399999998, 145.7662506], [-27.4679394, 153.02809140000002]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_5045b6969442493abcc8e49e0c9313a7);
        
    
            poly_line_offset_b80aa8e8bf564796bd8d19b6ea5bf928.bindTooltip(
                `<div>
                     Departing: Cairns Arriving: Brisbane Aircraft Model: A330-203 Engine Model: CF6-80E142 Price: $230.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_a0580ee02d8e46a0bc455df30bccf2c3 = L.polyline(
                [[-12.4611301, 130.8418427], [-27.4679394, 153.02809140000002]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_5045b6969442493abcc8e49e0c9313a7);
        
    
            poly_line_offset_a0580ee02d8e46a0bc455df30bccf2c3.bindTooltip(
                `<div>
                     Departing: Darwin Arriving: Brisbane Aircraft Model: A330-203 Engine Model: CF6-80E142 Price: $240.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_f04a4463f2b44391acb6a0daf77972e5 = L.polyline(
                [[-33.8678513, 151.2073212], [-37.813999200000005, 144.9633179]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_5045b6969442493abcc8e49e0c9313a7);
        
    
            poly_line_offset_f04a4463f2b44391acb6a0daf77972e5.bindTooltip(
                `<div>
                     Departing: Sydney Arriving: Melbourne Aircraft Model: A330-203 Engine Model: CF6-80E142 Price: $180.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_caaed21bb0fd45b0b80397cb148f5620 = L.polyline(
                [[-34.928661299999995, 138.59863280000002], [-31.952240000000003, 115.8613968]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_5045b6969442493abcc8e49e0c9313a7);
        
    
            poly_line_offset_caaed21bb0fd45b0b80397cb148f5620.bindTooltip(
                `<div>
                     Departing: Adelaide Arriving: Perth Aircraft Model: A330-203 Engine Model: CF6-80E142 Price: $200.00 Space Class: D
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_dd9ea4c49bef43229a357d5895a45e3e = L.polyline(
                [[-34.928661299999995, 138.59863280000002], [-12.4611301, 130.8418427]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_5045b6969442493abcc8e49e0c9313a7);
        
    
            poly_line_offset_dd9ea4c49bef43229a357d5895a45e3e.bindTooltip(
                `<div>
                     Departing: Adelaide Arriving: Darwin Aircraft Model: A330-203 Engine Model: CF6-80E142 Price: $230.00 Space Class: D
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_f0838d48ef4d40e5b97066006e08237a = L.polyline(
                [[-12.4611301, 130.8418427], [-34.928661299999995, 138.59863280000002]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_5045b6969442493abcc8e49e0c9313a7);
        
    
            poly_line_offset_f0838d48ef4d40e5b97066006e08237a.bindTooltip(
                `<div>
                     Departing: Darwin Arriving: Adelaide Aircraft Model: A330-203 Engine Model: CF6-80E142 Price: $230.00 Space Class: D
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_a8ebd13a2f41456b9fc81e5de6750a03 = L.polyline(
                [[-31.952240000000003, 115.8613968], [-34.928661299999995, 138.59863280000002]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_5045b6969442493abcc8e49e0c9313a7);
        
    
            poly_line_offset_a8ebd13a2f41456b9fc81e5de6750a03.bindTooltip(
                `<div>
                     Departing: Perth Arriving: Adelaide Aircraft Model: A330-203 Engine Model: CF6-80E142 Price: $220.00 Space Class: D
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_717d08b27c5b4d63af9ff67538945edb = L.polyline(
                [[-27.4679394, 153.02809140000002], [-33.8651, 151.2099]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_5045b6969442493abcc8e49e0c9313a7);
        
    
            poly_line_offset_717d08b27c5b4d63af9ff67538945edb.bindTooltip(
                `<div>
                     Departing: Brisbane Arriving: Sydney Aircraft Model: A330-203 Engine Model: CF6-80E142 Price: $170.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_249ab852a0fd4ced83d5ba88b3275bfc = L.polyline(
                [[-27.4679394, 153.02809140000002], [-16.923040399999998, 145.7662506]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_5045b6969442493abcc8e49e0c9313a7);
        
    
            poly_line_offset_249ab852a0fd4ced83d5ba88b3275bfc.bindTooltip(
                `<div>
                     Departing: Brisbane Arriving: Cairns Aircraft Model: A330-203 Engine Model: CF6-80E142 Price: $230.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_c9d8518025cb4b03a34a4b84f51b8c50 = L.polyline(
                [[-27.4679394, 153.02809140000002], [-12.4611301, 130.8418427]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_5045b6969442493abcc8e49e0c9313a7);
        
    
            poly_line_offset_c9d8518025cb4b03a34a4b84f51b8c50.bindTooltip(
                `<div>
                     Departing: Brisbane Arriving: Darwin Aircraft Model: A330-203 Engine Model: CF6-80E142 Price: $240.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_0711420fa8714902804a85cddf5743ff = L.polyline(
                [[-16.923040399999998, 145.7662506], [-27.4679394, 153.02809140000002]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_5045b6969442493abcc8e49e0c9313a7);
        
    
            poly_line_offset_0711420fa8714902804a85cddf5743ff.bindTooltip(
                `<div>
                     Departing: Cairns Arriving: Brisbane Aircraft Model: A330-203 Engine Model: CF6-80E142 Price: $230.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_39edeb309e604c8185db7d33db0e562a = L.polyline(
                [[-12.4611301, 130.8418427], [-27.4679394, 153.02809140000002]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_5045b6969442493abcc8e49e0c9313a7);
        
    
            poly_line_offset_39edeb309e604c8185db7d33db0e562a.bindTooltip(
                `<div>
                     Departing: Darwin Arriving: Brisbane Aircraft Model: A330-203 Engine Model: CF6-80E142 Price: $240.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_bf9c768147574ecfa82cf26e2df91b37 = L.polyline(
                [[-33.8678513, 151.2073212], [-37.813999200000005, 144.9633179]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_5045b6969442493abcc8e49e0c9313a7);
        
    
            poly_line_offset_bf9c768147574ecfa82cf26e2df91b37.bindTooltip(
                `<div>
                     Departing: Sydney Arriving: Melbourne Aircraft Model: A330-203 Engine Model: CF6-80E142 Price: $180.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_91c941ee9b914267af8bae6218ea2194 = L.polyline(
                [[-34.928661299999995, 138.59863280000002], [-31.952240000000003, 115.8613968]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_5045b6969442493abcc8e49e0c9313a7);
        
    
            poly_line_offset_91c941ee9b914267af8bae6218ea2194.bindTooltip(
                `<div>
                     Departing: Adelaide Arriving: Perth Aircraft Model: A330-203 Engine Model: CF6-80E142 Price: $200.00 Space Class: D
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_c9cab4e0add34b0eb87fafa4b3551b0f = L.polyline(
                [[-34.928661299999995, 138.59863280000002], [-12.4611301, 130.8418427]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_5045b6969442493abcc8e49e0c9313a7);
        
    
            poly_line_offset_c9cab4e0add34b0eb87fafa4b3551b0f.bindTooltip(
                `<div>
                     Departing: Adelaide Arriving: Darwin Aircraft Model: A330-203 Engine Model: CF6-80E142 Price: $230.00 Space Class: D
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_7b6bc1eb4312481084f8572331e94154 = L.polyline(
                [[-12.4611301, 130.8418427], [-34.928661299999995, 138.59863280000002]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_5045b6969442493abcc8e49e0c9313a7);
        
    
            poly_line_offset_7b6bc1eb4312481084f8572331e94154.bindTooltip(
                `<div>
                     Departing: Darwin Arriving: Adelaide Aircraft Model: A330-203 Engine Model: CF6-80E142 Price: $230.00 Space Class: D
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_5af510d2256146d28f415402176eb09e = L.polyline(
                [[-31.952240000000003, 115.8613968], [-34.928661299999995, 138.59863280000002]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_5045b6969442493abcc8e49e0c9313a7);
        
    
            poly_line_offset_5af510d2256146d28f415402176eb09e.bindTooltip(
                `<div>
                     Departing: Perth Arriving: Adelaide Aircraft Model: A330-203 Engine Model: CF6-80E142 Price: $220.00 Space Class: D
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_9deed764021a4cfd9245b38470c21cee = L.polyline(
                [[-27.4679394, 153.02809140000002], [-33.8651, 151.2099]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_5045b6969442493abcc8e49e0c9313a7);
        
    
            poly_line_offset_9deed764021a4cfd9245b38470c21cee.bindTooltip(
                `<div>
                     Departing: Brisbane Arriving: Sydney Aircraft Model: A330-203 Engine Model: CF6-80E142 Price: $170.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_eaeb0986c5ac40daa151c35618aa6afd = L.polyline(
                [[-27.4679394, 153.02809140000002], [-16.923040399999998, 145.7662506]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_5045b6969442493abcc8e49e0c9313a7);
        
    
            poly_line_offset_eaeb0986c5ac40daa151c35618aa6afd.bindTooltip(
                `<div>
                     Departing: Brisbane Arriving: Cairns Aircraft Model: A330-203 Engine Model: CF6-80E142 Price: $230.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_93474afec4fe48acab700661ae09148e = L.polyline(
                [[-27.4679394, 153.02809140000002], [-12.4611301, 130.8418427]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_5045b6969442493abcc8e49e0c9313a7);
        
    
            poly_line_offset_93474afec4fe48acab700661ae09148e.bindTooltip(
                `<div>
                     Departing: Brisbane Arriving: Darwin Aircraft Model: A330-203 Engine Model: CF6-80E142 Price: $240.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_6dee89fc1ff64c659fc916baf16466ae = L.polyline(
                [[-16.923040399999998, 145.7662506], [-27.4679394, 153.02809140000002]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_5045b6969442493abcc8e49e0c9313a7);
        
    
            poly_line_offset_6dee89fc1ff64c659fc916baf16466ae.bindTooltip(
                `<div>
                     Departing: Cairns Arriving: Brisbane Aircraft Model: A330-203 Engine Model: CF6-80E142 Price: $230.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_de6270692fa24b3495736c850ea6c1c1 = L.polyline(
                [[-12.4611301, 130.8418427], [-27.4679394, 153.02809140000002]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_5045b6969442493abcc8e49e0c9313a7);
        
    
            poly_line_offset_de6270692fa24b3495736c850ea6c1c1.bindTooltip(
                `<div>
                     Departing: Darwin Arriving: Brisbane Aircraft Model: A330-203 Engine Model: CF6-80E142 Price: $240.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_632d14503c934ad2975ab2b3c71dbdaf = L.polyline(
                [[-33.8678513, 151.2073212], [-37.813999200000005, 144.9633179]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_5045b6969442493abcc8e49e0c9313a7);
        
    
            poly_line_offset_632d14503c934ad2975ab2b3c71dbdaf.bindTooltip(
                `<div>
                     Departing: Sydney Arriving: Melbourne Aircraft Model: A330-203 Engine Model: CF6-80E142 Price: $180.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_825bf0decc3e485596f5ad8c8ea27166 = L.polyline(
                [[-34.928661299999995, 138.59863280000002], [-31.952240000000003, 115.8613968]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_5045b6969442493abcc8e49e0c9313a7);
        
    
            poly_line_offset_825bf0decc3e485596f5ad8c8ea27166.bindTooltip(
                `<div>
                     Departing: Adelaide Arriving: Perth Aircraft Model: A330-203 Engine Model: CF6-80E142 Price: $200.00 Space Class: D
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_09e71d79669d43598cb2dd0282751d60 = L.polyline(
                [[-34.928661299999995, 138.59863280000002], [-12.4611301, 130.8418427]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_5045b6969442493abcc8e49e0c9313a7);
        
    
            poly_line_offset_09e71d79669d43598cb2dd0282751d60.bindTooltip(
                `<div>
                     Departing: Adelaide Arriving: Darwin Aircraft Model: A330-203 Engine Model: CF6-80E142 Price: $230.00 Space Class: D
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_bae5e9eb16f34255a1588d20fbed591a = L.polyline(
                [[-12.4611301, 130.8418427], [-34.928661299999995, 138.59863280000002]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_5045b6969442493abcc8e49e0c9313a7);
        
    
            poly_line_offset_bae5e9eb16f34255a1588d20fbed591a.bindTooltip(
                `<div>
                     Departing: Darwin Arriving: Adelaide Aircraft Model: A330-203 Engine Model: CF6-80E142 Price: $230.00 Space Class: D
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_529c31f6fcbe498396be6d9154775f10 = L.polyline(
                [[-31.952240000000003, 115.8613968], [-34.928661299999995, 138.59863280000002]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_5045b6969442493abcc8e49e0c9313a7);
        
    
            poly_line_offset_529c31f6fcbe498396be6d9154775f10.bindTooltip(
                `<div>
                     Departing: Perth Arriving: Adelaide Aircraft Model: A330-203 Engine Model: CF6-80E142 Price: $220.00 Space Class: D
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_3d449f55e15b4a718ee6f6432ff2c128 = L.polyline(
                [[-27.4679394, 153.02809140000002], [-33.8651, 151.2099]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_5045b6969442493abcc8e49e0c9313a7);
        
    
            poly_line_offset_3d449f55e15b4a718ee6f6432ff2c128.bindTooltip(
                `<div>
                     Departing: Brisbane Arriving: Sydney Aircraft Model: A330-203 Engine Model: CF6-80E142 Price: $170.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_3044091adfaa4e19b4901d757f884e8b = L.polyline(
                [[-27.4679394, 153.02809140000002], [-16.923040399999998, 145.7662506]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_5045b6969442493abcc8e49e0c9313a7);
        
    
            poly_line_offset_3044091adfaa4e19b4901d757f884e8b.bindTooltip(
                `<div>
                     Departing: Brisbane Arriving: Cairns Aircraft Model: A330-203 Engine Model: CF6-80E142 Price: $230.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_5f6fb122768f4eadb39c2c0532a169df = L.polyline(
                [[-27.4679394, 153.02809140000002], [-12.4611301, 130.8418427]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_5045b6969442493abcc8e49e0c9313a7);
        
    
            poly_line_offset_5f6fb122768f4eadb39c2c0532a169df.bindTooltip(
                `<div>
                     Departing: Brisbane Arriving: Darwin Aircraft Model: A330-203 Engine Model: CF6-80E142 Price: $240.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_409c5e4fa4c143a0b1c8c258ddbf4ecf = L.polyline(
                [[-16.923040399999998, 145.7662506], [-27.4679394, 153.02809140000002]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_5045b6969442493abcc8e49e0c9313a7);
        
    
            poly_line_offset_409c5e4fa4c143a0b1c8c258ddbf4ecf.bindTooltip(
                `<div>
                     Departing: Cairns Arriving: Brisbane Aircraft Model: A330-203 Engine Model: CF6-80E142 Price: $230.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_097a2d3d5a4e4e34961dc032541b9a3a = L.polyline(
                [[-12.4611301, 130.8418427], [-27.4679394, 153.02809140000002]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_5045b6969442493abcc8e49e0c9313a7);
        
    
            poly_line_offset_097a2d3d5a4e4e34961dc032541b9a3a.bindTooltip(
                `<div>
                     Departing: Darwin Arriving: Brisbane Aircraft Model: A330-203 Engine Model: CF6-80E142 Price: $240.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var feature_group_b9d313c2d58e4e0995c249fe327ce762 = L.featureGroup(
                {}
            ).addTo(map_2b09cbfb923147c0b2d49acb4399a6e6);
        
    
            var poly_line_offset_fcb63afff6fd4bd392a02ef9afa50537 = L.polyline(
                [[-37.813999200000005, 144.9633179], [-33.8678513, 151.2073212]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_b9d313c2d58e4e0995c249fe327ce762);
        
    
            poly_line_offset_fcb63afff6fd4bd392a02ef9afa50537.bindTooltip(
                `<div>
                     Departing: Melbourne Arriving: Sydney Aircraft Model: A330-243 Engine Model: 772B-60 Price: $180.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_ad804efdeb6c4c36b23783462a36c1a4 = L.polyline(
                [[-37.813999200000005, 144.9633179], [-33.8678513, 151.2073212]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_b9d313c2d58e4e0995c249fe327ce762);
        
    
            poly_line_offset_ad804efdeb6c4c36b23783462a36c1a4.bindTooltip(
                `<div>
                     Departing: Melbourne Arriving: Sydney Aircraft Model: A330-243 Engine Model: 772B-60 Price: $180.00 Space Class: C
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_1632c2de6a45429790a9cab9284b0e8b = L.polyline(
                [[-37.813999200000005, 144.9633179], [-33.8678513, 151.2073212]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_b9d313c2d58e4e0995c249fe327ce762);
        
    
            poly_line_offset_1632c2de6a45429790a9cab9284b0e8b.bindTooltip(
                `<div>
                     Departing: Melbourne Arriving: Sydney Aircraft Model: A330-243 Engine Model: 772B-60 Price: $180.00 Space Class: C
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_09dac87983004d39b62c90ce0f126d4e = L.polyline(
                [[-37.813999200000005, 144.9633179], [-33.8678513, 151.2073212]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_b9d313c2d58e4e0995c249fe327ce762);
        
    
            poly_line_offset_09dac87983004d39b62c90ce0f126d4e.bindTooltip(
                `<div>
                     Departing: Melbourne Arriving: Sydney Aircraft Model: A330-243 Engine Model: 772B-60 Price: $180.00 Space Class: C
                 </div>`,
                {"sticky": true}
            );
        
    
            var feature_group_e2dc8c44c13342f99d22e0ae12d27fc0 = L.featureGroup(
                {}
            ).addTo(map_2b09cbfb923147c0b2d49acb4399a6e6);
        
    
            var poly_line_offset_aa4cf2c04e7145c1b8efc97202b81472 = L.polyline(
                [[-37.813999200000005, 144.9633179], [-36.7581787, 144.2802429]],
                {"bubblingMouseEvents": true, "color": "#FFC000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#FFC000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_e2dc8c44c13342f99d22e0ae12d27fc0);
        
    
            poly_line_offset_aa4cf2c04e7145c1b8efc97202b81472.bindTooltip(
                `<div>
                     Departing: Melbourne Arriving: Bendigo Aircraft Model: B717-200 Engine Model: UNKNOWN Price: $70.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_ffb475a3c3bc4793bcd1eca40e13a543 = L.polyline(
                [[-36.7581787, 144.2802429], [-37.813999200000005, 144.9633179]],
                {"bubblingMouseEvents": true, "color": "#FFC000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#FFC000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_e2dc8c44c13342f99d22e0ae12d27fc0);
        
    
            poly_line_offset_ffb475a3c3bc4793bcd1eca40e13a543.bindTooltip(
                `<div>
                     Departing: Bendigo Arriving: Melbourne Aircraft Model: B717-200 Engine Model: UNKNOWN Price: $70.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_4c197b3934ef484f84597e0bd021b2f9 = L.polyline(
                [[-34.928661299999995, 138.59863280000002], [-32.4959717, 137.7728119]],
                {"bubblingMouseEvents": true, "color": "#70AD47", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#70AD47", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_e2dc8c44c13342f99d22e0ae12d27fc0);
        
    
            poly_line_offset_4c197b3934ef484f84597e0bd021b2f9.bindTooltip(
                `<div>
                     Departing: Adelaide Arriving: Pt Augusta Aircraft Model: B717-200 Engine Model: UNKNOWN Price: $50.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_9892922dc50342fc8e8de3ff174bf071 = L.polyline(
                [[-32.4959717, 137.7728119], [-34.928661299999995, 138.59863280000002]],
                {"bubblingMouseEvents": true, "color": "#70AD47", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#70AD47", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_e2dc8c44c13342f99d22e0ae12d27fc0);
        
    
            poly_line_offset_9892922dc50342fc8e8de3ff174bf071.bindTooltip(
                `<div>
                     Departing: Pt Augusta Arriving: Adelaide Aircraft Model: B717-200 Engine Model: UNKNOWN Price: $50.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_df013d197e934dcb84db8624fc24fbeb = L.polyline(
                [[-37.813999200000005, 144.9633179], [-36.7581787, 144.2802429]],
                {"bubblingMouseEvents": true, "color": "#FFC000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#FFC000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_e2dc8c44c13342f99d22e0ae12d27fc0);
        
    
            poly_line_offset_df013d197e934dcb84db8624fc24fbeb.bindTooltip(
                `<div>
                     Departing: Melbourne Arriving: Bendigo Aircraft Model: B717-200 Engine Model: UNKNOWN Price: $70.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_2de4ca6844b245f8a23eaa9307894074 = L.polyline(
                [[-36.7581787, 144.2802429], [-37.813999200000005, 144.9633179]],
                {"bubblingMouseEvents": true, "color": "#FFC000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#FFC000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_e2dc8c44c13342f99d22e0ae12d27fc0);
        
    
            poly_line_offset_2de4ca6844b245f8a23eaa9307894074.bindTooltip(
                `<div>
                     Departing: Bendigo Arriving: Melbourne Aircraft Model: B717-200 Engine Model: UNKNOWN Price: $70.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_3f700c8b0b89407490a3e3a32cf35d07 = L.polyline(
                [[-34.928661299999995, 138.59863280000002], [-32.4959717, 137.7728119]],
                {"bubblingMouseEvents": true, "color": "#70AD47", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#70AD47", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_e2dc8c44c13342f99d22e0ae12d27fc0);
        
    
            poly_line_offset_3f700c8b0b89407490a3e3a32cf35d07.bindTooltip(
                `<div>
                     Departing: Adelaide Arriving: Pt Augusta Aircraft Model: B717-200 Engine Model: UNKNOWN Price: $50.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_9d5bb89c765d46a79c9f168bb44a9225 = L.polyline(
                [[-32.4959717, 137.7728119], [-34.928661299999995, 138.59863280000002]],
                {"bubblingMouseEvents": true, "color": "#70AD47", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#70AD47", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_e2dc8c44c13342f99d22e0ae12d27fc0);
        
    
            poly_line_offset_9d5bb89c765d46a79c9f168bb44a9225.bindTooltip(
                `<div>
                     Departing: Pt Augusta Arriving: Adelaide Aircraft Model: B717-200 Engine Model: UNKNOWN Price: $50.00 Space Class: C
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_7b7cc2d34ccb468cb6779be10cbe61a8 = L.polyline(
                [[-37.813999200000005, 144.9633179], [-36.7581787, 144.2802429]],
                {"bubblingMouseEvents": true, "color": "#FFC000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#FFC000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_e2dc8c44c13342f99d22e0ae12d27fc0);
        
    
            poly_line_offset_7b7cc2d34ccb468cb6779be10cbe61a8.bindTooltip(
                `<div>
                     Departing: Melbourne Arriving: Bendigo Aircraft Model: B717-200 Engine Model: UNKNOWN Price: $70.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_2da3dc19e29e4c6793559da49a3975ab = L.polyline(
                [[-36.7581787, 144.2802429], [-37.813999200000005, 144.9633179]],
                {"bubblingMouseEvents": true, "color": "#FFC000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#FFC000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_e2dc8c44c13342f99d22e0ae12d27fc0);
        
    
            poly_line_offset_2da3dc19e29e4c6793559da49a3975ab.bindTooltip(
                `<div>
                     Departing: Bendigo Arriving: Melbourne Aircraft Model: B717-200 Engine Model: UNKNOWN Price: $70.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_de1b7c80bd6141a3ad360484f58c8b39 = L.polyline(
                [[-34.928661299999995, 138.59863280000002], [-32.4959717, 137.7728119]],
                {"bubblingMouseEvents": true, "color": "#70AD47", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#70AD47", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_e2dc8c44c13342f99d22e0ae12d27fc0);
        
    
            poly_line_offset_de1b7c80bd6141a3ad360484f58c8b39.bindTooltip(
                `<div>
                     Departing: Adelaide Arriving: Pt Augusta Aircraft Model: B717-200 Engine Model: UNKNOWN Price: $50.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_8c6bad3a6195408ebc14885981691bc2 = L.polyline(
                [[-32.4959717, 137.7728119], [-34.928661299999995, 138.59863280000002]],
                {"bubblingMouseEvents": true, "color": "#70AD47", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#70AD47", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_e2dc8c44c13342f99d22e0ae12d27fc0);
        
    
            poly_line_offset_8c6bad3a6195408ebc14885981691bc2.bindTooltip(
                `<div>
                     Departing: Pt Augusta Arriving: Adelaide Aircraft Model: B717-200 Engine Model: UNKNOWN Price: $50.00 Space Class: C
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_599be3fb0a1245098cdcdb993397fd20 = L.polyline(
                [[-37.813999200000005, 144.9633179], [-36.7581787, 144.2802429]],
                {"bubblingMouseEvents": true, "color": "#FFC000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#FFC000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_e2dc8c44c13342f99d22e0ae12d27fc0);
        
    
            poly_line_offset_599be3fb0a1245098cdcdb993397fd20.bindTooltip(
                `<div>
                     Departing: Melbourne Arriving: Bendigo Aircraft Model: B717-200 Engine Model: UNKNOWN Price: $70.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_bcd74e8e311249c494e72d507f921710 = L.polyline(
                [[-36.7581787, 144.2802429], [-37.813999200000005, 144.9633179]],
                {"bubblingMouseEvents": true, "color": "#FFC000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#FFC000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_e2dc8c44c13342f99d22e0ae12d27fc0);
        
    
            poly_line_offset_bcd74e8e311249c494e72d507f921710.bindTooltip(
                `<div>
                     Departing: Bendigo Arriving: Melbourne Aircraft Model: B717-200 Engine Model: UNKNOWN Price: $70.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_c546de07d5be42339430e828fe29bbfc = L.polyline(
                [[-34.928661299999995, 138.59863280000002], [-32.4959717, 137.7728119]],
                {"bubblingMouseEvents": true, "color": "#70AD47", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#70AD47", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_e2dc8c44c13342f99d22e0ae12d27fc0);
        
    
            poly_line_offset_c546de07d5be42339430e828fe29bbfc.bindTooltip(
                `<div>
                     Departing: Adelaide Arriving: Pt Augusta Aircraft Model: B717-200 Engine Model: UNKNOWN Price: $50.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_ddb6d5e8b3bc4e40b2c036f8c6086db4 = L.polyline(
                [[-32.4959717, 137.7728119], [-34.928661299999995, 138.59863280000002]],
                {"bubblingMouseEvents": true, "color": "#70AD47", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#70AD47", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_e2dc8c44c13342f99d22e0ae12d27fc0);
        
    
            poly_line_offset_ddb6d5e8b3bc4e40b2c036f8c6086db4.bindTooltip(
                `<div>
                     Departing: Pt Augusta Arriving: Adelaide Aircraft Model: B717-200 Engine Model: UNKNOWN Price: $50.00 Space Class: C
                 </div>`,
                {"sticky": true}
            );
        
    
            var feature_group_9f1ac2c37e62405ebcfd2d457851456f = L.featureGroup(
                {}
            ).addTo(map_2b09cbfb923147c0b2d49acb4399a6e6);
        
    
            var poly_line_offset_ee213e3bd1d74608abcf0cb64bdd7241 = L.polyline(
                [[-33.8678513, 151.2073212], [-35.283458700000004, 149.128067]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_9f1ac2c37e62405ebcfd2d457851456f);
        
    
            poly_line_offset_ee213e3bd1d74608abcf0cb64bdd7241.bindTooltip(
                `<div>
                     Departing: Sydney Arriving: Canberra Aircraft Model: B737-3B7 Engine Model: CFM56-3B1 Price: $120.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_8c89394fa4eb458cb110da48842f1852 = L.polyline(
                [[-37.813999200000005, 144.9633179], [-34.928661299999995, 138.59863280000002]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_9f1ac2c37e62405ebcfd2d457851456f);
        
    
            poly_line_offset_8c89394fa4eb458cb110da48842f1852.bindTooltip(
                `<div>
                     Departing: Melbourne Arriving: Adelaide Aircraft Model: B737-3B7 Engine Model: CFM56-3B1 Price: $175.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_db48b30c82c7435c99749e007066e5ea = L.polyline(
                [[-37.813999200000005, 144.9633179], [-41.438758899999996, 147.13467409999998]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_9f1ac2c37e62405ebcfd2d457851456f);
        
    
            poly_line_offset_db48b30c82c7435c99749e007066e5ea.bindTooltip(
                `<div>
                     Departing: Melbourne Arriving: Launceston Aircraft Model: B737-3B7 Engine Model: CFM56-3B1 Price: $100.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_2afdd3c141c546e486786ea2471c6b58 = L.polyline(
                [[-34.928661299999995, 138.59863280000002], [-37.813999200000005, 144.9633179]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_9f1ac2c37e62405ebcfd2d457851456f);
        
    
            poly_line_offset_2afdd3c141c546e486786ea2471c6b58.bindTooltip(
                `<div>
                     Departing: Adelaide Arriving: Melbourne Aircraft Model: B737-3B7 Engine Model: CFM56-3B1 Price: $175.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_2ac46fb677d84f869c999fe1e3b3a41d = L.polyline(
                [[-42.8793602, 147.3294067], [-37.813999200000005, 144.9633179]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_9f1ac2c37e62405ebcfd2d457851456f);
        
    
            poly_line_offset_2ac46fb677d84f869c999fe1e3b3a41d.bindTooltip(
                `<div>
                     Departing: Hobart Arriving: Melbourne Aircraft Model: B737-3B7 Engine Model: CFM56-3B1 Price: $130.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_6e3d8ce0c3174e71870ab9c89acf613c = L.polyline(
                [[-27.4679394, 153.02809140000002], [-20.7255748, 139.4927085]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_9f1ac2c37e62405ebcfd2d457851456f);
        
    
            poly_line_offset_6e3d8ce0c3174e71870ab9c89acf613c.bindTooltip(
                `<div>
                     Departing: Brisbane Arriving: Mt Isa Aircraft Model: B737-3B7 Engine Model: CFM56-3B1 Price: $170.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_b63f42e99d3542d9b557221566bb06f7 = L.polyline(
                [[-27.4679394, 153.02809140000002], [-23.380319600000004, 150.50595090000002]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_9f1ac2c37e62405ebcfd2d457851456f);
        
    
            poly_line_offset_b63f42e99d3542d9b557221566bb06f7.bindTooltip(
                `<div>
                     Departing: Brisbane Arriving: Rockhampton Aircraft Model: B737-3B7 Engine Model: CFM56-3B1 Price: $180.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_1cb722778b644516975c3a339f088ac7 = L.polyline(
                [[-20.7255748, 139.4927085], [-12.4611301, 130.8418427]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_9f1ac2c37e62405ebcfd2d457851456f);
        
    
            poly_line_offset_1cb722778b644516975c3a339f088ac7.bindTooltip(
                `<div>
                     Departing: Mt Isa Arriving: Darwin Aircraft Model: B737-3B7 Engine Model: CFM56-3B1 Price: $120.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_b733c673a1f747ec90512151cfb4767e = L.polyline(
                [[-12.4611301, 130.8418427], [-20.7255748, 139.4927085]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_9f1ac2c37e62405ebcfd2d457851456f);
        
    
            poly_line_offset_b733c673a1f747ec90512151cfb4767e.bindTooltip(
                `<div>
                     Departing: Darwin Arriving: Mt Isa Aircraft Model: B737-3B7 Engine Model: CFM56-3B1 Price: $120.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_23e24f0c5eb24d97b77e01e4eb826791 = L.polyline(
                [[-33.8678513, 151.2073212], [-35.283458700000004, 149.128067]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_9f1ac2c37e62405ebcfd2d457851456f);
        
    
            poly_line_offset_23e24f0c5eb24d97b77e01e4eb826791.bindTooltip(
                `<div>
                     Departing: Sydney Arriving: Canberra Aircraft Model: B737-3B7 Engine Model: CFM56-3B1 Price: $120.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_22b8dbeef50c4b1fb8ad32da6291f89b = L.polyline(
                [[-37.813999200000005, 144.9633179], [-34.928661299999995, 138.59863280000002]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_9f1ac2c37e62405ebcfd2d457851456f);
        
    
            poly_line_offset_22b8dbeef50c4b1fb8ad32da6291f89b.bindTooltip(
                `<div>
                     Departing: Melbourne Arriving: Adelaide Aircraft Model: B737-3B7 Engine Model: CFM56-3B1 Price: $175.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_0412c7705b624c84a4272b71196c22be = L.polyline(
                [[-37.813999200000005, 144.9633179], [-41.438758899999996, 147.13467409999998]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_9f1ac2c37e62405ebcfd2d457851456f);
        
    
            poly_line_offset_0412c7705b624c84a4272b71196c22be.bindTooltip(
                `<div>
                     Departing: Melbourne Arriving: Launceston Aircraft Model: B737-3B7 Engine Model: CFM56-3B1 Price: $100.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_5c7355e2e0004c46958ba0b9b4ffaf11 = L.polyline(
                [[-34.928661299999995, 138.59863280000002], [-37.813999200000005, 144.9633179]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_9f1ac2c37e62405ebcfd2d457851456f);
        
    
            poly_line_offset_5c7355e2e0004c46958ba0b9b4ffaf11.bindTooltip(
                `<div>
                     Departing: Adelaide Arriving: Melbourne Aircraft Model: B737-3B7 Engine Model: CFM56-3B1 Price: $175.00 Space Class: C
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_90f0aa24b7dd457e82b4263c3383d9ca = L.polyline(
                [[-42.8793602, 147.3294067], [-37.813999200000005, 144.9633179]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_9f1ac2c37e62405ebcfd2d457851456f);
        
    
            poly_line_offset_90f0aa24b7dd457e82b4263c3383d9ca.bindTooltip(
                `<div>
                     Departing: Hobart Arriving: Melbourne Aircraft Model: B737-3B7 Engine Model: CFM56-3B1 Price: $130.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_c91775210bb84c42bd83b8821b2699ab = L.polyline(
                [[-27.4679394, 153.02809140000002], [-20.7255748, 139.4927085]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_9f1ac2c37e62405ebcfd2d457851456f);
        
    
            poly_line_offset_c91775210bb84c42bd83b8821b2699ab.bindTooltip(
                `<div>
                     Departing: Brisbane Arriving: Mt Isa Aircraft Model: B737-3B7 Engine Model: CFM56-3B1 Price: $170.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_5333bf85a80d42c79880676a0e7d0e2f = L.polyline(
                [[-27.4679394, 153.02809140000002], [-23.380319600000004, 150.50595090000002]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_9f1ac2c37e62405ebcfd2d457851456f);
        
    
            poly_line_offset_5333bf85a80d42c79880676a0e7d0e2f.bindTooltip(
                `<div>
                     Departing: Brisbane Arriving: Rockhampton Aircraft Model: B737-3B7 Engine Model: CFM56-3B1 Price: $180.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_943e17c6b1104250af4a679d0ee5b48b = L.polyline(
                [[-20.7255748, 139.4927085], [-12.4611301, 130.8418427]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_9f1ac2c37e62405ebcfd2d457851456f);
        
    
            poly_line_offset_943e17c6b1104250af4a679d0ee5b48b.bindTooltip(
                `<div>
                     Departing: Mt Isa Arriving: Darwin Aircraft Model: B737-3B7 Engine Model: CFM56-3B1 Price: $120.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_635628037b3e4511a803620b0b381330 = L.polyline(
                [[-12.4611301, 130.8418427], [-20.7255748, 139.4927085]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_9f1ac2c37e62405ebcfd2d457851456f);
        
    
            poly_line_offset_635628037b3e4511a803620b0b381330.bindTooltip(
                `<div>
                     Departing: Darwin Arriving: Mt Isa Aircraft Model: B737-3B7 Engine Model: CFM56-3B1 Price: $120.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_db02c1b35da6412eb282b3c74af4de6c = L.polyline(
                [[-33.8678513, 151.2073212], [-35.283458700000004, 149.128067]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_9f1ac2c37e62405ebcfd2d457851456f);
        
    
            poly_line_offset_db02c1b35da6412eb282b3c74af4de6c.bindTooltip(
                `<div>
                     Departing: Sydney Arriving: Canberra Aircraft Model: B737-3B7 Engine Model: CFM56-3B1 Price: $120.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_5cd38f3fddbb406db3d16d5e4619e30e = L.polyline(
                [[-37.813999200000005, 144.9633179], [-34.928661299999995, 138.59863280000002]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_9f1ac2c37e62405ebcfd2d457851456f);
        
    
            poly_line_offset_5cd38f3fddbb406db3d16d5e4619e30e.bindTooltip(
                `<div>
                     Departing: Melbourne Arriving: Adelaide Aircraft Model: B737-3B7 Engine Model: CFM56-3B1 Price: $175.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_993ec9db22ca4bf0aac56823441d8729 = L.polyline(
                [[-37.813999200000005, 144.9633179], [-41.438758899999996, 147.13467409999998]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_9f1ac2c37e62405ebcfd2d457851456f);
        
    
            poly_line_offset_993ec9db22ca4bf0aac56823441d8729.bindTooltip(
                `<div>
                     Departing: Melbourne Arriving: Launceston Aircraft Model: B737-3B7 Engine Model: CFM56-3B1 Price: $100.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_a4b85cb464194149863686fb64c1a162 = L.polyline(
                [[-34.928661299999995, 138.59863280000002], [-37.813999200000005, 144.9633179]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_9f1ac2c37e62405ebcfd2d457851456f);
        
    
            poly_line_offset_a4b85cb464194149863686fb64c1a162.bindTooltip(
                `<div>
                     Departing: Adelaide Arriving: Melbourne Aircraft Model: B737-3B7 Engine Model: CFM56-3B1 Price: $175.00 Space Class: C
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_51fa14aa77b34a54bf131eb39a472da5 = L.polyline(
                [[-42.8793602, 147.3294067], [-37.813999200000005, 144.9633179]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_9f1ac2c37e62405ebcfd2d457851456f);
        
    
            poly_line_offset_51fa14aa77b34a54bf131eb39a472da5.bindTooltip(
                `<div>
                     Departing: Hobart Arriving: Melbourne Aircraft Model: B737-3B7 Engine Model: CFM56-3B1 Price: $130.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_c5663b8da5f74b7ab7f53a4b05f6f622 = L.polyline(
                [[-27.4679394, 153.02809140000002], [-20.7255748, 139.4927085]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_9f1ac2c37e62405ebcfd2d457851456f);
        
    
            poly_line_offset_c5663b8da5f74b7ab7f53a4b05f6f622.bindTooltip(
                `<div>
                     Departing: Brisbane Arriving: Mt Isa Aircraft Model: B737-3B7 Engine Model: CFM56-3B1 Price: $170.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_296109a100a741899c2cf5ca0e6ca104 = L.polyline(
                [[-27.4679394, 153.02809140000002], [-23.380319600000004, 150.50595090000002]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_9f1ac2c37e62405ebcfd2d457851456f);
        
    
            poly_line_offset_296109a100a741899c2cf5ca0e6ca104.bindTooltip(
                `<div>
                     Departing: Brisbane Arriving: Rockhampton Aircraft Model: B737-3B7 Engine Model: CFM56-3B1 Price: $180.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_7c28fc37c2ce4a08a4e542e08376fb2b = L.polyline(
                [[-20.7255748, 139.4927085], [-12.4611301, 130.8418427]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_9f1ac2c37e62405ebcfd2d457851456f);
        
    
            poly_line_offset_7c28fc37c2ce4a08a4e542e08376fb2b.bindTooltip(
                `<div>
                     Departing: Mt Isa Arriving: Darwin Aircraft Model: B737-3B7 Engine Model: CFM56-3B1 Price: $120.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_c896a721b02648e4a5fd95129bbd35ac = L.polyline(
                [[-12.4611301, 130.8418427], [-20.7255748, 139.4927085]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_9f1ac2c37e62405ebcfd2d457851456f);
        
    
            poly_line_offset_c896a721b02648e4a5fd95129bbd35ac.bindTooltip(
                `<div>
                     Departing: Darwin Arriving: Mt Isa Aircraft Model: B737-3B7 Engine Model: CFM56-3B1 Price: $120.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_be670216056c41df8d85107fafd5c88a = L.polyline(
                [[-33.8678513, 151.2073212], [-35.283458700000004, 149.128067]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_9f1ac2c37e62405ebcfd2d457851456f);
        
    
            poly_line_offset_be670216056c41df8d85107fafd5c88a.bindTooltip(
                `<div>
                     Departing: Sydney Arriving: Canberra Aircraft Model: B737-3B7 Engine Model: CFM56-3B1 Price: $120.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_f47eb6e5c6d74c8b9b5402ddc95b4803 = L.polyline(
                [[-37.813999200000005, 144.9633179], [-34.928661299999995, 138.59863280000002]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_9f1ac2c37e62405ebcfd2d457851456f);
        
    
            poly_line_offset_f47eb6e5c6d74c8b9b5402ddc95b4803.bindTooltip(
                `<div>
                     Departing: Melbourne Arriving: Adelaide Aircraft Model: B737-3B7 Engine Model: CFM56-3B1 Price: $175.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_4ece0b5a806b4d22b194bad2c64218d8 = L.polyline(
                [[-37.813999200000005, 144.9633179], [-41.438758899999996, 147.13467409999998]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_9f1ac2c37e62405ebcfd2d457851456f);
        
    
            poly_line_offset_4ece0b5a806b4d22b194bad2c64218d8.bindTooltip(
                `<div>
                     Departing: Melbourne Arriving: Launceston Aircraft Model: B737-3B7 Engine Model: CFM56-3B1 Price: $100.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_dca7181aa3b746edae49073cfd8c0da3 = L.polyline(
                [[-34.928661299999995, 138.59863280000002], [-37.813999200000005, 144.9633179]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_9f1ac2c37e62405ebcfd2d457851456f);
        
    
            poly_line_offset_dca7181aa3b746edae49073cfd8c0da3.bindTooltip(
                `<div>
                     Departing: Adelaide Arriving: Melbourne Aircraft Model: B737-3B7 Engine Model: CFM56-3B1 Price: $175.00 Space Class: C
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_f6697e5498174fdca3da1ba6886ef0bb = L.polyline(
                [[-42.8793602, 147.3294067], [-37.813999200000005, 144.9633179]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_9f1ac2c37e62405ebcfd2d457851456f);
        
    
            poly_line_offset_f6697e5498174fdca3da1ba6886ef0bb.bindTooltip(
                `<div>
                     Departing: Hobart Arriving: Melbourne Aircraft Model: B737-3B7 Engine Model: CFM56-3B1 Price: $130.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_468b41eeacb54ea8a7241f3e0a47295b = L.polyline(
                [[-27.4679394, 153.02809140000002], [-20.7255748, 139.4927085]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_9f1ac2c37e62405ebcfd2d457851456f);
        
    
            poly_line_offset_468b41eeacb54ea8a7241f3e0a47295b.bindTooltip(
                `<div>
                     Departing: Brisbane Arriving: Mt Isa Aircraft Model: B737-3B7 Engine Model: CFM56-3B1 Price: $170.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_9ff70f176dd844d3b509fded997d0acf = L.polyline(
                [[-27.4679394, 153.02809140000002], [-23.380319600000004, 150.50595090000002]],
                {"bubblingMouseEvents": true, "color": "#C00000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#C00000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_9f1ac2c37e62405ebcfd2d457851456f);
        
    
            poly_line_offset_9ff70f176dd844d3b509fded997d0acf.bindTooltip(
                `<div>
                     Departing: Brisbane Arriving: Rockhampton Aircraft Model: B737-3B7 Engine Model: CFM56-3B1 Price: $180.00 Space Class: A
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_7bc68a03ac8b4621a71b0638bbe45453 = L.polyline(
                [[-20.7255748, 139.4927085], [-12.4611301, 130.8418427]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_9f1ac2c37e62405ebcfd2d457851456f);
        
    
            poly_line_offset_7bc68a03ac8b4621a71b0638bbe45453.bindTooltip(
                `<div>
                     Departing: Mt Isa Arriving: Darwin Aircraft Model: B737-3B7 Engine Model: CFM56-3B1 Price: $120.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_b41a0bf928ff4f0fae6f6042b020d027 = L.polyline(
                [[-12.4611301, 130.8418427], [-20.7255748, 139.4927085]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_9f1ac2c37e62405ebcfd2d457851456f);
        
    
            poly_line_offset_b41a0bf928ff4f0fae6f6042b020d027.bindTooltip(
                `<div>
                     Departing: Darwin Arriving: Mt Isa Aircraft Model: B737-3B7 Engine Model: CFM56-3B1 Price: $120.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var feature_group_e5b1f4a74c9049c4be01f104c9fbcdc2 = L.featureGroup(
                {}
            ).addTo(map_2b09cbfb923147c0b2d49acb4399a6e6);
        
    
            var poly_line_offset_ba3fe44eab624b77a732682190b59515 = L.polyline(
                [[-35.283458700000004, 149.128067], [-33.8678513, 151.2073212]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_e5b1f4a74c9049c4be01f104c9fbcdc2);
        
    
            poly_line_offset_ba3fe44eab624b77a732682190b59515.bindTooltip(
                `<div>
                     Departing: Canberra Arriving: Sydney Aircraft Model: B737-476 Engine Model: CFM-56-3 Price: $120.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_766e1f7ed51d43a393cbf067b878316d = L.polyline(
                [[-12.4611301, 130.8418427], [-23.6974792, 133.8836212]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_e5b1f4a74c9049c4be01f104c9fbcdc2);
        
    
            poly_line_offset_766e1f7ed51d43a393cbf067b878316d.bindTooltip(
                `<div>
                     Departing: Darwin Arriving: Alice Springs Aircraft Model: B737-476 Engine Model: CFM-56-3 Price: $120.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_1c59acb08ebc4c5da050e70b4bc30cf2 = L.polyline(
                [[-23.6974792, 133.8836212], [-12.4611301, 130.8418427]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_e5b1f4a74c9049c4be01f104c9fbcdc2);
        
    
            poly_line_offset_1c59acb08ebc4c5da050e70b4bc30cf2.bindTooltip(
                `<div>
                     Departing: Alice Springs Arriving: Darwin Aircraft Model: B737-476 Engine Model: CFM-56-3 Price: $120.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_1efbdb67469b47b28c46f4ff92f8ca7f = L.polyline(
                [[-17.955379500000003, 122.23921969999999], [-31.952240000000003, 115.8613968]],
                {"bubblingMouseEvents": true, "color": "#FFC000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#FFC000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_e5b1f4a74c9049c4be01f104c9fbcdc2);
        
    
            poly_line_offset_1efbdb67469b47b28c46f4ff92f8ca7f.bindTooltip(
                `<div>
                     Departing: Broome Arriving: Perth Aircraft Model: B737-476 Engine Model: CFM-56-3 Price: $90.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_6eab6f32bd854fa88124583f702d3916 = L.polyline(
                [[-41.438758899999996, 147.13467409999998], [-37.813999200000005, 144.9633179]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_e5b1f4a74c9049c4be01f104c9fbcdc2);
        
    
            poly_line_offset_6eab6f32bd854fa88124583f702d3916.bindTooltip(
                `<div>
                     Departing: Launceston Arriving: Melbourne Aircraft Model: B737-476 Engine Model: CFM-56-3 Price: $100.00
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_83eeb47c500f43529222f57cf41cd776 = L.polyline(
                [[-35.283458700000004, 149.128067], [-33.8678513, 151.2073212]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_e5b1f4a74c9049c4be01f104c9fbcdc2);
        
    
            poly_line_offset_83eeb47c500f43529222f57cf41cd776.bindTooltip(
                `<div>
                     Departing: Canberra Arriving: Sydney Aircraft Model: B737-476 Engine Model: CFM-56-3 Price: $120.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_9bced2cccb774b25a8f5acc13e19d5b2 = L.polyline(
                [[-12.4611301, 130.8418427], [-23.6974792, 133.8836212]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_e5b1f4a74c9049c4be01f104c9fbcdc2);
        
    
            poly_line_offset_9bced2cccb774b25a8f5acc13e19d5b2.bindTooltip(
                `<div>
                     Departing: Darwin Arriving: Alice Springs Aircraft Model: B737-476 Engine Model: CFM-56-3 Price: $120.00 Space Class: E
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_7c2a2b3419114366bfdcc2d286be4941 = L.polyline(
                [[-23.6974792, 133.8836212], [-12.4611301, 130.8418427]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_e5b1f4a74c9049c4be01f104c9fbcdc2);
        
    
            poly_line_offset_7c2a2b3419114366bfdcc2d286be4941.bindTooltip(
                `<div>
                     Departing: Alice Springs Arriving: Darwin Aircraft Model: B737-476 Engine Model: CFM-56-3 Price: $120.00 Space Class: E
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_ec8eca092c504e789df43c1148c42664 = L.polyline(
                [[-17.955379500000003, 122.23921969999999], [-31.952240000000003, 115.8613968]],
                {"bubblingMouseEvents": true, "color": "#FFC000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#FFC000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_e5b1f4a74c9049c4be01f104c9fbcdc2);
        
    
            poly_line_offset_ec8eca092c504e789df43c1148c42664.bindTooltip(
                `<div>
                     Departing: Broome Arriving: Perth Aircraft Model: B737-476 Engine Model: CFM-56-3 Price: $90.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_8526b2a71a3a4a7e9f96d9fe5db18e76 = L.polyline(
                [[-41.438758899999996, 147.13467409999998], [-37.813999200000005, 144.9633179]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_e5b1f4a74c9049c4be01f104c9fbcdc2);
        
    
            poly_line_offset_8526b2a71a3a4a7e9f96d9fe5db18e76.bindTooltip(
                `<div>
                     Departing: Launceston Arriving: Melbourne Aircraft Model: B737-476 Engine Model: CFM-56-3 Price: $100.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_1984f34b5e084830a0b5d09fb915f8bb = L.polyline(
                [[-35.283458700000004, 149.128067], [-33.8678513, 151.2073212]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_e5b1f4a74c9049c4be01f104c9fbcdc2);
        
    
            poly_line_offset_1984f34b5e084830a0b5d09fb915f8bb.bindTooltip(
                `<div>
                     Departing: Canberra Arriving: Sydney Aircraft Model: B737-476 Engine Model: CFM-56-3 Price: $120.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_d466251eb6214d509fb5b2fab127ee94 = L.polyline(
                [[-12.4611301, 130.8418427], [-23.6974792, 133.8836212]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_e5b1f4a74c9049c4be01f104c9fbcdc2);
        
    
            poly_line_offset_d466251eb6214d509fb5b2fab127ee94.bindTooltip(
                `<div>
                     Departing: Darwin Arriving: Alice Springs Aircraft Model: B737-476 Engine Model: CFM-56-3 Price: $120.00 Space Class: E
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_80ab248a132a4257a8fec70826e9683b = L.polyline(
                [[-23.6974792, 133.8836212], [-12.4611301, 130.8418427]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_e5b1f4a74c9049c4be01f104c9fbcdc2);
        
    
            poly_line_offset_80ab248a132a4257a8fec70826e9683b.bindTooltip(
                `<div>
                     Departing: Alice Springs Arriving: Darwin Aircraft Model: B737-476 Engine Model: CFM-56-3 Price: $120.00 Space Class: E
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_5c7e2203393a4d01960634d52d9b2ccc = L.polyline(
                [[-17.955379500000003, 122.23921969999999], [-31.952240000000003, 115.8613968]],
                {"bubblingMouseEvents": true, "color": "#FFC000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#FFC000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_e5b1f4a74c9049c4be01f104c9fbcdc2);
        
    
            poly_line_offset_5c7e2203393a4d01960634d52d9b2ccc.bindTooltip(
                `<div>
                     Departing: Broome Arriving: Perth Aircraft Model: B737-476 Engine Model: CFM-56-3 Price: $90.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_d82365e987ae4a47b11d8a3f1d3674b9 = L.polyline(
                [[-41.438758899999996, 147.13467409999998], [-37.813999200000005, 144.9633179]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_e5b1f4a74c9049c4be01f104c9fbcdc2);
        
    
            poly_line_offset_d82365e987ae4a47b11d8a3f1d3674b9.bindTooltip(
                `<div>
                     Departing: Launceston Arriving: Melbourne Aircraft Model: B737-476 Engine Model: CFM-56-3 Price: $100.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_2e6d801cb9dd4c87bdd2237c7c1d0d45 = L.polyline(
                [[-35.283458700000004, 149.128067], [-33.8678513, 151.2073212]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_e5b1f4a74c9049c4be01f104c9fbcdc2);
        
    
            poly_line_offset_2e6d801cb9dd4c87bdd2237c7c1d0d45.bindTooltip(
                `<div>
                     Departing: Canberra Arriving: Sydney Aircraft Model: B737-476 Engine Model: CFM-56-3 Price: $120.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_cd2ef3e8cb6b48909dbfc3df26b2d5e8 = L.polyline(
                [[-12.4611301, 130.8418427], [-23.6974792, 133.8836212]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_e5b1f4a74c9049c4be01f104c9fbcdc2);
        
    
            poly_line_offset_cd2ef3e8cb6b48909dbfc3df26b2d5e8.bindTooltip(
                `<div>
                     Departing: Darwin Arriving: Alice Springs Aircraft Model: B737-476 Engine Model: CFM-56-3 Price: $120.00 Space Class: E
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_bdf417866eba46ada8f1479e71dea3b4 = L.polyline(
                [[-23.6974792, 133.8836212], [-12.4611301, 130.8418427]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_e5b1f4a74c9049c4be01f104c9fbcdc2);
        
    
            poly_line_offset_bdf417866eba46ada8f1479e71dea3b4.bindTooltip(
                `<div>
                     Departing: Alice Springs Arriving: Darwin Aircraft Model: B737-476 Engine Model: CFM-56-3 Price: $120.00 Space Class: E
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_a64d051e6a7e4a528d16cec37184105d = L.polyline(
                [[-17.955379500000003, 122.23921969999999], [-31.952240000000003, 115.8613968]],
                {"bubblingMouseEvents": true, "color": "#FFC000", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#FFC000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_e5b1f4a74c9049c4be01f104c9fbcdc2);
        
    
            poly_line_offset_a64d051e6a7e4a528d16cec37184105d.bindTooltip(
                `<div>
                     Departing: Broome Arriving: Perth Aircraft Model: B737-476 Engine Model: CFM-56-3 Price: $90.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_offset_33ff1fc02b6543b2a6369b2fc5177920 = L.polyline(
                [[-41.438758899999996, 147.13467409999998], [-37.813999200000005, 144.9633179]],
                {"bubblingMouseEvents": true, "color": "#ED7D31", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#ED7D31", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "offset": 5, "opacity": 1, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(feature_group_e5b1f4a74c9049c4be01f104c9fbcdc2);
        
    
            poly_line_offset_33ff1fc02b6543b2a6369b2fc5177920.bindTooltip(
                `<div>
                     Departing: Launceston Arriving: Melbourne Aircraft Model: B737-476 Engine Model: CFM-56-3 Price: $100.00 Space Class: B
                 </div>`,
                {"sticky": true}
            );
        
    
            var feature_group_39e6773c2252489a82d157a454367096 = L.featureGroup(
                {}
            ).addTo(map_2b09cbfb923147c0b2d49acb4399a6e6);
        
    
            var circle_marker_de6ef4203b8f4602ab5cbbde8c5f8c43 = L.circleMarker(
                [-33.8678513, 151.2073212],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_de6ef4203b8f4602ab5cbbde8c5f8c43.bindTooltip(
                `<div>
                     Sydney
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_7ec523930fda4a9f948af2cfb55b53e5 = L.circleMarker(
                [-35.283458700000004, 149.128067],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_7ec523930fda4a9f948af2cfb55b53e5.bindTooltip(
                `<div>
                     Canberra
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_b962ad87a7b64cd68b59be1c4a73f0ee = L.circleMarker(
                [-32.9271507, 151.776474],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_b962ad87a7b64cd68b59be1c4a73f0ee.bindTooltip(
                `<div>
                     Newcastle
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_32b8745ef69a442ea0bf396e4f67c025 = L.circleMarker(
                [-31.953913500000002, 141.45393959999998],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_32b8745ef69a442ea0bf396e4f67c025.bindTooltip(
                `<div>
                     Broken Hill
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_fba4a7442f554943b2733cb57e9b10e9 = L.circleMarker(
                [-37.813999200000005, 144.9633179],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_fba4a7442f554943b2733cb57e9b10e9.bindTooltip(
                `<div>
                     Melbourne
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_c0971dd44a7d4414b44dfd2a6f956626 = L.circleMarker(
                [-36.7581787, 144.2802429],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_c0971dd44a7d4414b44dfd2a6f956626.bindTooltip(
                `<div>
                     Bendigo
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_66450baedaab4e30b7125fecaa6aab36 = L.circleMarker(
                [-34.928661299999995, 138.59863280000002],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_66450baedaab4e30b7125fecaa6aab36.bindTooltip(
                `<div>
                     Adelaide
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_0142c4ee92dc4f08a2df3a3155798ae7 = L.circleMarker(
                [-12.4611301, 130.8418427],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_0142c4ee92dc4f08a2df3a3155798ae7.bindTooltip(
                `<div>
                     Darwin
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_da44f4ad41884e3b8b5f8a95e5acd03f = L.circleMarker(
                [-23.6974792, 133.8836212],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_da44f4ad41884e3b8b5f8a95e5acd03f.bindTooltip(
                `<div>
                     Alice Springs
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_a33fe56d6a634e59ac0cb055d9cf5a13 = L.circleMarker(
                [-31.952240000000003, 115.8613968],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_a33fe56d6a634e59ac0cb055d9cf5a13.bindTooltip(
                `<div>
                     Perth
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_e22a53f935a54113b31f92b0e585e36e = L.circleMarker(
                [-35.0269203, 117.8836899],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_e22a53f935a54113b31f92b0e585e36e.bindTooltip(
                `<div>
                     Albany
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_19260447c0a54eeaabaa50019611e234 = L.circleMarker(
                [-30.7461395, 121.47419740000002],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_19260447c0a54eeaabaa50019611e234.bindTooltip(
                `<div>
                     Kalgoorlie
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_bb6bc36509d44d2382bab29b838797e3 = L.circleMarker(
                [-17.955379500000003, 122.23921969999999],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_bb6bc36509d44d2382bab29b838797e3.bindTooltip(
                `<div>
                     Broome
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_a165a5db98d64475b06636da1709ea9b = L.circleMarker(
                [-41.438758899999996, 147.13467409999998],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_a165a5db98d64475b06636da1709ea9b.bindTooltip(
                `<div>
                     Launceston
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_f1b8f43abf14490ab647eb338e0ccf4e = L.circleMarker(
                [-42.8793602, 147.3294067],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_f1b8f43abf14490ab647eb338e0ccf4e.bindTooltip(
                `<div>
                     Hobart
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_eda0f030e66848c4b1f3bc1e73e48b98 = L.circleMarker(
                [-27.4679394, 153.02809140000002],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_eda0f030e66848c4b1f3bc1e73e48b98.bindTooltip(
                `<div>
                     Brisbane
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_0d3e9af352854d13b86125a9aa6e0ddf = L.circleMarker(
                [-20.7255748, 139.4927085],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_0d3e9af352854d13b86125a9aa6e0ddf.bindTooltip(
                `<div>
                     Mt Isa
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_934b44f760684471862188d514f15aa7 = L.circleMarker(
                [-23.380319600000004, 150.50595090000002],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_934b44f760684471862188d514f15aa7.bindTooltip(
                `<div>
                     Rockhampton
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_706df088210e42bfaec802745a49be47 = L.circleMarker(
                [-16.923040399999998, 145.7662506],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_706df088210e42bfaec802745a49be47.bindTooltip(
                `<div>
                     Cairns
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_d1d8056d54ed4a1b8a7f5a16cb2afcf9 = L.circleMarker(
                [-32.4959717, 137.7728119],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_d1d8056d54ed4a1b8a7f5a16cb2afcf9.bindTooltip(
                `<div>
                     Pt Augusta
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_37ff1ad4050d450ba8a02e800bf2d667 = L.circleMarker(
                [-33.8678513, 151.2073212],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_37ff1ad4050d450ba8a02e800bf2d667.bindTooltip(
                `<div>
                     Sydney
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_a878bdfa3cde463692f424d9a895b2d0 = L.circleMarker(
                [-35.283458700000004, 149.128067],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_a878bdfa3cde463692f424d9a895b2d0.bindTooltip(
                `<div>
                     Canberra
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_f05b541c60a94ea7a5faf9ef510a0182 = L.circleMarker(
                [-32.9271507, 151.776474],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_f05b541c60a94ea7a5faf9ef510a0182.bindTooltip(
                `<div>
                     Newcastle
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_0a8bcf4c5a234588afa9fac097c12f9f = L.circleMarker(
                [-31.953913500000002, 141.45393959999998],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_0a8bcf4c5a234588afa9fac097c12f9f.bindTooltip(
                `<div>
                     Broken Hill
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_fb516dfe8929431280db9fd27f45b1de = L.circleMarker(
                [-37.813999200000005, 144.9633179],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_fb516dfe8929431280db9fd27f45b1de.bindTooltip(
                `<div>
                     Melbourne
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_062d35e69d1e4e94a4b2a07f7d1f87d9 = L.circleMarker(
                [-36.7581787, 144.2802429],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_062d35e69d1e4e94a4b2a07f7d1f87d9.bindTooltip(
                `<div>
                     Bendigo
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_e0fb7df7686c4bd68ca3b501c89416dc = L.circleMarker(
                [-34.928661299999995, 138.59863280000002],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_e0fb7df7686c4bd68ca3b501c89416dc.bindTooltip(
                `<div>
                     Adelaide
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_45ce69d1eb374db8a7d102676f597d3d = L.circleMarker(
                [-12.4611301, 130.8418427],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_45ce69d1eb374db8a7d102676f597d3d.bindTooltip(
                `<div>
                     Darwin
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_e1b01df5e9b042a9bc6ca53d5286a986 = L.circleMarker(
                [-23.6974792, 133.8836212],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_e1b01df5e9b042a9bc6ca53d5286a986.bindTooltip(
                `<div>
                     Alice Springs
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_b86cffd175d14598a3d7f6d8521e3ec3 = L.circleMarker(
                [-31.952240000000003, 115.8613968],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_b86cffd175d14598a3d7f6d8521e3ec3.bindTooltip(
                `<div>
                     Perth
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_684fb78549084cfdbcec8e6062aecd04 = L.circleMarker(
                [-35.0269203, 117.8836899],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_684fb78549084cfdbcec8e6062aecd04.bindTooltip(
                `<div>
                     Albany
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_db4fc43a0c554f3cb7e95ea558ce57d3 = L.circleMarker(
                [-30.7461395, 121.47419740000002],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_db4fc43a0c554f3cb7e95ea558ce57d3.bindTooltip(
                `<div>
                     Kalgoorlie
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_c4b3a47e8b944b909137b225841fda3b = L.circleMarker(
                [-17.955379500000003, 122.23921969999999],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_c4b3a47e8b944b909137b225841fda3b.bindTooltip(
                `<div>
                     Broome
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_c4bf0048f2fa45c9be30f37380391437 = L.circleMarker(
                [-41.438758899999996, 147.13467409999998],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_c4bf0048f2fa45c9be30f37380391437.bindTooltip(
                `<div>
                     Launceston
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_7377df165e264b8b890c7a7c8aee631e = L.circleMarker(
                [-42.8793602, 147.3294067],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_7377df165e264b8b890c7a7c8aee631e.bindTooltip(
                `<div>
                     Hobart
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_f0c896582e2d4d8c928a3372ffbd727f = L.circleMarker(
                [-27.4679394, 153.02809140000002],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_f0c896582e2d4d8c928a3372ffbd727f.bindTooltip(
                `<div>
                     Brisbane
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_d115ecb9e14147e1b05161997cceb02f = L.circleMarker(
                [-20.7255748, 139.4927085],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_d115ecb9e14147e1b05161997cceb02f.bindTooltip(
                `<div>
                     Mt Isa
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_b84e1acbedce47b59602f273fbe75af0 = L.circleMarker(
                [-23.380319600000004, 150.50595090000002],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_b84e1acbedce47b59602f273fbe75af0.bindTooltip(
                `<div>
                     Rockhampton
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_86de61596dee4b1d927be38bccd79a21 = L.circleMarker(
                [-16.923040399999998, 145.7662506],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_86de61596dee4b1d927be38bccd79a21.bindTooltip(
                `<div>
                     Cairns
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_1c98607d7e43422f9dc0f25a6f20c7aa = L.circleMarker(
                [-32.4959717, 137.7728119],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_1c98607d7e43422f9dc0f25a6f20c7aa.bindTooltip(
                `<div>
                     Pt Augusta
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_0bc5cf16b2ee441e9bc13c2daaca0038 = L.circleMarker(
                [-33.8678513, 151.2073212],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_0bc5cf16b2ee441e9bc13c2daaca0038.bindTooltip(
                `<div>
                     Sydney
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_e56b86878cd24b3fb51609bb39e96df7 = L.circleMarker(
                [-35.283458700000004, 149.128067],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_e56b86878cd24b3fb51609bb39e96df7.bindTooltip(
                `<div>
                     Canberra
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_aa98ebbae069456c97282be952983f1c = L.circleMarker(
                [-32.9271507, 151.776474],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_aa98ebbae069456c97282be952983f1c.bindTooltip(
                `<div>
                     Newcastle
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_504d6b1fe862443aae0c7d093d9ce9b0 = L.circleMarker(
                [-31.953913500000002, 141.45393959999998],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_504d6b1fe862443aae0c7d093d9ce9b0.bindTooltip(
                `<div>
                     Broken Hill
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_f0cf108d6fba43f9bae70a6452a4fa51 = L.circleMarker(
                [-37.813999200000005, 144.9633179],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_f0cf108d6fba43f9bae70a6452a4fa51.bindTooltip(
                `<div>
                     Melbourne
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_9b884f6390ff4acdbe8b4a817d40e3eb = L.circleMarker(
                [-36.7581787, 144.2802429],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_9b884f6390ff4acdbe8b4a817d40e3eb.bindTooltip(
                `<div>
                     Bendigo
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_0eb1af39e90d4252b7f15e54b4e8089c = L.circleMarker(
                [-34.928661299999995, 138.59863280000002],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_0eb1af39e90d4252b7f15e54b4e8089c.bindTooltip(
                `<div>
                     Adelaide
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_d654bedaa49549889c2bf2282af5e74d = L.circleMarker(
                [-12.4611301, 130.8418427],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_d654bedaa49549889c2bf2282af5e74d.bindTooltip(
                `<div>
                     Darwin
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_048b5383c32f4ba194ff88d0f183ca40 = L.circleMarker(
                [-23.6974792, 133.8836212],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_048b5383c32f4ba194ff88d0f183ca40.bindTooltip(
                `<div>
                     Alice Springs
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_c8030b42d46b41a198e4bdc735856c1e = L.circleMarker(
                [-31.952240000000003, 115.8613968],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_c8030b42d46b41a198e4bdc735856c1e.bindTooltip(
                `<div>
                     Perth
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_e80c5878040e4b67a8a16813b15e4d2d = L.circleMarker(
                [-35.0269203, 117.8836899],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_e80c5878040e4b67a8a16813b15e4d2d.bindTooltip(
                `<div>
                     Albany
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_d2b5e4e231ac4008a24112c50923e88d = L.circleMarker(
                [-30.7461395, 121.47419740000002],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_d2b5e4e231ac4008a24112c50923e88d.bindTooltip(
                `<div>
                     Kalgoorlie
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_32e478f44b89463facd590dbc2ad3009 = L.circleMarker(
                [-17.955379500000003, 122.23921969999999],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_32e478f44b89463facd590dbc2ad3009.bindTooltip(
                `<div>
                     Broome
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_77d65e6daaa148e6a888f67d1c90fb32 = L.circleMarker(
                [-41.438758899999996, 147.13467409999998],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_77d65e6daaa148e6a888f67d1c90fb32.bindTooltip(
                `<div>
                     Launceston
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_3ebb9b8327ec4a5b91b8db7943fdbf4f = L.circleMarker(
                [-42.8793602, 147.3294067],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_3ebb9b8327ec4a5b91b8db7943fdbf4f.bindTooltip(
                `<div>
                     Hobart
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_393bf697ab0e49fba73c26a590dd1dc7 = L.circleMarker(
                [-27.4679394, 153.02809140000002],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_393bf697ab0e49fba73c26a590dd1dc7.bindTooltip(
                `<div>
                     Brisbane
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_50bfd72c0d874ba6922e6d534aefee74 = L.circleMarker(
                [-20.7255748, 139.4927085],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_50bfd72c0d874ba6922e6d534aefee74.bindTooltip(
                `<div>
                     Mt Isa
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_916612ad94544a5994ed4c8a7b47a4b0 = L.circleMarker(
                [-23.380319600000004, 150.50595090000002],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_916612ad94544a5994ed4c8a7b47a4b0.bindTooltip(
                `<div>
                     Rockhampton
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_c2f4234c25b144838d05e8f9d4385ecc = L.circleMarker(
                [-16.923040399999998, 145.7662506],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_c2f4234c25b144838d05e8f9d4385ecc.bindTooltip(
                `<div>
                     Cairns
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_18912f2cf39f40dc90c8f2b7f124dd3f = L.circleMarker(
                [-32.4959717, 137.7728119],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_18912f2cf39f40dc90c8f2b7f124dd3f.bindTooltip(
                `<div>
                     Pt Augusta
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_dad0955210254c918c09b7ff308bc2d1 = L.circleMarker(
                [-33.8678513, 151.2073212],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_dad0955210254c918c09b7ff308bc2d1.bindTooltip(
                `<div>
                     Sydney
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_3c89fe49af2741ff99f373726b095ca6 = L.circleMarker(
                [-35.283458700000004, 149.128067],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_3c89fe49af2741ff99f373726b095ca6.bindTooltip(
                `<div>
                     Canberra
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_fe2ec1f435be4d7c92bb3f52c2a234ba = L.circleMarker(
                [-32.9271507, 151.776474],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_fe2ec1f435be4d7c92bb3f52c2a234ba.bindTooltip(
                `<div>
                     Newcastle
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_118496fa14e94e93aa8e62fe16008230 = L.circleMarker(
                [-31.953913500000002, 141.45393959999998],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_118496fa14e94e93aa8e62fe16008230.bindTooltip(
                `<div>
                     Broken Hill
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_fc236bed80db4873a7a08df78df293c8 = L.circleMarker(
                [-37.813999200000005, 144.9633179],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_fc236bed80db4873a7a08df78df293c8.bindTooltip(
                `<div>
                     Melbourne
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_42ac9b8db23d46e980e5e9832366273c = L.circleMarker(
                [-36.7581787, 144.2802429],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_42ac9b8db23d46e980e5e9832366273c.bindTooltip(
                `<div>
                     Bendigo
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_6788795cb1584ca9ad67d6c51c4097b1 = L.circleMarker(
                [-34.928661299999995, 138.59863280000002],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_6788795cb1584ca9ad67d6c51c4097b1.bindTooltip(
                `<div>
                     Adelaide
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_263a0758ba6144709f14dca2b2abe326 = L.circleMarker(
                [-12.4611301, 130.8418427],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_263a0758ba6144709f14dca2b2abe326.bindTooltip(
                `<div>
                     Darwin
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_f106bb519f1a4285bd339f93c4a2aa74 = L.circleMarker(
                [-23.6974792, 133.8836212],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_f106bb519f1a4285bd339f93c4a2aa74.bindTooltip(
                `<div>
                     Alice Springs
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_dd59472567574bab8d1a8dd6bcd1976b = L.circleMarker(
                [-31.952240000000003, 115.8613968],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_dd59472567574bab8d1a8dd6bcd1976b.bindTooltip(
                `<div>
                     Perth
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_45f09e827ae14f119f51d59fa53a621e = L.circleMarker(
                [-35.0269203, 117.8836899],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_45f09e827ae14f119f51d59fa53a621e.bindTooltip(
                `<div>
                     Albany
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_33e44b928838402ebb37c404245a1c4c = L.circleMarker(
                [-30.7461395, 121.47419740000002],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_33e44b928838402ebb37c404245a1c4c.bindTooltip(
                `<div>
                     Kalgoorlie
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_f44adc9bd0fe4450ba81464832b8febb = L.circleMarker(
                [-17.955379500000003, 122.23921969999999],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_f44adc9bd0fe4450ba81464832b8febb.bindTooltip(
                `<div>
                     Broome
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_43fdae09e38849c19731ce26ece0463b = L.circleMarker(
                [-41.438758899999996, 147.13467409999998],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_43fdae09e38849c19731ce26ece0463b.bindTooltip(
                `<div>
                     Launceston
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_0dd54948b82e44a797f22422affafe06 = L.circleMarker(
                [-42.8793602, 147.3294067],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_0dd54948b82e44a797f22422affafe06.bindTooltip(
                `<div>
                     Hobart
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_99132e371f134a6f883e504261ebf82d = L.circleMarker(
                [-27.4679394, 153.02809140000002],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_99132e371f134a6f883e504261ebf82d.bindTooltip(
                `<div>
                     Brisbane
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_6e2754d27c07491e8643e31a841b064d = L.circleMarker(
                [-20.7255748, 139.4927085],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_6e2754d27c07491e8643e31a841b064d.bindTooltip(
                `<div>
                     Mt Isa
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_a38e7052d83941d4a797580bcdaf3786 = L.circleMarker(
                [-23.380319600000004, 150.50595090000002],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_a38e7052d83941d4a797580bcdaf3786.bindTooltip(
                `<div>
                     Rockhampton
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_ed3f755a192f4247b36c18caab24229c = L.circleMarker(
                [-16.923040399999998, 145.7662506],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_ed3f755a192f4247b36c18caab24229c.bindTooltip(
                `<div>
                     Cairns
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_90f45bd453b54a499521cd893156f019 = L.circleMarker(
                [-32.4959717, 137.7728119],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#f9a729", "fillOpacity": 100, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7, "stroke": true, "weight": 0}
            ).addTo(feature_group_39e6773c2252489a82d157a454367096);
        
    
            circle_marker_90f45bd453b54a499521cd893156f019.bindTooltip(
                `<div>
                     Pt Augusta
                 </div>`,
                {"sticky": true}
            );
        
    
            var layer_control_e6d99228f887491489cf8350a194d92f = {
                base_layers : {
                    "cartodbdark_matter" : tile_layer_0e361733a70740b8bbc7ba3a324d0c8b,
                },
                overlays :  {
                    "A320-232" : feature_group_1e99830b659146f19e4de9fbf52339ba,
                    "A330-202" : feature_group_8581070929d640f782a848959b6812e9,
                    "A330-203" : feature_group_5045b6969442493abcc8e49e0c9313a7,
                    "A330-243" : feature_group_b9d313c2d58e4e0995c249fe327ce762,
                    "UNKNOWN" : feature_group_e2dc8c44c13342f99d22e0ae12d27fc0,
                    "B737-3B7" : feature_group_9f1ac2c37e62405ebcfd2d457851456f,
                    "B737-476" : feature_group_e5b1f4a74c9049c4be01f104c9fbcdc2,
                    "Cities" : feature_group_39e6773c2252489a82d157a454367096,
                },
            };
            L.control.layers(
                layer_control_e6d99228f887491489cf8350a194d92f.base_layers,
                layer_control_e6d99228f887491489cf8350a194d92f.overlays,
                {"autoZIndex": true, "collapsed": true, "position": "topright"}
            ).addTo(map_2b09cbfb923147c0b2d49acb4399a6e6);
        
</script>
