---
date: 2017-04-10T11:00:59-04:00
description: "A comparison of the Uber Dataset and Taxis ranging from ... to ..."
featured_image: "/images/taxi-vs-uber.jpeg"
title: "Comparison Between Uber and Taxis"
---


# PORCACCCIODDDDDDIO

<script type="text/javascript" src="https://cdn.bokeh.org/bokeh/release/bokeh-2.3.0.min.js" integrity="sha384-HjagQp6T0/7bxYTAXbLotF1MLAGWmhkY5siA1Gc/pcEgvgRPtMsRn0gQtMwGKiw1" crossorigin="anonymous"></script>
        <script type="text/javascript">
            Bokeh.set_log_level("info");
        </script>


        
              <div class="bk-root" id="fc98331e-7dcb-425e-bda3-8d0d92b2aa25" data-root-id="1809"></div>
            
          
        
      
      
        <script type="application/json" id="1955">
          {"3a0e2536-0e8c-4049-88f0-36c905812fbe":{"defs":[{"extends":null,"module":null,"name":"DataModel","overrides":[],"properties":[]}],"roots":{"references":[{"attributes":{},"id":"1810","type":"DataRange1d"},{"attributes":{"active_multi":null,"tools":[{"id":"1826"},{"id":"1827"},{"id":"1828"},{"id":"1829"},{"id":"1830"},{"id":"1831"}]},"id":"1833","type":"Toolbar"},{"attributes":{"source":{"id":"1840"}},"id":"1844","type":"CDSView"},{"attributes":{},"id":"1829","type":"SaveTool"},{"attributes":{},"id":"1819","type":"BasicTicker"},{"attributes":{"fill_color":{"value":"#1f77b4"},"line_color":{"value":"#1f77b4"},"x":{"field":"x"},"y":{"field":"y"}},"id":"1841","type":"Circle"},{"attributes":{},"id":"1854","type":"UnionRenderers"},{"attributes":{},"id":"1852","type":"BasicTickFormatter"},{"attributes":{"fill_alpha":{"value":0.1},"fill_color":{"value":"#1f77b4"},"line_alpha":{"value":0.1},"line_color":{"value":"#1f77b4"},"x":{"field":"x"},"y":{"field":"y"}},"id":"1842","type":"Circle"},{"attributes":{},"id":"1826","type":"PanTool"},{"attributes":{"data":{"x":[1,2],"y":[3,4]},"selected":{"id":"1855"},"selection_policy":{"id":"1854"}},"id":"1840","type":"ColumnDataSource"},{"attributes":{"overlay":{"id":"1832"}},"id":"1828","type":"BoxZoomTool"},{"attributes":{"formatter":{"id":"1849"},"major_label_policy":{"id":"1848"},"ticker":{"id":"1823"}},"id":"1822","type":"LinearAxis"},{"attributes":{"data_source":{"id":"1840"},"glyph":{"id":"1841"},"hover_glyph":null,"muted_glyph":null,"nonselection_glyph":{"id":"1842"},"view":{"id":"1844"}},"id":"1843","type":"GlyphRenderer"},{"attributes":{"formatter":{"id":"1852"},"major_label_policy":{"id":"1851"},"ticker":{"id":"1819"}},"id":"1818","type":"LinearAxis"},{"attributes":{"axis":{"id":"1822"},"dimension":1,"ticker":null},"id":"1825","type":"Grid"},{"attributes":{},"id":"1849","type":"BasicTickFormatter"},{"attributes":{"axis":{"id":"1818"},"ticker":null},"id":"1821","type":"Grid"},{"attributes":{},"id":"1823","type":"BasicTicker"},{"attributes":{},"id":"1816","type":"LinearScale"},{"attributes":{},"id":"1814","type":"LinearScale"},{"attributes":{},"id":"1855","type":"Selection"},{"attributes":{},"id":"1831","type":"HelpTool"},{"attributes":{"bottom_units":"screen","fill_alpha":0.5,"fill_color":"lightgrey","left_units":"screen","level":"overlay","line_alpha":1.0,"line_color":"black","line_dash":[4,4],"line_width":2,"right_units":"screen","syncable":false,"top_units":"screen"},"id":"1832","type":"BoxAnnotation"},{"attributes":{},"id":"1812","type":"DataRange1d"},{"attributes":{},"id":"1848","type":"AllLabels"},{"attributes":{},"id":"1827","type":"WheelZoomTool"},{"attributes":{},"id":"1830","type":"ResetTool"},{"attributes":{},"id":"1851","type":"AllLabels"},{"attributes":{},"id":"1846","type":"Title"},{"attributes":{"below":[{"id":"1818"}],"center":[{"id":"1821"},{"id":"1825"}],"left":[{"id":"1822"}],"renderers":[{"id":"1843"}],"title":{"id":"1846"},"toolbar":{"id":"1833"},"x_range":{"id":"1810"},"x_scale":{"id":"1814"},"y_range":{"id":"1812"},"y_scale":{"id":"1816"}},"id":"1809","subtype":"Figure","type":"Plot"}],"root_ids":["1809"]},"title":"Bokeh Application","version":"2.3.0"}}
        </script>
        <script type="text/javascript">
          (function() {
            var fn = function() {
              Bokeh.safely(function() {
                (function(root) {
                  function embed_document(root) {
                    
                  var docs_json = document.getElementById('1955').textContent;
                  var render_items = [{"docid":"3a0e2536-0e8c-4049-88f0-36c905812fbe","root_ids":["1809"],"roots":{"1809":"fc98331e-7dcb-425e-bda3-8d0d92b2aa25"}}];
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