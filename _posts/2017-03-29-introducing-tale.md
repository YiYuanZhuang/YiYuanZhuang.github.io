---
layout: post
title:  " The Larceny/Theft Shadows in San Francisco "
author: "YiYuan, JiaNan, lingYu"
comments: true
tags: Tale
excerpt_separator: <!--more-->
sticky: true
hidden: true
date: 2024-05-07
---

Welcome to San Francisco Larceny/Theft Crime webpage!

San Francisco(SF) is a city full of freedom, but it is also overshadowed by rampant larceny/theft. This article is based on the crime data of the San Francisco Police Department from 2013 to 2017 [1], tracking the silent traces of theft, and analyzing the model of theft crime from the perspectives of time, space, and different types.  We look forward to bringing inspiration to local residents in dealing with theft crimes, while exploring more possibilities for optimizing police investment in San Francisco.

## "Carnival" Under the Night
A comprehensive investigation in San Francisco found that the incidence of theft is shocking, affecting more than half of the city's residents. These incidents involve an astonishing number of blatant car intrusions, often occurring in areas popular with tourists. This unsettling reality resonates deeply with the widespread civic disillusionment in this city. [2] To improve this situation, we first analyzed the distribution of theft in SF during a 24-hour cycle.

As the city transitions into evening, a crescendo of red bars signals a surge in theft incidents, peaking at 6 pm. This indicates thefts are more frequent when people may be returning home from get off work or when pedestrian traffic is high. On the contrary, the theft rate is lowest around 5 am. in the morning, and gradually increases after noon to the evening peak.

For community residents, as thefts peak at night, it is a good idea to remain vigilant at dusk, especially in known crowded or high-traffic areas, be more careful to secure personal belongings and be more aware of surroundings observation. Consider scheduling outings at lower-risk times, such as in the morning, to reduce chances of becoming a theft victim.

Law enforcement agencies can better protect these peak hours by allocating additional resources and patrols to prevent theft. In addition, community outreach activities can play a crucial role in educating the public to protect themselves from theft. Strategically deploying monitoring infrastructure in key areas, especially those with high incidence during peak hours, can serve both as a deterrent and an investigative role.

## Fiery Northeast
What catches the eye is a hot theft crime map. The red lighting up the northeastern heart of the city in San Francisco is not good news because it means theft is rampant.

During these five years, the density of theft incidents in the northeast of San Francisco has been consistently the highest. This includes public areas with high traffic and a large number of tourists, such as the financial district, the southern part of the market (SoMa), the task area, and the surrounding area of Market Street

With the passage of time, it can be observed that destructive behavior has spread to more residential areas and remote communities, indicating that the problem is not limited to commercial intensive and tourist centered areas, but criminal activities are spreading throughout the city. The central region. By 2016, the heat map showed that the high incidence areas had significantly expanded towards the southern and western parts of the city. The destruction activities in the central and eastern communities such as Potrero Hill, as well as the surrounding areas of Golden Gate Park and Dolores Park, have also increased, indicating that although these leisure areas are community centered, they cannot be spared from such incidents.

Obviously, theft is not only a problem in a central city, but also affects various communities throughout San Francisco. Measures to prevent theft need to be taken throughout the city, and social and environmental conditions that lead to high accident rates, such as poor lighting, lack of safety cameras, and proposing better property protection methods, need to be examined. In addition, based on the conclusions analyzed in the heat map, it can also help determine the priority of intervention areas and effectively customize community and police resources.


## Dangerous Theft Ballet

It is an "elaborate" ballet of thefts, with a number of different crime types spinning around over the course of a few hours as you tap the different types of thefts with your finger.

This crime ballet chart shows the occurrence of different types of larceny/theft at different times of the day. Based on Larceny/Theft descriptions in San Francisco crime data, it can be roughly divided into 4 types: Attempted, Petty theft, Grand theft, and Others. “Attempted" means an attempted theft but failed. "Petty theft" means the amount stolen is less than or equal to US$950. “Grand theft" means the amount exceeds $950 [3]. "Others" means thefts that are not specifically classified in the crime data provided by the San Francisco police, such as "Embezzlement from a dependent or elder adult by the caretaker", "Theft of animals", etc. This type only accounts for 0.2% of the total larceny/theft data, so no detailed classification will be conducted in this chart.

<figure>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>Bokeh Plot</title>
    <script type="text/javascript" src="https://cdn.bokeh.org/bokeh/release/bokeh-2.4.3.min.js"></script>
    <script type="text/javascript">
        Bokeh.set_log_level("info");
    </script>
  </head>
  <body>
    <div class="bk-root" id="c735d63c-cfa8-481f-96d2-6fdc7d0ff7e9" data-root-id="1261"></div>
  
    <script type="application/json" id="1451">
      {"fe4dfd6f-4159-46f8-b714-d97eb4c4fc54":{"defs":[],"roots":{"references":[{"attributes":{"axis":{"id":"1274"},"coordinates":null,"dimension":1,"group":null,"ticker":null},"id":"1277","type":"Grid"},{"attributes":{"source":{"id":"1259"}},"id":"1297","type":"CDSView"},{"attributes":{"label":{"value":"OTHERS"},"renderers":[{"id":"1308"}]},"id":"1319","type":"LegendItem"},{"attributes":{},"id":"1267","type":"CategoricalScale"},{"attributes":{"fill_alpha":{"value":0.1},"fill_color":{"value":"#1f77b4"},"hatch_alpha":{"value":0.1},"hatch_color":{"value":"#1f77b4"},"line_alpha":{"value":0.1},"line_color":{"value":"#1f77b4"},"top":{"field":"ATTEMPTED"},"width":{"value":0.8},"x":{"field":"Hour"}},"id":"1295","type":"VBar"},{"attributes":{},"id":"1278","type":"PanTool"},{"attributes":{"fill_alpha":{"value":0.1},"fill_color":{"value":"#1f77b4"},"hatch_alpha":{"value":0.1},"hatch_color":{"value":"#1f77b4"},"line_alpha":{"value":0.1},"line_color":{"value":"#1f77b4"},"top":{"field":"ATTEMPTED"},"width":{"value":0.8},"x":{"field":"Hour"}},"id":"1294","type":"VBar"},{"attributes":{"axis_label":"Normalized LARCENY/THEFT type Count","coordinates":null,"formatter":{"id":"1323"},"group":null,"major_label_policy":{"id":"1324"},"ticker":{"id":"1275"}},"id":"1274","type":"LinearAxis"},{"attributes":{"click_policy":"mute","coordinates":null,"group":null,"items":[{"id":"1317"},{"id":"1318"},{"id":"1319"},{"id":"1320"}],"location":[0,0]},"id":"1316","type":"Legend"},{"attributes":{"overlay":{"id":"1284"}},"id":"1280","type":"BoxZoomTool"},{"attributes":{"coordinates":null,"data_source":{"id":"1259"},"glyph":{"id":"1293"},"group":null,"hover_glyph":null,"muted":true,"muted_glyph":{"id":"1295"},"nonselection_glyph":{"id":"1294"},"view":{"id":"1297"}},"id":"1296","type":"GlyphRenderer"},{"attributes":{"axis_label":"Hour of Day","coordinates":null,"formatter":{"id":"1326"},"group":null,"major_label_policy":{"id":"1327"},"ticker":{"id":"1272"}},"id":"1271","type":"CategoricalAxis"},{"attributes":{"label":{"value":"PETTY_THEFT"},"renderers":[{"id":"1314"}]},"id":"1320","type":"LegendItem"},{"attributes":{"bottom_units":"screen","coordinates":null,"fill_alpha":0.5,"fill_color":"lightgrey","group":null,"left_units":"screen","level":"overlay","line_alpha":1.0,"line_color":"black","line_dash":[4,4],"line_width":2,"right_units":"screen","syncable":false,"top_units":"screen"},"id":"1284","type":"BoxAnnotation"},{"attributes":{"axis":{"id":"1271"},"coordinates":null,"group":null,"ticker":null},"id":"1273","type":"Grid"},{"attributes":{},"id":"1265","type":"DataRange1d"},{"attributes":{"below":[{"id":"1271"}],"center":[{"id":"1273"},{"id":"1277"}],"height":400,"left":[{"id":"1274"}],"renderers":[{"id":"1296"},{"id":"1302"},{"id":"1308"},{"id":"1314"}],"right":[{"id":"1316"}],"title":{"id":"1262"},"toolbar":{"id":"1285"},"width":1000,"x_range":{"id":"1260"},"x_scale":{"id":"1267"},"y_range":{"id":"1265"},"y_scale":{"id":"1269"}},"id":"1261","subtype":"Figure","type":"Plot"},{"attributes":{"fill_color":{"value":"#aec7e8"},"hatch_color":{"value":"#aec7e8"},"line_color":{"value":"#aec7e8"},"top":{"field":"GRAND_THEFT"},"width":{"value":0.8},"x":{"field":"Hour"}},"id":"1299","type":"VBar"},{"attributes":{},"id":"1272","type":"CategoricalTicker"},{"attributes":{"fill_alpha":{"value":0.1},"fill_color":{"value":"#aec7e8"},"hatch_alpha":{"value":0.1},"hatch_color":{"value":"#aec7e8"},"line_alpha":{"value":0.1},"line_color":{"value":"#aec7e8"},"top":{"field":"GRAND_THEFT"},"width":{"value":0.8},"x":{"field":"Hour"}},"id":"1300","type":"VBar"},{"attributes":{},"id":"1275","type":"BasicTicker"},{"attributes":{"coordinates":null,"group":null,"text":"Normalized LARCENY/THEFT type by Hour"},"id":"1262","type":"Title"},{"attributes":{},"id":"1279","type":"WheelZoomTool"},{"attributes":{},"id":"1282","type":"ResetTool"},{"attributes":{},"id":"1327","type":"AllLabels"},{"attributes":{"fill_alpha":{"value":0.1},"fill_color":{"value":"#ff7f0e"},"hatch_alpha":{"value":0.1},"hatch_color":{"value":"#ff7f0e"},"line_alpha":{"value":0.1},"line_color":{"value":"#ff7f0e"},"top":{"field":"OTHERS"},"width":{"value":0.8},"x":{"field":"Hour"}},"id":"1306","type":"VBar"},{"attributes":{"tools":[{"id":"1278"},{"id":"1279"},{"id":"1280"},{"id":"1281"},{"id":"1282"},{"id":"1283"}]},"id":"1285","type":"Toolbar"},{"attributes":{"data":{"ATTEMPTED":{"__ndarray__":"8qo1QCgwnj+uL8Kj0TqdP6EcedUaIJQ/RNqyI8aalD/ml+xxcRWVP12hBTnEKpM/dmhYTsK6kT8LcohVJsCMP9nj4ioqoJ8/dmhYTsK6oT+748vqGLCiP/zxfLUdSKY/sZyEdSOYqj/ml+xxcRWlP2+O06oeAKc/U1q+w84Sqz+aXHOFFuSwPybAHJAVLLA/t3YJGcdStT+BlSBwGFSyP2AOyAoWiLA/C3KIVSbArD/gvWfOzVqqP9A9XC7F4qM/","dtype":"float64","order":"little","shape":[24]},"GRAND_THEFT":{"__ndarray__":"wMg95IKjoj/QCrMImtKYPxk2Sh7rz48/pb2++wKhhD+TfdmvoY55P04jaIETcXo/hbgCDoh0hD8K8tbAXLeMP805VnF2DJg/TCUvCip0nj+LMdzO95ykPxKUx58EKqc/qmE/s2Awqj9ekPL82dOnPxve/feXGKg/gmYLgnjGqD+7Tq7W9h+rP86NSzb9o7A/GYu+fy3ctj/lcvklF9S2P9Tx2RnzbLQ/MtorrgN4sD+4UfT7yJetP0PasMU796c/","dtype":"float64","order":"little","shape":[24]},"Hour":[0,1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,21,22,23],"OTHERS":{"__ndarray__":"vQsr89CotT9LEkNLadeVPwl1AgkheZE/+ONDTnSqiz/TWqKov76AP51AQkheBIA/SxJDS2nXhT/f3YKKpmKUP23kmuI+kaQ/AKlrNRkHqj+UdKt0VpKoPxX44uoHHaU/Cc3vGV8Huz/PTMTP+ZOuP6i8sz3ikqo/rXpsOCTarz9gYboAWO2wP8PJ4+0S8Ko/Lv6jrtVkrD+BLKOrypGmP1LXajIONKQ/WZySGbOQoj9gYboAWO2gP+pZ9H8q8Z4/","dtype":"float64","order":"little","shape":[24]},"PETTY_THEFT":{"__ndarray__":"8nnc8Z+Ooj8drrMk1n6aP+UuGMmXZY0/PBJXvGJ4gz+RtWQHJ6F7P9noJWM+3n0/XLUBomwIhj98kwttzuCQPxYmAQN+Dpw/mleWsFfloj8/Q9e8dyWoP4pVuLoP7qo/iGM/CHjXrz8O/OHYDwKuPzmoy4oIKq8/SSK8/xJZsD+j0uve0L+wP/a9tQLMxrE/+3v1Rs3dsj/iiS2y5c6wPw2/Lj+lEq0/KRysX3DDpz+GJDi6+kCmP15XbqqCpKU/","dtype":"float64","order":"little","shape":[24]}},"selected":{"id":"1329"},"selection_policy":{"id":"1328"}},"id":"1259","type":"ColumnDataSource"},{"attributes":{"source":{"id":"1259"}},"id":"1309","type":"CDSView"},{"attributes":{"fill_color":{"value":"#ff7f0e"},"hatch_color":{"value":"#ff7f0e"},"line_color":{"value":"#ff7f0e"},"top":{"field":"OTHERS"},"width":{"value":0.8},"x":{"field":"Hour"}},"id":"1305","type":"VBar"},{"attributes":{"fill_alpha":{"value":0.1},"fill_color":{"value":"#ff7f0e"},"hatch_alpha":{"value":0.1},"hatch_color":{"value":"#ff7f0e"},"line_alpha":{"value":0.1},"line_color":{"value":"#ff7f0e"},"top":{"field":"OTHERS"},"width":{"value":0.8},"x":{"field":"Hour"}},"id":"1307","type":"VBar"},{"attributes":{},"id":"1269","type":"LinearScale"},{"attributes":{"coordinates":null,"data_source":{"id":"1259"},"glyph":{"id":"1299"},"group":null,"hover_glyph":null,"muted":true,"muted_glyph":{"id":"1301"},"nonselection_glyph":{"id":"1300"},"view":{"id":"1303"}},"id":"1302","type":"GlyphRenderer"},{"attributes":{},"id":"1283","type":"HelpTool"},{"attributes":{},"id":"1323","type":"BasicTickFormatter"},{"attributes":{},"id":"1326","type":"CategoricalTickFormatter"},{"attributes":{"label":{"value":"ATTEMPTED"},"renderers":[{"id":"1296"}]},"id":"1317","type":"LegendItem"},{"attributes":{"fill_alpha":{"value":0.1},"fill_color":{"value":"#ffbb78"},"hatch_alpha":{"value":0.1},"hatch_color":{"value":"#ffbb78"},"line_alpha":{"value":0.1},"line_color":{"value":"#ffbb78"},"top":{"field":"PETTY_THEFT"},"width":{"value":0.8},"x":{"field":"Hour"}},"id":"1313","type":"VBar"},{"attributes":{},"id":"1328","type":"UnionRenderers"},{"attributes":{"coordinates":null,"data_source":{"id":"1259"},"glyph":{"id":"1311"},"group":null,"hover_glyph":null,"muted":true,"muted_glyph":{"id":"1313"},"nonselection_glyph":{"id":"1312"},"view":{"id":"1315"}},"id":"1314","type":"GlyphRenderer"},{"attributes":{"coordinates":null,"data_source":{"id":"1259"},"glyph":{"id":"1305"},"group":null,"hover_glyph":null,"muted":true,"muted_glyph":{"id":"1307"},"nonselection_glyph":{"id":"1306"},"view":{"id":"1309"}},"id":"1308","type":"GlyphRenderer"},{"attributes":{"fill_alpha":{"value":0.1},"fill_color":{"value":"#ffbb78"},"hatch_alpha":{"value":0.1},"hatch_color":{"value":"#ffbb78"},"line_alpha":{"value":0.1},"line_color":{"value":"#ffbb78"},"top":{"field":"PETTY_THEFT"},"width":{"value":0.8},"x":{"field":"Hour"}},"id":"1312","type":"VBar"},{"attributes":{},"id":"1329","type":"Selection"},{"attributes":{"fill_alpha":{"value":0.1},"fill_color":{"value":"#aec7e8"},"hatch_alpha":{"value":0.1},"hatch_color":{"value":"#aec7e8"},"line_alpha":{"value":0.1},"line_color":{"value":"#aec7e8"},"top":{"field":"GRAND_THEFT"},"width":{"value":0.8},"x":{"field":"Hour"}},"id":"1301","type":"VBar"},{"attributes":{"fill_color":{"value":"#1f77b4"},"hatch_color":{"value":"#1f77b4"},"line_color":{"value":"#1f77b4"},"top":{"field":"ATTEMPTED"},"width":{"value":0.8},"x":{"field":"Hour"}},"id":"1293","type":"VBar"},{"attributes":{"fill_color":{"value":"#ffbb78"},"hatch_color":{"value":"#ffbb78"},"line_color":{"value":"#ffbb78"},"top":{"field":"PETTY_THEFT"},"width":{"value":0.8},"x":{"field":"Hour"}},"id":"1311","type":"VBar"},{"attributes":{},"id":"1324","type":"AllLabels"},{"attributes":{"label":{"value":"GRAND_THEFT"},"renderers":[{"id":"1302"}]},"id":"1318","type":"LegendItem"},{"attributes":{},"id":"1281","type":"SaveTool"},{"attributes":{"source":{"id":"1259"}},"id":"1315","type":"CDSView"},{"attributes":{"source":{"id":"1259"}},"id":"1303","type":"CDSView"},{"attributes":{"factors":["0","1","2","3","4","5","6","7","8","9","10","11","12","13","14","15","16","17","18","19","20","21","22","23"]},"id":"1260","type":"FactorRange"}],"root_ids":["1261"]},"title":"Bokeh Application","version":"2.4.3"}}
    </script>
    <script type="text/javascript">
      (function() {
        const fn = function() {
          Bokeh.safely(function() {
            (function(root) {
              function embed_document(root) {
              const docs_json = document.getElementById('1451').textContent;
              const render_items = [{"docid":"fe4dfd6f-4159-46f8-b714-d97eb4c4fc54","root_ids":["1261"],"roots":{"1261":"c735d63c-cfa8-481f-96d2-6fdc7d0ff7e9"}}];
              root.Bokeh.embed.embed_items(docs_json, render_items);
              }
              if (root.Bokeh !== undefined) {
                embed_document(root);
              } else {
                let attempts = 0;
                const timer = setInterval(function(root) {
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
    <figcaption>Figure 3: Interactive bar chart of different types of thefts in San Francisco</figcaption>
</figure>

In this bar chart, you are encouraged to click on different larceny/theft types to see how they change throughout the day. From the chart, we can see that 5:00-7:00 pm is the peak time for Attempted theft, which echoes the information seen in the first chart. There are several influencing factors: (1) High visibility and dense crowds. 5:00-7:00 pm is during the day, which provides better visibility for thieves than at night. In addition, the flow of people during the evening peak hours can provide criminals with opportunities to steal unknowingly. (2) Store operations are busy. During this period, retail stores are usually busy with customers browsing and employees managing inventory, and they are easily tired after a day's work, putting off vigilance, which also allows criminals to take advantage of the chaos to sneak in.

Therefore, staggered hours are a good option for residents, and they should remain vigilant when entering public places during the peak period of theft crime. For store operators, timely shift changes may be a choice to keep staff sensitive to theft, and promptly stop them when theft occurs, reducing incidents such as "Walgreens stores" that have to close in batches due to looting [4]. At the same time, the San Francisco police should improve the prevention of theft crimes during this period by strengthening patrols and shortening response times to crime incidents to reduce residents’ property losses.

The patterns of "Petty theft" and "Attempted" theft are very similar, with both peaking around 5 p.m. Different from them, the peak period of "Grand theft" is after 5 o'clock, concentrated between 5:00-10:00. Among all kinds of grand thefts, the " Grand theft from locked auto" ranks far ahead, which accounts for 56% of the total "Grand theft". Prioritizing and targeting this type of theft would be a good option for San Francisco police to improve their reputation. It is good to hear San Francisco announced a proposed law in October 2023 to make it easier to prosecute car break-in thieves and their police are cracking down on car break-ins using a bait car program meant to catch thieves red-handed [5]. These measures may seem great, but it would be ideal to prevent larceny/theft crimes before they happen and stop them in time when they happen.

To this day, larceny/theft in San Francisco is still the number one crime type that troubles the local police department and residents. The analysis of this article hopes to bring more confidence to local residents in dealing with theft, and also inject more determination into the police department to solve this problem. We remain hopeful for a new San Francisco filled with freedom and security!


## Live Application

The application is live at [Heroku App](https://lit-woodland-17019-4fe9595cf520.herokuapp.com/voila/render/interactive.ipynb?)



## Reference
1. Police Department Incident Reports. "[Police Department Incident Reports](https://data.sfgov.org/browse?category=Public+Safety)"
2. CBS News San Francisco. "[SFNext: Theft, Car Break-ins San Francisco](https://www.cbsnews.com/sanfrancisco/news/sfnext-theft-car-break-ins-san-francisco/?intcid=CNM-00-10abd1h)."
3. Valery Nechay Law. "[San Francisco Theft](https://valerynechaylaw.com/san-francisco-theft/)."
4. CBS News San Francisco. "[Walgreens Retail Theft, Shoplifting San Francisco Civic Center Caught on Camera](https://www.cbsnews.com/sanfrancisco/news/walgreens-retail-theft-shoplifting-san-francisco-civic-center-caught-on-camera/)."
5. The SF Standard. "[San Francisco Car Break-In: New Law to Close Loophole](https://sfstandard.com/2023/10/26/san-francisco-car-break-in-new-law-loophole/)."

