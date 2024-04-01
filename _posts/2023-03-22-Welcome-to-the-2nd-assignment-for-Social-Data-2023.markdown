---
layout: post
title:  "2nd Assignment for Social Data 2023"
date:   2023-03-22 12:25:55 +01:00
categories: Social Data Viz
---

## Crime in San Francisco

Welcome to our web page on the crime data set of San Francisco. This data set contains information on many different types of crimes in San Francisco, including the crime category, the location specified by latitude and longitude position, the day of the week, the time of the day etc. This data set spans several years, from 2003 to 2017. Therefore, several trends and patterns are identifiable and the data set can be used to provide a comprehensive overview of the crime trends in the city. 
## Exploring how to avoid assaults in SF
On the 28th of February 2023, two teens were arrested for assault near Dolores Park in San Francisco ([article](https://www.cbsnews.com/sanfrancisco/news/sf-assault-2-teen-girls-on-scooters-arrested-18th-street-dolores-park/)). This led to a substantial media coverage leading to news stories present in both CBS and ABC News [1,2] among other. According to officers, two people were assaulted by two teens, who rode into them on electric scooters. The suspects then got off the scooters and continued attacking the victims by punching them.
Considering this recent crime, we deem it interesting to analyse the data set and see the trends and patterns regarding assault crimes. By analysing the trends and patterns in assault crimes, we hope to provide the reader of this page with additional knowledge and ability to therefore make safer decisions in their life.
To highlight this, we firstly draw attention towards the distribution of when in a 24-hour cycle the assaults most frequently take place in SF below in Figure 1.

<figure>
    <img src='/SocialDataAssignment2/assets/images/assault_polar.jpg' width=500 height=500>
    <figcaption>Figure 1: Visualisation of the 24-hour cycle of assault crimes in San Francisco using a polar chart.</figcaption>
</figure>

From this figure it becomes apparent that most assault crimes happen during the evenings, which is clearly shown based on the high density of bars in that region of the figure compared to the hours between 2am to 8am. One might therefore envision that citizens of SF should be more cautious around the mentioned time of the day, and for example be mindful of when one plans on leaving work to get home. As we are deeply touched by the assault crime occuring on the 28th of February 2023, which happened at around 17:40, we feel obliged to inform the population about the tendencies of assault crimes in general. In this way, we hope to enlighten citizens - however without advocating fear and unreasonable behaviour. It is important to remember that the raw number of assault crimes are not solely representative of the crimes in the SF area, and can only be used to showcase a part of the whole story. 

In this next section, we hope to illuminate a more complete description of the assault crimes in SF. We want to not only detail the timestamp of assault crimes, but more importantly also to be able to answer the question: Where is it the safest to stay in SF to avoid assault crimes? In Figure 2, we present a map of San Francisco in order to show the exact position of each assault crime taking place in the month of February between 2003-2017. In this way, we showcase the tendency of assaults in February as the 2023 incident also took place during this month. Even though the figure only shows a sample of the data, we can confirm that the sample is representative for the true distribution of every month. The general dependency between assault crimes and location stands, and can be used as a legitimate representation of where to avoid assault crimes in February, but also across the whole year.

<figure>
    <img src='/SocialDataAssignment2/assets/images/assault_map_heat.png' width=500 height=400 class="center">
    <figcaption>Figure 2: Heatmap showing the frequency of assault crimes in February between 2003 and 2017. We also highlight the location of the 2023 incident. </figcaption>
</figure>

Now in Figure 2, we can clearly see the trends and patterns of where assault crimes happen. Namely, that they tend to happen quite often in the northeast part of San Francisco. This includes Tenderloin, Downtown and Mission. The assault crime, which happened on the 28th of February 2023 also happened in the northeast part of San Francisco, so this shows the same tendency. Now one can conclude both the when’s as well as the where’s of assault crimes in San Francisco. We note that the visualisation is not normalised to the population sizes of the areas. Therefore, the map we show might be influenced by a confounding variable such as population size, which could explain parts of the tendency. Nevertheless, the conclusions described still hold, specifically that the area in the northeast is more prone to assault crimes.

Only looking at assault crimes is not a sufficient point of reference of the safety. Maybe we do not only just want to learn about assault crimes specifically. As previously mentioned, the crime data set of San Francisco provides data collected from many different categories of crime. Similar crimes to assault may be disorderly conduct or theft. Finally, we show an interactive plot in Figure 3 that shows the occurences of different crime types. We strongly encourage the reader to explore emerging insights through filtering, zooming, and highlighting the different aspects of the visualisation. 

We would love to see what you come up with, so feel free to share it on Twitter using #StopCrimesInSFInsights.

<html lang="en">
  
  <head>
    
      <meta charset="utf-8">
      <title>Bokeh Plot</title>
      
      
        
          
        
        
          
        <script type="text/javascript" src="https://cdn.bokeh.org/bokeh/release/bokeh-2.2.3.min.js" integrity="sha384-T2yuo9Oe71Cz/I4X9Ac5+gpEa5a8PpJCDlqKYO0CfAuEszu1JrXLl8YugMqYe3sM" crossorigin="anonymous"></script>
        <script type="text/javascript">
            Bokeh.set_log_level("info");
        </script>
        
      
      
    
  </head>
  
  
  <body>
    
      
        
          
          
            
              <div class="bk-root" id="044c4ebd-c50d-4da3-8f7f-898d46875f27" data-root-id="1150"></div>
            
          
        
      
      
        <script type="application/json" id="1375">
          {"c9406b3d-10bc-4001-82ea-a8e8c82d8de0":{"roots":{"references":[{"attributes":{},"id":"1164","type":"BasicTicker"},{"attributes":{},"id":"1189","type":"CategoricalTickFormatter"},{"attributes":{"label":{"value":"BURGLARY"},"renderers":[{"id":"1185"}]},"id":"1288","type":"LegendItem"},{"attributes":{"label":{"value":"LARCENY/THEFT"},"renderers":[{"id":"1201"}]},"id":"1289","type":"LegendItem"},{"attributes":{},"id":"1191","type":"BasicTickFormatter"},{"attributes":{"fill_alpha":{"value":0.5},"fill_color":{"value":"#aec7e8"},"line_alpha":{"value":0.5},"line_color":{"value":"#aec7e8"},"top":{"field":"LARCENY/THEFT"},"x":{"field":"Hour_hour"}},"id":"1200","type":"VBar"},{"attributes":{"fill_alpha":{"value":0.5},"fill_color":{"value":"#2ca02c"},"line_alpha":{"value":0.5},"line_color":{"value":"#2ca02c"},"top":{"field":"ASSAULT"},"x":{"field":"Hour_hour"}},"id":"1245","type":"VBar"},{"attributes":{"label":{"value":"ROBBERY"},"renderers":[{"id":"1216"}]},"id":"1290","type":"LegendItem"},{"attributes":{"fill_alpha":{"value":0.1},"fill_color":{"value":"#2ca02c"},"line_alpha":{"value":0.1},"line_color":{"value":"#2ca02c"},"top":{"field":"ASSAULT"},"x":{"field":"Hour_hour"}},"id":"1244","type":"VBar"},{"attributes":{"axis":{"id":"1160"},"ticker":null},"id":"1162","type":"Grid"},{"attributes":{"label":{"value":"ASSAULT"},"renderers":[{"id":"1246"}]},"id":"1292","type":"LegendItem"},{"attributes":{"label":{"value":"LARCENY/THEFT"},"renderers":[{"id":"1201"}]},"id":"1211","type":"LegendItem"},{"attributes":{"label":{"value":"VEHICLE THEFT"},"renderers":[{"id":"1276"}]},"id":"1294","type":"LegendItem"},{"attributes":{"fill_alpha":{"value":0.1},"fill_color":{"value":"#98df8a"},"line_alpha":{"value":0.1},"line_color":{"value":"#98df8a"},"top":{"field":"DISORDERLY CONDUCT"},"x":{"field":"Hour_hour"}},"id":"1259","type":"VBar"},{"attributes":{"data_source":{"id":"1148"},"glyph":{"id":"1243"},"hover_glyph":null,"muted":true,"muted_glyph":{"id":"1245"},"nonselection_glyph":{"id":"1244"},"selection_glyph":null,"view":{"id":"1247"}},"id":"1246","type":"GlyphRenderer"},{"attributes":{"source":{"id":"1148"}},"id":"1247","type":"CDSView"},{"attributes":{"label":{"value":"ASSAULT"},"renderers":[{"id":"1246"}]},"id":"1256","type":"LegendItem"},{"attributes":{"source":{"id":"1148"}},"id":"1202","type":"CDSView"},{"attributes":{"axis":{"id":"1163"},"dimension":1,"ticker":null},"id":"1166","type":"Grid"},{"attributes":{"fill_alpha":{"value":0.5},"fill_color":{"value":"#1f77b4"},"line_alpha":{"value":0.5},"line_color":{"value":"#1f77b4"},"top":{"field":"BURGLARY"},"x":{"field":"Hour_hour"}},"id":"1184","type":"VBar"},{"attributes":{"fill_alpha":{"value":0.1},"fill_color":{"value":"#1f77b4"},"line_alpha":{"value":0.1},"line_color":{"value":"#1f77b4"},"top":{"field":"BURGLARY"},"x":{"field":"Hour_hour"}},"id":"1183","type":"VBar"},{"attributes":{},"id":"1167","type":"PanTool"},{"attributes":{"data":{"ASSAULT":{"__ndarray__":"klDS+KW7qz98AOJ6JTypP5K/G+NRpKY/syGOnfU7lj+hqVLnsgCMP691xdrxRoY/RSsbYEUWjj9vC+5hsiqWP1EbMHHA/6A/jM+/TWoGoz9UsrxFIB+lPwzpP01NfKY/B3jJvhukqz/k0cMxlGOoPwncVZS116g/cZtmPIatqz+rWrMtQmmrP1boJyTsjqs/529kAIAfqz9OQUa37kaqP6+6luhVhKk/8nYpKJGCqj+ctU03RUqpPxXjGrzGOqg/","dtype":"float64","order":"little","shape":[24]},"BURGLARY":{"__ndarray__":"qCBtVJ2Toz9UAYWq12OZP4QsLPo6ZJs/PCdBdaNHnD/9DCkPXRCZP335Y/zL5JY/EbIj0o3qlj/HWtSRVLShPxjl68/8aas/ieK1pogHqD8+2/slKEKmP1Ta+oS1DKU/OqQxP5A9rD8Qi5msa5OiP1uSUy3MWKQ/pL7I14XMpz/OtCa15YqqP1yWo50pxLE/rH7BYFfvsT/gVdEHufmqP+ULW7QGnac/wkwVRXPJpj8lLhP7B6ulP7xEJ92DDKQ/","dtype":"float64","order":"little","shape":[24]},"DISORDERLY CONDUCT":{"__ndarray__":"2kDJIDbBqj8UO7ETO7GjPwaxCdaMrqE/Hr4E5hNFlj/eeRZCBX+QP8pIylIvd6Q/jJBirKj0uT8M3eAZZ4i3P6om0wAolLE/8ubACzp/qj9iokPQdKGmPxE0XahlQqQ/ETRdqGVCpD+hEde+p0ejPxxQrVW7/aE/23LC1i8QoT+rYjHbhoyfPz5H/1yeAJ4/xdMeVwHBoD/t2Bg1j6GbPw6UDGITrJk/tn6BiNxHnT/NTx6+BOajP1IRSCfxL6U/","dtype":"float64","order":"little","shape":[24]},"Hour_hour":[0,1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,21,22,23],"LARCENY/THEFT":{"__ndarray__":"iBLodKt1pD+lziBWQT2ZP8ZN0T0jb5A/X5Bw3+6lhD8WhhdpuN96P2wn7yrSAns/GLtTJTU8hT/N+kzwf7GQP6YCd0PTUJw/UxK2qF/MoD9seKShAfakP8UXrp8xDKc/LJEvDOCFrT88a6Zn1CuqP0dubAIlDKs/JskhgUWzrD99mqqk3wquPxsKO9h6IrE/oYaSweGLtD+aGylQq0mzP+upr0xs1bA/+anBVOhfrD8WE23knKSrP5Qd+CYfFKk/","dtype":"float64","order":"little","shape":[24]},"ROBBERY":{"__ndarray__":"4mFiFMWnqz8sz8bX+YmsP4cPCK/Yzq0/hGH81bj2oT9PC15djUGXP05DsFb8GJQ/4Md2GPl+kz9NNNhwfVWRP05kocqIcJM/TwteXY1Blz8HJMW40NiaPywggaWR/J0/Kbmfq1+/oT+pLe9obv+iP/Mt8OFTA6Q/qhvW2mBrpj89QhE4jbaoP2LjgmgMkKg/UK3S+Lwmqj9i0Wna/vurP1E45g4KjK8/YJpROtjZsT+OyEZkI7KxP9YF4s1MebA/","dtype":"float64","order":"little","shape":[24]},"STOLEN PROPERTY":{"__ndarray__":"wzeVY7F1qD/Ch3T6q0KhP0FZxK364pw/S3LUJVqglj+Dr6ciTR+UP8Tntcy2qI8/uux6H0CekT+YAn4WnfOYP5y/H4IKGaA/p4hQY28JoT/8s/MuHgGjP+o+darMq6Y/DomzhXq8rT9FxoaCbTurP/OJj+49g60/uB6F61G4rj/aWGGL7y+wPxjyopTURrA/JRsVSESdrz/ZyfYle1aqP+bRstVZU6g/dqfrcm4ipj/qPnWqzKumPwqrWxZ8PaU/","dtype":"float64","order":"little","shape":[24]},"VEHICLE THEFT":{"__ndarray__":"f6o7AUhEoz/PHiJqIVWaPzsVm7cr15Q/JifutyPpiT/nmxb5QwGEP+SH3URrBYQ/HPD6r+ewjT+MCbswdWqZP1bwjjxrOaI/pYva9MXWoT+FyMoffcCgP9fVaEENBp4/JyI2o9Utpj+nuB4xBYCfPyN/KIDCeKI/fKDlluvDpT8v2Xx6wd6pP7vtW4xiHLE/sLZohCbktD9MtOMf4UWyP5FTZ7N5LrM/qskh/+5vsj/YISTSkHSzP9VIFgEy/LA/","dtype":"float64","order":"little","shape":[24]}},"selected":{"id":"1194"},"selection_policy":{"id":"1193"}},"id":"1148","type":"ColumnDataSource"},{"attributes":{"bottom_units":"screen","fill_alpha":0.5,"fill_color":"lightgrey","left_units":"screen","level":"overlay","line_alpha":1.0,"line_color":"black","line_dash":[4,4],"line_width":2,"right_units":"screen","top_units":"screen"},"id":"1173","type":"BoxAnnotation"},{"attributes":{"label":{"value":"BURGLARY"},"renderers":[{"id":"1185"}]},"id":"1196","type":"LegendItem"},{"attributes":{},"id":"1193","type":"UnionRenderers"},{"attributes":{},"id":"1194","type":"Selection"},{"attributes":{"data_source":{"id":"1148"},"glyph":{"id":"1198"},"hover_glyph":null,"muted":true,"muted_glyph":{"id":"1200"},"nonselection_glyph":{"id":"1199"},"selection_glyph":null,"view":{"id":"1202"}},"id":"1201","type":"GlyphRenderer"},{"attributes":{},"id":"1158","type":"LinearScale"},{"attributes":{"fill_color":{"value":"#98df8a"},"line_color":{"value":"#98df8a"},"top":{"field":"DISORDERLY CONDUCT"},"x":{"field":"Hour_hour"}},"id":"1258","type":"VBar"},{"attributes":{"fill_color":{"value":"#ff7f0e"},"line_color":{"value":"#ff7f0e"},"top":{"field":"ROBBERY"},"x":{"field":"Hour_hour"}},"id":"1213","type":"VBar"},{"attributes":{"axis_label":"Hour of Day","formatter":{"id":"1189"},"ticker":{"id":"1161"}},"id":"1160","type":"CategoricalAxis"},{"attributes":{"fill_alpha":{"value":0.5},"fill_color":{"value":"#98df8a"},"line_alpha":{"value":0.5},"line_color":{"value":"#98df8a"},"top":{"field":"DISORDERLY CONDUCT"},"x":{"field":"Hour_hour"}},"id":"1260","type":"VBar"},{"attributes":{},"id":"1156","type":"CategoricalScale"},{"attributes":{"label":{"value":"STOLEN PROPERTY"},"renderers":[{"id":"1231"}]},"id":"1291","type":"LegendItem"},{"attributes":{"label":{"value":"DISORDERLY CONDUCT"},"renderers":[{"id":"1261"}]},"id":"1293","type":"LegendItem"},{"attributes":{"label":{"value":"DISORDERLY CONDUCT"},"renderers":[{"id":"1261"}]},"id":"1271","type":"LegendItem"},{"attributes":{"data_source":{"id":"1148"},"glyph":{"id":"1258"},"hover_glyph":null,"muted":true,"muted_glyph":{"id":"1260"},"nonselection_glyph":{"id":"1259"},"selection_glyph":null,"view":{"id":"1262"}},"id":"1261","type":"GlyphRenderer"},{"attributes":{"source":{"id":"1148"}},"id":"1262","type":"CDSView"},{"attributes":{"fill_alpha":{"value":0.1},"fill_color":{"value":"#aec7e8"},"line_alpha":{"value":0.1},"line_color":{"value":"#aec7e8"},"top":{"field":"LARCENY/THEFT"},"x":{"field":"Hour_hour"}},"id":"1199","type":"VBar"},{"attributes":{},"id":"1161","type":"CategoricalTicker"},{"attributes":{},"id":"1154","type":"DataRange1d"},{"attributes":{"fill_alpha":{"value":0.5},"fill_color":{"value":"#ff7f0e"},"line_alpha":{"value":0.5},"line_color":{"value":"#ff7f0e"},"top":{"field":"ROBBERY"},"x":{"field":"Hour_hour"}},"id":"1215","type":"VBar"},{"attributes":{"fill_color":{"value":"#d62728"},"line_color":{"value":"#d62728"},"top":{"field":"VEHICLE THEFT"},"x":{"field":"Hour_hour"}},"id":"1273","type":"VBar"},{"attributes":{"fill_alpha":{"value":0.1},"fill_color":{"value":"#ff7f0e"},"line_alpha":{"value":0.1},"line_color":{"value":"#ff7f0e"},"top":{"field":"ROBBERY"},"x":{"field":"Hour_hour"}},"id":"1214","type":"VBar"},{"attributes":{"fill_alpha":{"value":0.1},"fill_color":{"value":"#ffbb78"},"line_alpha":{"value":0.1},"line_color":{"value":"#ffbb78"},"top":{"field":"STOLEN PROPERTY"},"x":{"field":"Hour_hour"}},"id":"1229","type":"VBar"},{"attributes":{"data_source":{"id":"1148"},"glyph":{"id":"1213"},"hover_glyph":null,"muted":true,"muted_glyph":{"id":"1215"},"nonselection_glyph":{"id":"1214"},"selection_glyph":null,"view":{"id":"1217"}},"id":"1216","type":"GlyphRenderer"},{"attributes":{"source":{"id":"1148"}},"id":"1217","type":"CDSView"},{"attributes":{"axis_label":"Normalized Count","formatter":{"id":"1191"},"ticker":{"id":"1164"}},"id":"1163","type":"LinearAxis"},{"attributes":{"label":{"value":"ROBBERY"},"renderers":[{"id":"1216"}]},"id":"1226","type":"LegendItem"},{"attributes":{"text":"Crime Counts by Hour and Category"},"id":"1151","type":"Title"},{"attributes":{"data_source":{"id":"1148"},"glyph":{"id":"1182"},"hover_glyph":null,"muted":true,"muted_glyph":{"id":"1184"},"nonselection_glyph":{"id":"1183"},"selection_glyph":null,"view":{"id":"1186"}},"id":"1185","type":"GlyphRenderer"},{"attributes":{"fill_alpha":{"value":0.5},"fill_color":{"value":"#d62728"},"line_alpha":{"value":0.5},"line_color":{"value":"#d62728"},"top":{"field":"VEHICLE THEFT"},"x":{"field":"Hour_hour"}},"id":"1275","type":"VBar"},{"attributes":{"factors":["1","2","3","4","5","6","7","8","9","10","11","12","13","14","15","16","17","18","19","20","21","22","23","24"]},"id":"1149","type":"FactorRange"},{"attributes":{"fill_alpha":{"value":0.1},"fill_color":{"value":"#d62728"},"line_alpha":{"value":0.1},"line_color":{"value":"#d62728"},"top":{"field":"VEHICLE THEFT"},"x":{"field":"Hour_hour"}},"id":"1274","type":"VBar"},{"attributes":{"label":{"value":"VEHICLE THEFT"},"renderers":[{"id":"1276"}]},"id":"1286","type":"LegendItem"},{"attributes":{"data_source":{"id":"1148"},"glyph":{"id":"1273"},"hover_glyph":null,"muted":true,"muted_glyph":{"id":"1275"},"nonselection_glyph":{"id":"1274"},"selection_glyph":null,"view":{"id":"1277"}},"id":"1276","type":"GlyphRenderer"},{"attributes":{},"id":"1172","type":"HelpTool"},{"attributes":{"below":[{"id":"1160"}],"center":[{"id":"1162"},{"id":"1166"},{"id":"1195"}],"left":[{"id":"1163"},{"id":"1287"}],"plot_height":400,"plot_width":800,"renderers":[{"id":"1185"},{"id":"1201"},{"id":"1216"},{"id":"1231"},{"id":"1246"},{"id":"1261"},{"id":"1276"}],"title":{"id":"1151"},"toolbar":{"id":"1174"},"x_range":{"id":"1149"},"x_scale":{"id":"1156"},"y_range":{"id":"1154"},"y_scale":{"id":"1158"}},"id":"1150","subtype":"Figure","type":"Plot"},{"attributes":{"active_drag":"auto","active_inspect":"auto","active_multi":null,"active_scroll":"auto","active_tap":"auto","tools":[{"id":"1167"},{"id":"1168"},{"id":"1169"},{"id":"1170"},{"id":"1171"},{"id":"1172"}]},"id":"1174","type":"Toolbar"},{"attributes":{"source":{"id":"1148"}},"id":"1277","type":"CDSView"},{"attributes":{"fill_color":{"value":"#ffbb78"},"line_color":{"value":"#ffbb78"},"top":{"field":"STOLEN PROPERTY"},"x":{"field":"Hour_hour"}},"id":"1228","type":"VBar"},{"attributes":{"click_policy":"hide","items":[{"id":"1288"},{"id":"1289"},{"id":"1290"},{"id":"1291"},{"id":"1292"},{"id":"1293"},{"id":"1294"}],"location":[0,0]},"id":"1287","type":"Legend"},{"attributes":{},"id":"1171","type":"ResetTool"},{"attributes":{"fill_alpha":{"value":0.5},"fill_color":{"value":"#ffbb78"},"line_alpha":{"value":0.5},"line_color":{"value":"#ffbb78"},"top":{"field":"STOLEN PROPERTY"},"x":{"field":"Hour_hour"}},"id":"1230","type":"VBar"},{"attributes":{"fill_color":{"value":"#2ca02c"},"line_color":{"value":"#2ca02c"},"top":{"field":"ASSAULT"},"x":{"field":"Hour_hour"}},"id":"1243","type":"VBar"},{"attributes":{"overlay":{"id":"1173"}},"id":"1169","type":"BoxZoomTool"},{"attributes":{"data_source":{"id":"1148"},"glyph":{"id":"1228"},"hover_glyph":null,"muted":true,"muted_glyph":{"id":"1230"},"nonselection_glyph":{"id":"1229"},"selection_glyph":null,"view":{"id":"1232"}},"id":"1231","type":"GlyphRenderer"},{"attributes":{},"id":"1168","type":"WheelZoomTool"},{"attributes":{"click_policy":"hide","items":[{"id":"1196"},{"id":"1211"},{"id":"1226"},{"id":"1241"},{"id":"1256"},{"id":"1271"},{"id":"1286"}],"visible":false},"id":"1195","type":"Legend"},{"attributes":{},"id":"1170","type":"SaveTool"},{"attributes":{"source":{"id":"1148"}},"id":"1232","type":"CDSView"},{"attributes":{"label":{"value":"STOLEN PROPERTY"},"renderers":[{"id":"1231"}]},"id":"1241","type":"LegendItem"},{"attributes":{"source":{"id":"1148"}},"id":"1186","type":"CDSView"},{"attributes":{"fill_color":{"value":"#aec7e8"},"line_color":{"value":"#aec7e8"},"top":{"field":"LARCENY/THEFT"},"x":{"field":"Hour_hour"}},"id":"1198","type":"VBar"},{"attributes":{"fill_color":{"value":"#1f77b4"},"line_color":{"value":"#1f77b4"},"top":{"field":"BURGLARY"},"x":{"field":"Hour_hour"}},"id":"1182","type":"VBar"}],"root_ids":["1150"]},"title":"Bokeh Application","version":"2.2.3"}}
        </script>
        <script type="text/javascript">
          (function() {
            var fn = function() {
              Bokeh.safely(function() {
                (function(root) {
                  function embed_document(root) {
                    
                  var docs_json = document.getElementById('1375').textContent;
                  var render_items = [{"docid":"c9406b3d-10bc-4001-82ea-a8e8c82d8de0","root_ids":["1150"],"roots":{"1150":"044c4ebd-c50d-4da3-8f7f-898d46875f27"}}];
                  root.Bokeh.embed.embed_items(docs_json, render_items);
                
                  }
                  if (root.Bokeh !== undefined) {
                    embed_document(root);
                  } else {
                    var attempts = 0;
                    var timer = setInterval(function(root) {
                      if (root.Bokeh !== undefined) {
                        clearInterval(timer);
                        embed_document(root);
                      } else {
                        attempts++;
                        if (attempts > 100) {
                          clearInterval(timer);
                          console.log("Bokeh: ERROR: Unable to run BokehJS code because BokehJS library is missing");
                        }
                      }
                    }, 10, root)
                  }
                })(window);
              });
            };
            if (document.readyState != "loading") fn();
            else document.addEventListener("DOMContentLoaded", fn);
          })();
        </script>
    
  </body>
  
</html>

### References

1. [CBS News Article: 2 teens arrested in assault near San Francisco Dolores Park](https://www.cbsnews.com/sanfrancisco/news/sf-assault-2-teen-girls-on-scooters-arrested-18th-street-dolores-park/)
2. [ABC News Article: 2 teen girls arrested in connection to scooter attack near SF's Dolores Park, police say](https://abc7news.com/sf-dolores-park-beating-arrest-teen-girls-arrested-scooter-attack-couple-attacked/12894504/)