---
date: 2017-04-10T11:00:59-04:00
description: "A comparison of the Uber Dataset and Taxis ranging from ... to ..."
featured_image: "/images/taxi-vs-uber.jpeg"
title: "Comparison Between Uber and Taxis"
---


# PORCACCCIODDDDDDIO


        <script type="text/javascript" src="https://cdn.bokeh.org/bokeh/release/bokeh-2.3.1.min.js" integrity="sha384-YF85VygJKMVnHE+lLv2AM93Vbstr0yo2TbIu5v8se5Rq3UQAUmcuh4aaJwNlpKwa" crossorigin="anonymous"></script>
        <script type="text/javascript">
            Bokeh.set_log_level("info");
        </script>
        
<div class="bk-root" id="92b85e80-03d2-427b-ad81-3846c29da8ac" data-root-id="1149"></div>
            
          
        
      
      
        <script type="application/json" id="1295">
          {"f81e5ef0-3ad7-43fa-8df2-c840c3c1933d":{"defs":[],"roots":{"references":[{"attributes":{"axis":{"id":"1162"},"dimension":1,"ticker":null},"id":"1165","type":"Grid"},{"attributes":{"axis":{"id":"1158"},"ticker":null},"id":"1161","type":"Grid"},{"attributes":{"fill_alpha":{"value":0.1},"fill_color":{"value":"#1f77b4"},"line_alpha":{"value":0.1},"line_color":{"value":"#1f77b4"},"x":{"field":"x"},"y":{"field":"y"}},"id":"1182","type":"Circle"},{"attributes":{},"id":"1194","type":"UnionRenderers"},{"attributes":{},"id":"1159","type":"BasicTicker"},{"attributes":{},"id":"1171","type":"HelpTool"},{"attributes":{},"id":"1152","type":"DataRange1d"},{"attributes":{},"id":"1187","type":"BasicTickFormatter"},{"attributes":{},"id":"1192","type":"AllLabels"},{"attributes":{},"id":"1169","type":"SaveTool"},{"attributes":{},"id":"1154","type":"LinearScale"},{"attributes":{"source":{"id":"1180"}},"id":"1184","type":"CDSView"},{"attributes":{},"id":"1166","type":"PanTool"},{"attributes":{"bottom_units":"screen","fill_alpha":0.5,"fill_color":"lightgrey","left_units":"screen","level":"overlay","line_alpha":1.0,"line_color":"black","line_dash":[4,4],"line_width":2,"right_units":"screen","syncable":false,"top_units":"screen"},"id":"1172","type":"BoxAnnotation"},{"attributes":{},"id":"1190","type":"BasicTickFormatter"},{"attributes":{"formatter":{"id":"1190"},"major_label_policy":{"id":"1192"},"ticker":{"id":"1159"}},"id":"1158","type":"LinearAxis"},{"attributes":{},"id":"1189","type":"AllLabels"},{"attributes":{"below":[{"id":"1158"}],"center":[{"id":"1161"},{"id":"1165"}],"left":[{"id":"1162"}],"renderers":[{"id":"1183"}],"title":{"id":"1185"},"toolbar":{"id":"1173"},"x_range":{"id":"1150"},"x_scale":{"id":"1154"},"y_range":{"id":"1152"},"y_scale":{"id":"1156"}},"id":"1149","subtype":"Figure","type":"Plot"},{"attributes":{},"id":"1150","type":"DataRange1d"},{"attributes":{},"id":"1156","type":"LinearScale"},{"attributes":{"data_source":{"id":"1180"},"glyph":{"id":"1181"},"hover_glyph":null,"muted_glyph":null,"nonselection_glyph":{"id":"1182"},"view":{"id":"1184"}},"id":"1183","type":"GlyphRenderer"},{"attributes":{},"id":"1167","type":"WheelZoomTool"},{"attributes":{},"id":"1193","type":"Selection"},{"attributes":{"overlay":{"id":"1172"}},"id":"1168","type":"BoxZoomTool"},{"attributes":{"data":{"x":[1,2],"y":[3,4]},"selected":{"id":"1193"},"selection_policy":{"id":"1194"}},"id":"1180","type":"ColumnDataSource"},{"attributes":{},"id":"1185","type":"Title"},{"attributes":{},"id":"1163","type":"BasicTicker"},{"attributes":{},"id":"1170","type":"ResetTool"},{"attributes":{"fill_color":{"value":"#1f77b4"},"line_color":{"value":"#1f77b4"},"x":{"field":"x"},"y":{"field":"y"}},"id":"1181","type":"Circle"},{"attributes":{"active_multi":null,"tools":[{"id":"1166"},{"id":"1167"},{"id":"1168"},{"id":"1169"},{"id":"1170"},{"id":"1171"}]},"id":"1173","type":"Toolbar"},{"attributes":{"formatter":{"id":"1187"},"major_label_policy":{"id":"1189"},"ticker":{"id":"1163"}},"id":"1162","type":"LinearAxis"}],"root_ids":["1149"]},"title":"Bokeh Application","version":"2.3.1"}}
        </script>
        <script type="text/javascript">
          (function() {
            var fn = function() {
              Bokeh.safely(function() {
                (function(root) {
                  function embed_document(root) {
                    
                  var docs_json = document.getElementById('1295').textContent;
                  var render_items = [{"docid":"f81e5ef0-3ad7-43fa-8df2-c840c3c1933d","root_ids":["1149"],"roots":{"1149":"92b85e80-03d2-427b-ad81-3846c29da8ac"}}];
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