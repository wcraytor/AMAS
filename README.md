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

<li>The GitHub libraries will be split between Runtime Binaries and Open Source.<br>
    <ul><br>
      <li>Runtime Binaries will be available to appraisers and others who wish to test the code, or use it in their work.</li><br>
      <li>Open Source libraries will be available to developers and will be split between Core Infrastrcture and User Interace. <br>
         <ul>
          <li>Core Infrastructure code will be available to contributing developers.  Core infrastructure code will be independent of DevExpress and other third party library requiring paid license fees.</li><br>
          <li>DevExpress will be used for complex user interfaces in many if not most cases.  The DevExpress libraries for such code will not be uploaded due to license restrictions.  That is to say, developers will have to download  DevExpress libaries based on their own license.</li><br>
          <li>Other User Interface code should be based on open source libraries and will be available to all developers.<br>
         </ul>
        </li>
      </ul>
<br>
<li>Note that DevExpress licensing restrictions will not affect appraisers and other users, who simply want to run the code for testing or use in their work.</li><br>
  
<li style="margin:0;padding:0">Core Infrastructure code will include the Model Parsers, Domain Definitions, and other code not related to supporting a user interface. </li><br>
  
<li>Core code will be migrated as soon as possible (if not initially) to AspNet Core - so that it can run on Linux and Mac, as well as on Windows.</li><br>



<li>  Developers can added User Interface code based on other software and utilities, if approved.</li><br>

<li>  DevExpress/WPF will be used for the desktop interface.</li><br>

<li>  DevExpress Asp.Net/MVC + DevExtreme for the browser interface.</li><br>

<li> Migration to AspNet Core will occur in parallel.  This will allow the software to be used on Linux and MAC operating systems.</li><br>
</ol>


