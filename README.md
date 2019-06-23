# AMAS
Appraisal Model Adjustment Standard

This website is for research and development of a standard for specifying appraisal models based on a common and openly available language that can incorporate, initially, the output models of Salford Systesms (MiniTab) MARS(t) and R-Language Earth.   Models expressed in this standard can be uploaded in to appraisal software tools which support the standard and these tools will then parse the model into individual feature adjustment code which they can execute to make the adjustments between sales comparables and the subject property.

Please contact William Bert Craytor if you are interested in participating:

William Bert Craytor

Email:  bert@PacificVista.net
Pacific Vista Net
242 Clifton Rd
Pacifica, CA 94044
Phone: 650-880-0790

 

## ROADMAP

<ol style="margin:0;padding:0">
<li style="margin:0;padding:0">  Clean, comment, update and check-in my existing ANTLR/C# parser for Salford Systems MARS(t) models, generating Excel macros and Sales Comparable spreadsheets.</li><br>

<li style="margin:0;padding:0">  Add R-Earth model uploading.</li><br>

<li> Upload UML designs.</li><br>

<li>  Add tests.</li><br>

<li>  Make improvements.</li><br>
</ol>

## CAVEATS (Developers)

<ol style="margin:0;padding:0">

<li>The GitHub libraries will be split between Runtime Binaries and Open Source.  The Open Source libraries will be split between Core Infrastrcture and User Interace.</li></br>

<li>DevExpress will be used for complex user interfaces in many if not most cases. This means that developer access to any code that incorporates DevExpress libraries, will require the developer have a license for DevExpress. Core infrastructure code will be independent of DevExpress and other third party library requiring paid license fees.</li><br> 

<li>The above restriction will not affect appraisers and other users, who simply want to run the code for testing or use in their work.</li><br>
  
<li style="margin:0;padding:0">Consequently, code will be cleanly split between supporting infrastructure (domain, parsing, RabbitMQ messaging, ...) code and User Interface code requiring a DevExpress license. There will be separate user access for each set of libraries. </li><br>
  
<li>Core code will be migrated as soon as possible (if not initially) to AspNet Core - so that it can run on Linux and MAC, as well as on Windows.</li><br>



<li>  Developers can added User Interface code based on other software and utilities, if approved.</li><br>

<li>  DevExpress/WPF will be used for the desktop interface.</li><br>

<li>  DevExpress Asp.Net/MVC + DevExtreme for the browser interface.</li><br>

<li> Migration to AspNet Core will occur in parallel.  This will allow the software to be used.</li><br>
</ol>


