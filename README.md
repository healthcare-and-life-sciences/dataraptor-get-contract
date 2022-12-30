![](images/ahlsbanner.png)
<h1 id='RbXACA01blL'>A-HLS - DataRaptor Library Documentation - DRgetContract</h1>

<i>This DataRaptor acts as a base for developers to get information about a Contract.</i><br/>

<hr style='width:100%'><h2 id='RbXACA8G9bk'>Overview</h2>

A DataRaptor is a mapping tool to help read, transform, and write Salesforce data. There are four types of DataRaptors: <span style="color:#1e1e1c" textcolor="#1e1e1c">Turbo Extract, Extract, Load, and Transform. You can use these four methods to extract data for digital customer interactions and business processes to present data. </span><br/>

<br/>

This DataRaptor Extract collects meaningful information about a specific ‘Contract,’ making it available for display or further use in an OmniScript.<br/>

<hr style='width:100%'><h2 id='RbXACApZ1wl'>Business Objective</h2>

The Business objective is to quickly extract information about a specific ‘Contract’ that can be meaningful to achieve the jobs to be done for a business user or reporting.<br/>

<h2 id='RbXACAJVPQq'><span style="color:#333333" textcolor="#333333">Business Value and Benefits</span></h2>

<div style="" class="" data-section-style='5'><ul id='temp:C:RbXeba407850d644673b4c30a773'><li id='temp:C:RbXc3a6a2fdb31f47598a5245c89' class='' value='1'><span style="color:#0e101a" textcolor="#0e101a">Decrease IT costs associated with custom build</span>

<br/></li><li id='temp:C:RbX8de271a32aed47018b9d03dd7' class=''>Improve user experience

<br/></li></ul></div><hr style='width:100%'><h2 id='RbXACAtkCdC'>Export-Package Includes</h2>

<h3 id='RbXACA0x5k0'><b>DataRaptor (1)</b></h3>

<div style="" class="" data-section-style='5'><ul id='RbXACAm36p4'><li id='RbXACA4Dn5w' class='' value='1'>DRgetContract

<br/></li></ul></div><h2 id='RbXACAqXo2I'><b>JSON Reference</b></h2>

<div style="" class="" data-section-style='5'><ul id='RbXACAgW5xV'><li id='RbXACAzfqzt' class='' value='1'>{<br>  "Contract": {<br>    "EndDate": "2021-05-04",<br>    "StartDate": "2020-05-04",<br>    "ContractTerm": 12,<br>    "AccountId": "0015f000006mp5VAAQ",<br>    "Name": "Test2",<br>    "Id": "8005f000000Jk5HAAS"<br>  }<br>}

<br/></li></ul></div><hr style='width:100%'><h2 id='RbXACAoVPZS'>Configuration Requirements</h2>

<div style="" class="" data-section-style='5'><ul id='RbXACAC5fac'><li id='RbXACAcQpLB' class='' value='1'>The Data Raptor is ready to be imported and customized. No further base configuration requirements are necessary.

<br/></li></ul></div><h3 id='RbXACAXXAbW'>Installation Instructions:</h3>

The following steps are required for installation.<br/>

<h4 id='RbXACAWB3gU'>Install the Data Pack</h4>

<div style="" class="" data-section-style='6'><ul id='RbXACAdUAMa'><li id='RbXACAEGIEA' class='' value='1'>The Data Pack folder in the following GitHub repository contains one (1) DPA Data Pack. Please download the Data Pack and save them to your desktop: <a href="https://github.com/HLS-Accelerate/DataRaptor-Library/tree/main/DRgetContract">https://github.com/HLS-Accelerate/DataRaptor-Library/tree/main/DRgetContract</a>

<br/></li><li id='RbXACADLZl1' class='parent'>Then, complete the following steps to import them into your Salesforce org.

<br/></li><ul><li id='RbXACAzYxpv' class=''>To Import, in your destination Salesforce org, Click on <b>App Launcher</b> → Search for '<b>OmniStudio DataPacks</b>' and click on it.

<br/></li><li id='RbXACAqzGLc' class=''>Click on '<b>Installed</b>' and on the right side click on '<b>Import from</b>'.

<br/></li><li id='RbXACAov0QI' class=''>Select '<b>From File</b>' - When the window opens, select the Data Pack file that you downloaded and stored on your machine. Click '<b>Install</b>'.

<br/></li></ul><li id='RbXACAELy8H' class=''>More about DataRaptors: <a href="https://trailhead.salesforce.com/content/learn/modules/omnistudio-dataraptors">https://trailhead.salesforce.com/content/learn/modules/omnistudio-dataraptors</a>

<br/></li></ul></div><hr style='width:100%'><h2 id='RbXACAXW5HB'><span style="color:#333333" textcolor="#333333">Assumptions</span></h2>

<div style="" class="" data-section-style='5'><ul id='RbXACA9cfjy'><li id='RbXACAbEhVF' class='' value='1'>A customer has licenses for Health Cloud and the HINS Managed Package with OmniStudio. These solutions have all been installed and are functional.

<br/></li><li id='RbXACAKRk45' class=''>A customer is assuming Salesforce Lightning Experience — not Classic.

<br/></li><li id='RbXACAlqry4' class=''>Data Model elements that are part of the HINS (Vlocity) Managed package and Health Cloud are available.

<br/></li><li id='RbXACAsfS50' class=''>The Accelerator uses the Lightning Design System standards and look. Customers may want to apply their branding.

<br/></li></ul></div><h2 id='RbXACAw7d9O'>Installed Packages Requirement</h2>

<div style="" class="" data-section-style='5'><ul id='RbXACA5z9JJ'><li id='RbXACAon6Ip' class='' value='1'>HealthCloud (HealthCloudGA) - Version 236.1 or higher

<br/></li><li id='RbXACAUprQN' class=''>Vlocity Insurance (vlocity_ins) - Version 890.317 or higher

<br/></li></ul></div><hr style='width:100%'><h2 id='RbXACAHN5iS'>Revision History</h2>

<div style="" class="" data-section-style='5'><ul id='RbXACAfFQp0'><ul><li id='RbXACAk4w5t' class='parent' value='1'><b>Revision Short Description (May 12, 2022)</b>

<br/></li><ul><li id='RbXACA6CqgY' class=''>Error correction from previous versions to adapt to the new Data Model.

<br/></li><li id='RbXACAsbLEK' class=''>Initial export with QA.

<br/></li></ul><li id='RbXACAYiVH7' class='parent'><b>Revision Short Description (June 21, 2022)</b>

<br/></li><ul><li id='RbXACAZACtm' class=''>Updated Documentation.
