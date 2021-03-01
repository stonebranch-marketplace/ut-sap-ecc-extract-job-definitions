# ut-sap-ecc-extract-job-definitions
<p>This Universal Task allows you to export SAP Job definitions from SAP into one flat file for each Job selected for extraction. The Jobs definitions to extract from SAP are provided in a CSV input file saved in the Universal Controller script library. For each Job to extract the SAP Jobname and SAP Job count ID needs to be provided in the input file.</p>
<p><span data-preserver-spaces="true">The extracted SAP Job definition files can be read by the Stonebranch Conversion Tool (CTK), which transitions each read Job definition file into an SAP Task. If the SAP Job was in status Released, meaning Start conditions had been defined in SAP for that Job, then automatically a time trigger with the scheduling criteria will be created by the transition tool. As a result, the transitioned SAP Task is ready to be scheduled in the same way as in SAP.</span></p>
<h3><strong>Key Features</strong></h3>
<ul>
<li><span data-preserver-spaces="true">Export SAP Job definitions from SAP into one flat file for each SAP Job</span></li>
<li><span data-preserver-spaces="true">Any defined start criteria will be exported for SAP each Job</span></li>
<li><span data-preserver-spaces="true">Jobs to be extracted can be in any Status (SCHEDULED, RELEASED, CANCELED, FINISHED, etc.)</span></li>
<li><span data-preserver-spaces="true">The Jobs to be extracted are provided via a list saved in the Universal Controller script library</span></li>
<li><span data-preserver-spaces="true">A detailed log file will be provided after each extraction process to identify Jobs that could not be found in SAP e.g. a Jobname has been provided in the input file, which does not exist in the SAP System</span></li>
<li><span data-preserver-spaces="true">The extracted SAP Job definition files can then read by the Stonebranch Conversion Tool (CTK), which transitions each read Job definition file into an SAP Task incl. defined Start criteria</span></li>
<li><span data-preserver-spaces="true">Support for Application Server Connection and Destination Connection (nwrfc.ini) e.g. Load Balancer connections, SAP SNC, etc.</span></li>
</ul>
<p><span data-preserver-spaces="true">&nbsp;</span></p>

<p>&nbsp;</p>
Please visit this link to find key features, prerequisites, installation instructions, configuration instructions, and examples of how to use this integration. 
<a href="https://docs.stonebranch.com/confluence/display/UC69/UAC+-+SAP+Extract+Job+Definitions">UAC - SAP Extract Job Definitions</a>.&nbsp;</li>

