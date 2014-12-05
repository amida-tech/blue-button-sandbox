---
layout: page
---

# Sandbox

This demo converts each section of a CCD document in XML (CCDA or C32) or CMS document to JSON.

## Source Data

<p>Please don't use real patient data!</p>
<textarea id="xml"></textarea>

<style type="text/css">
  button {
    font-size: 13px;
  }
  textarea {
    width: 100%;
    height: 300px;
    font-size: 14px;
    font-family: 'menlo', monospace;
    white-space: pre;
  }
</style>

Use sample data and convert: <button onclick="load('bb_ref_ccda')">Sample CCDA</button> | <button onclick="convert()">Convert</button> <button onclick="clearAll()">Clear</button>

[Demographics](#demographics-section), [Allergies](#allergies-section), [Plan of Care](#careplan-section), [Encounters](#encounters-section), [Immunizations](#immunizations-section), [Medications](#medications-section), [Problems](#problems-section), [Procedures](#procedures-section), [Results (Labs)](#results-section), [Social History](#social_history-section), [Vitals](#vitals-section), [Payers](#payers-section), [Claims](#claims-section)


<a name="demographics-section"></a>
## Demographics
<pre><code id="demographics" class="javascript"></code></pre>


<a name="allergies-section"></a>
## Allergies
<pre><code id="allergies" class="javascript"></code></pre>


<a name="careplan-section"></a>
## Plan of Care
<pre><code id="careplan" class="javascript"></code></pre>


<a name="encounters-section"></a>
## Encounters
<pre><code id="encounters" class="javascript"></code></pre>


<a name="immunizations-section"></a>
## Immunizations
<pre><code id="immunizations" class="javascript"></code></pre>


<a name="medications-section"></a>
## Medications
<pre><code id="medications" class="javascript"></code></pre>


<a name="problems-section"></a>
## Problems
<pre><code id="problems" class="javascript"></code></pre>


<a name="procedures-section"></a>
## Procedures
<pre><code id="procedures" class="javascript"></code></pre>


<a name="results-section"></a>
## Results (Labs)
<pre><code id="results" class="javascript"></code></pre>


<a name="social_history-section"></a>
## Social History
<pre><code id="social_history" class="javascript"></code></pre>


<a name="vitals-section"></a>
## Vitals
<pre><code id="vitals" class="javascript"></code></pre>


<a name="payers-section"></a>
## Payers
<pre><code id="payers" class="javascript"></code></pre>


<a name="claims-section"></a>
## Claims
<pre><code id="claims" class="javascript"></code></pre>


<script src="bower_components/blue-button-xml/dist/blue-button-xml.js"></script>
<script src="bower_components/blue-button-cms/dist/blue-button-cms.js"></script>
<script src="bower_components/blue-button-generate/dist/blue-button-generate.js"></script>
<script src="bower_components/blue-button/dist/blue-button.js"></script>
