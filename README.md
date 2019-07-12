
Modified version of the resource library described below
===

First of all, I did not make this library. I only forked the library and want to make it clear all I did was modify one file.

The only piece I used was the obiee.js file that I added a new method called executeReport to along with a new method for formatting the reportparams.

I am not an OBIEE developer but a Siebel developer who wanted to used OpenUI to call OBIEE reports and get the data back to display in the UI with ChartJS.

So the visualization part was not used, just the obiee.js file.

Insights - An Open-Source Visualisation Platform for OBIEE
===

Insights is an add-on for [OBIEE](http://www.oracle.com/technetwork/middleware/bi-enterprise-edition/overview/index.html) providing a customisable UI framework that allows you to build front end web applications that interface with the OBI back end.

Specifically, there's a visualisation builder and dashboard viewer that has been built using this framework and provides many UI features not present in the standard application.

To deploy the application please follow the [installation guide](https://github.com/RittmanMead/insights/wiki/Installation-Guide). Technical information can be found in the [wiki](https://github.com/RittmanMead/insights/wiki) for this project.

Note that Insights is only compatible with IE11, Chrome browsers and with OBIEE 11.1.1.9 and higher. Specific compatibility can be found in the [technical guide](https://github.com/RittmanMead/insights/wiki/Technical-Overview).
