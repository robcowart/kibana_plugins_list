# Kibana Plugins

It isn't always easy to find Kibana plugins, so I wanted to make a list of all of the plugins that I am aware of.

> NOTE: Not all plugins will work with all versions of Kibana. The Kibana plugin interfaces are in a state of constant development. Plugin developers should release a new version of their plugin for each new Kibana release as a result.

> &#11088; Denotes plugins that I have personally found to be very useful.

 Plugin | 5.x | 6.x | Description
--- |:---:|:---:| ---
[aggs-flower](https://github.com/commsart/aggs-flower) | &#10003; |  | Visualisation plugin using d3 forced simulation. Major purpose of this plugin was to provide tools for other plugin developments. This plugin therefore has some interesting features like context menu, filters, dynamic d3 behaviour, 3D effects, node repositioning, etc. while the query handling is pretty basic.
[analyze-api-ui-plugin](https://github.com/johtani/analyze-api-ui-plugin) |  | &#10003; | UI for elasticsearch analyze API
[area3d_vis](https://github.com/JuanCarniglia/area3d_vis) | &#10003; |  | 3D Graph Visualization
[badges-vis](https://github.com/e-ucm/badges-vis) | &#10003; |  | Display badges and achievements.
[bmap](https://github.com/TrumanDu/bmap) |  | &#10003; | A plugin for bmap
&#11088; [cohort](https://github.com/elo7/cohort) | &#10003; | &#10003; | Cohort analysis chart plugin
[computed-columns](https://github.com/seadiaz/computed-columns) | &#10003; |  | Visualization plugin like a table but with computed columns
[country-flag-fieldformatters](https://github.com/nabilbendafi/country-flag-fieldformatters) | &#10003; | &#10003; | Country flag FieldFormat plugin which uses flag-icon-css
[Data-visualization-export](https://github.com/paraponera/Data-visualization-export) |  | &#10003; | A kibana plugin to build a custom table without metrics from the data stored in the ES indexes. It will show all indices in the ES instance, and all columns in the index to build the custom table. The table can be exported as CSV.
[dendrogram_vis](https://github.com/JuanCarniglia/dendrogram_vis) | &#10003; |  | Dendrogram visualization plugin 
[elastalert-kibana-plugin](https://github.com/bitsensor/elastalert-kibana-plugin) |  | &#10003; | Create, test and edit ElastAlert rules within Kibana.
[elastic-ml-alert-plugin](https://github.com/serive/elastic-ml-alert-plugin) |  | &#10003; | Easily create alerts from Machine Learning results.
[enhanced_tilemap](https://github.com/nreese/enhanced_tilemap) | &#10003; |  | Mapping visualization
[kable](https://github.com/lmangani/kibana-kable) |  |  &#10003; | Kable App and Query Language
[kanban_vis](https://github.com/Echolee-L/kanban_vis) | &#10003; |  | A plugin for displaying data by status(or other field).
[kbn_c3js_vis](https://github.com/mstoyano/kbn_c3js_vis) | &#10003; |  | This plugin uses C3JS library (D3-based charts).
[kbn_circles_vis](https://github.com/JuanCarniglia/kbn_circles_vis) |  |  | This is a Circles Packing diagram visType.
[kbn_dashmenu_manager](https://github.com/dlumbrer/kbn_dashmenu_manager) |  | &#10003; | A "metadashboard" manager plugin from Kibana 6
[kbn_dotplot](https://github.com/dlumbrer/kbn_dotplot) |  | &#10003; | dotplot vis for kibana
&#11088; [kbn_network](https://github.com/dlumbrer/kbn_network) | &#10003; | &#10003; | Network graph plugin https://dlumbrer.github.io/kbn_network/
[kbn_percent_nice_vis](https://github.com/JuanCarniglia/kbn_percent_nice_vis) | &#10003; |  | This is a Metric visualization that allows displaying an image to show the % (For instance, 50% equals a half-empty/half-full (depending on your mood) glass of wine).
[kbn_picture_values_vis](https://github.com/JuanCarniglia/kbn_picture_values_vis) | &#10003; |  | This is a Metric visualization that actually goes a little beyond the metric visualization currentyl shipped with Kibana.
[kbn_polar](https://github.com/dlumbrer/kbn_polar) |  | &#10003; | Polar area visualization for Kibana
[kbn_radar](https://github.com/dlumbrer/kbn_radar) |  | &#10003; | Radar visualization for Kibana
[kbn_sankey_vis](https://github.com/uniberg/kbn_sankey_vis) | &#10003; | &#10003; | A Sankey Visualization
[kbn_searchtables](https://github.com/dlumbrer/kbn_searchtables) | &#10003; | &#10003; | Build tables and search with an input without applying filters.
[kbn_sunburst_vis](https://github.com/JuanCarniglia/kbn_sunburst_vis) |  |  | This is a Sunburst diagram visType
[keycloak-kibana](https://github.com/novomatic-tech/keycloak-kibana) | &#10003; | &#10003; | A Keycloak authorization plugin for Kibana.
[kibana-advanced-bytes-plugin](https://github.com/MaxxtonGroup/kibana-advanced-bytes-plugin) | &#10003; |  | Extension of the original bytes field format.
&#11088; [kibana_calendar_vis](https://github.com/aaronoah/kibana_calendar_vis) |  | &#10003; | This plugin gives a calendar heatmap visualization in Kibana Visualize app.
[kibana-chord](https://github.com/datavis-tech/kibana-chord) |  |  | A Chord Diagram visualization
[kibana-clock-vis-plugin](https://github.com/gmatheus/kibana-clock-vis-plugin) |  | &#10003; | Clock visualization
&#11088; [kibana-comments-app-plugin](https://github.com/gwintzer/kibana-comments-app-plugin) | &#10003; | &#10003; | Add comment annotations to your Kibana dashboards.
[kibana-d3-sankey](https://github.com/ReneU/kibana-d3-sankey) |  | &#10003; | Sankey Visualization
[kibana-datepicker-plugin](https://github.com/C3SL/kibana-datepicker-plugin) |  | &#10003; | This Plugin includes a new Visualization in Kibana to pick date, similar to Kibana's absolute timepicker.
&#11088; [kibana-datasweet-formula](https://github.com/datasweet-fr/kibana-datasweet-formula) | &#10003; | &#10003; | Allows calculated metrics on any standard kibana visualizations.
[kibana_diagram](https://github.com/lmangani/kibana_diagram) |  | &#10003; | Experimental Flow Diagram Vis.
&#11088; [kibana-enhanced-table](https://github.com/fbaligand/kibana-enhanced-table) | &#10003; | &#10003; | Kibana visualization like a Data Table, but with enhanced features like computed columns and filter bar.
[kibana-esri-heatmap](https://github.com/ReneU/kibana-esri-heatmap) |  | &#10003; | Heatmap Visualization Plugin
[kibana_ext_metrics_vis](https://github.com/ommsolutions/kibana_ext_metrics_vis) | &#10003; |  | Based on the core Metric-Plugin but gives you the ability to output custom aggregates on metric-results by using custom formula and/or JavaScript.
[kibana-fixed-filter](https://github.com/gwintzer/kibana-fixed-filter) |  | &#10003; | A plugin to fix the position of the dashboard filter element at the top of viewport when you scroll.
[kibana-gdpr-plugin](https://github.com/gingerwizard/kibana-gdpr-plugin) |  | &#10003; | A GDPR plugin for cookie acceptance and privacy link.
&#11088; [kibana_graph](https://github.com/lmangani/kibana_graph) | &#10003; | &#10003; | Interactive Network Graph Visualization.
[kibana_health_metric_vis](https://github.com/clamarque/kibana_health_metric_vis) | &#10003; |  | Plugin to change the color of the metric depending on the state of health.
[kibana-html-plugin](https://github.com/raystorm-place/kibana-html-plugin) | &#10003; |  | HTML visualization plugin
[kibana-html-plugin-6.1.1](https://github.com/jaydabhi17/kibana-html-plugin-6.1.1) |  | &#10003; | HTML plugin for Kibana 6.1.1
[kibana-iframe-communicator-plugin](https://github.com/bondib/kibana-iframe-communicator-plugin) | &#10003; |  | A plugin to demonstrate how one can communicate directly with Kibana hosted inside an IFrame, without the need to reload the iframe.
[kibana-logbrowser](https://github.com/searchtechnologies/kibana-logbrowser) | &#10003; |  | The Search Technologies Log Browser
[kibana_markdown_doc_view](https://github.com/sw-jung/kibana_markdown_doc_view) | &#10003; | &#10003; | A plugin for custom doc view using markdown+handlebars template.
[kibana_notification_center](https://github.com/sw-jung/kibana_notification_center) | &#10003; | &#10003; | This plugin helps you to use Kibana's notifications more usefully.
[kibana-object-format](https://github.com/istresearch/kibana-object-format) | &#10003; | &#10003; | This plugin enables you to configure field formatters for arrays of objects in the Discover tab and Search tables in dashboards.
[kibana-pivot-table](https://github.com/datavoyagerhk/kibana-pivot-table) | &#10003; |  | Pivot tables are interactive tables that allow the user to group and summarize large amounts of data in a concise. Basically a wrapper of Nicolas Kruchten's Pivot Table.
[kibana-plugin-gauge-sg](https://github.com/sbeyn/kibana-plugin-gauge-sg) | &#10003; |  |A gauge plugin
[kibana-plugin-metric-percent](https://github.com/amannocci/kibana-plugin-metric-percent) | &#10003; |  | The visualization displays a percent number based on a global number and various values.
[kibana-prometheus-exporter](https://github.com/pjhampton/kibana-prometheus-exporter) |  | &#10003; | Prometheus metrics for Kibana
[kibana-search-widget](https://github.com/michimau/kibana-search-widget) |  | &#10003; | A search bar visualization for use on iframe embedded dashboards.
[kibana-slider-plugin](https://github.com/raystorm-place/kibana-slider-plugin) | &#10003; |  | Slider input control plugin
&#11088; [kibana-swimlane-vis](https://github.com/prelert/kibana-swimlane-vis) | &#10003; | &#10003; | The original Prelert Swimlane Visualization! |
&#11088; [kibana-vega-vis](https://github.com/nyurik/kibana-vega-vis) | &#10003; | &#10003; | Allows any data visualizations from Elasticsearch and other data sources using Vega grammar. You can even create a visualization on top of an interactive map.
&#11088; [kibana-vis-dropdown](https://github.com/robcowart/kibana-vis-dropdown) | &#10003; |  | A dropdown visualization which allows users to set filters from a list of values.
[kibana_vis_gantt](https://github.com/sasauz/kibana_vis_gantt) | &#10003; |  | Gantt Chart plugin.
[kibana-vis-timeline](https://github.com/ReneU/kibana-vis-timeline) |  | &#10003; | Timeline Visualization
[kibana-viz-clock](https://github.com/MichalHecko/kibana-viz-clock) | &#10003; |  | Digital clock visualization plugin
[kibana-xlsx-import](https://github.com/kyushy/kibana-xlsx-import) | &#10003; | &#10003; | Kibana plugin for import XLSX/CSV file to ElasticSearch
[KibanaNestedSupportPlugin](https://github.com/ppadovani/KibanaNestedSupportPlugin) | &#10003; |  | Adds support for nested field search and aggregation.
[kibi_radar_vis](https://github.com/sirensolutions/kibi_radar_vis) | &#10003; |  | A Radar (or Spider) Chart plugin.
[kibi_timeline_vis](https://github.com/sirensolutions/kibi_timeline_vis) | &#10003; |  | The plugin displays a timeline of events taken from multiple saved searches.
[logtrail](https://github.com/sivasamyk/logtrail) | &#10003; | &#10003; | View, search & live tail log events
&#11088; [mapster](https://github.com/OmniCyberSecurity/mapster) | &#10003; | &#10003; | Live events map. Mapster is not truely in real-time. It fetches the events from ElasticSearch using Kibana and replays the events in real time with a lag corresponding to the Kibana refresh time.
[mathlion](https://github.com/fermiumlabs/mathlion) | &#10003; |  | Mathlion is an advanced math plugin for Kibana's Timelion http://mathlion.docs.fermiumlabs.com
[ob-kb-funnel](https://github.com/outbrain/ob-kb-funnel) | &#10003; |  | Visualization plugin for displaying a funnel Based on D3 Funnel lib
[ob-kb-percent](https://github.com/outbrain/ob-kb-percent) | &#10003; | &#10003; | Visualization plugin for displaying a single ratio (percent) metric. Customize the numerator and denominator of the calculation.
[radial_heatmap](https://github.com/JacobBrandt/radial_heatmap) | &#10003; |  | Used to render cyclical data.
[searchbox](https://github.com/zumo64/searchbox) | &#10003; | &#10003; | Search Tool Kibana Plugin
&#11088; [sentinl](https://github.com/sirensolutions/sentinl) | &#10003; |  | Kibi + Kibana Alert & Report App for Elasticsearch.
[timeline_heatmap](https://github.com/JacobBrandt/timeline_heatmap) | &#10003; |  | A visualization that uses swimlanes to visualize multiple sources over time. Each swimlane represents a source and the intervals of the date histogram are colored based on the metric defined at the given time.
[timelion-influxdb](https://github.com/lmangani/timelion-influxdb) |  | &#10003; | Experimental InfluxDB plugin for Timelion.
[timelion-prometheus](https://github.com/lmangani/timelion-prometheus) |  | &#10003; | Experimental Prometheus plugin for Timelion.
[tk-kibana-vis](https://github.com/e-ucm/tk-kibana-vis) | &#10003; |  | Thomas Kilmann Classification visualization.
[topology](https://github.com/bahaaldine/topology) | &#10003; |  | Plugin to explore Elasticsearch Topology
