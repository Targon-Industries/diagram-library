# diagram-library
A JavaScript + CSS library for web development to create simple diagrams.

# How to use
You can add the library to your project by inserting the following script tag:

```
<script src="https://targoninc.com/diagrams/diagrams.js"/>
```

To use all features of the library, it is recommended to use the following code:

```
<div class="settingbox diagram">
    <input type="checkbox" name="showPercentiles" id="showPercentiles" style="margin: 0;" checked>
    <label for="showPercentiles">Show percentiles</label>
    <input type="checkbox" name="showAverages" id="showAverages" style="margin: 0;" checked>
    <label for="showAverages">Show averages</label>
</div>
<details class="diagram" open>
    <summary class="diagram">Summary</summary>
    <div id="someStatistics" class="diagram_container">
    </div>
</details>
```

This will work well with the provided CSS and enable you to make use of the analytic features, like percentiles and averages. You could disable the display on the settings box to hide it from the user. 