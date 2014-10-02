<html xmlns="http://www.w3.org/1999/xhtml">
<head>
    <title>PeopleSoft 8 Sensor Pack</title>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8"/>
    <meta http-equiv="X-UA-Compatible" content="IE=EmulateIE8" />
    <meta content="Scroll Wiki Publisher" name="generator"/>
    <link type="text/css" rel="stylesheet" href="css/blueprint/liquid.css" media="screen, projection"/>
    <link type="text/css" rel="stylesheet" href="css/blueprint/print.css" media="print"/>
    <link type="text/css" rel="stylesheet" href="css/content-style.css" media="screen, projection, print"/>
    <link type="text/css" rel="stylesheet" href="css/screen.css" media="screen, projection"/>
    <link type="text/css" rel="stylesheet" href="css/print.css" media="print"/>
</head>
<body>
                <h1>PeopleSoft 8 Sensor Pack</h1>
    <div class="section-2"  id="4849980_PeopleSoft8SensorPack-Overview"  >
        <h2>Overview</h2>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Name    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<strong class=" ">PeopleSoft 8 Sensor Pack</strong>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Description    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
This Knowledge Sensor Pack can be used to help quantify and diagnose performance issues related to PeopleSoft and Jolt specific code.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Version    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
1.0    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
dynaTrace Diagnostics Version    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
2.5 and higher    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Author    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Eric.Horsman@dynatrace.com    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
License    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_5275722_2_dynaTraceBSD.txt">dynaTrace BSD</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Support    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="https://community/display/DL/Support+Levels">Not Supported</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Download    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_5275755_1_dynaTrace_Peoplesoft8KSP_v1.0.zip">dynaTrace_Peoplesoft8KSP_v1.0.zip</a>    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
    <div class="section-2"  id="4849980_PeopleSoft8SensorPack-Installation"  >
        <h2>Installation</h2>
<ol class=" "><li class=" ">    <p>
Save the attached file locally to the computer where the dynaTrace Diagnostics Client is installed.    </p>
</li><li class=" ">    <p>
Unzip the file.    </p>
</li><li class=" ">    <p>
In the dynaTrace Diagnostics Client, right-click on the Diagnostics Server and select 'Preferences...'.    </p>
</li><li class=" ">    <p>
Click on &quot;Sensor Packs&quot;.    </p>
</li><li class=" ">    <p>
Click on the &quot;Import...&quot; button.    </p>
</li><li class=" ">    <p>
Select &quot;Custom Sensor Type (*.dtdcs)&quot; in the &quot;Files of type&quot; dropdown.    </p>
</li><li class=" ">    <p>
Navigate to the directory where you extracted the .dtdcs file and click &quot;Open&quot;.    </p>
</li></ol>    <p>
You can confirm successful import by observing the PeopleSoft Sensor Pack in the Sensor Packs Panel. This Knowlege Sensor Pack is now <i class=" ">Placed</i> and <i class=" ">Active</i> within all System Profiles on this Diagnostics Server.    </p>
    <p>
Exercise the PeopleSoft 8 application.    </p>
    <p>
To further understand the usage and user activities in context to PeopleSoft, specific Servlet attributes can be captured. To do so, follow these steps:    </p>
<ol class=" "><li class=" ">    <p>
Right Click on the configuration in which you wish to add Servlet attributes and select &quot;Properties...&quot;.    </p>
</li><li class=" ">    <p>
In the left hand panel expand/select &quot;All Agents&quot; or the specific Application Instance that pertains to PeopleSoft.    </p>
</li><li class=" ">    <p>
Select &quot;Sensor Configuration&quot;.    </p>
</li><li class=" ">    <p>
Find the &quot;Servlets&quot; Sensor Pack in the &quot;Sensor Configuration&quot; list.    </p>
</li><li class=" ">    <p>
Click on&quot;Properties&quot; in the &quot;Options&quot; column.    </p>
</li><li class=" ">    <p>
Within the &quot;Configure Sensor Properties&quot; dialog, click on the &quot;Add&quot; button below the &quot;Attribute Capturing&quot; section (lower half).    </p>
</li><li class=" ">    <p>
A new entry will appear under the &quot;Source&quot; column in the &quot;Attribute Capturing&quot; list. Select &quot;Parameter&quot; from the drop down if it is not already selected.    </p>
</li><li class=" ">    <p>
Type the term &quot;Page&quot; in the corresponding &quot;Query&quot; column    </p>
</li><li class=" ">    <p>
You have now added the &quot;Page&quot; parameter. Follow steps 6-8 to add the following additional parameters:    </p>
<ul class=" "><li class=" ">    <p>
FolderRef    </p>
</li><li class=" ">    <p>
PortalActualURL    </p>
</li><li class=" ">    <p>
cmd    </p>
</li><li class=" ">    <p>
PanelGroupName    </p>
</li><li class=" ">    <p>
Menu    </p>
</li><li class=" ">    <p>
menugroup    </p>
</li><li class=" ">    <p>
ICType    </p>
</li><li class=" ">    <p>
ICScripProgramName    </p>
</li></ul></li><li class=" ">    <p>
Select OK.    </p>
</li></ol>    <p>
If you have followed the steps correctly, your Servlet Sensor Properties screen should look like this:    </p>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
            <img src="images_community/download/attachments/4849980/PeopleSoft8_Servlet_Parameters.jpg" alt="images_community/download/attachments/4849980/PeopleSoft8_Servlet_Parameters.jpg" class="confluence-embedded-image" />
            </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
    <p>
You will need to deploy this change into your application by either performing a Hot Sensor Placement or restarting your Application.    </p>
    <p>
Note ** - Some of these parameters may not be valuable to all PeopleSoft deployments, Please remove unnecessarily parameters after usage depicts the value of capturing each parameter.    </p>
    <div class="tablewrap">
        <table>
<thead class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
&nbsp;    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="PeopleSoft_8_Sensor_Pack.html">File</a>    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="PeopleSoft_8_Sensor_Pack.html">Modified</a>    </p>
            </td>
        </tr>
</thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
                </td>
                <td rowspan="1" colspan="1">
        <p>
ZIP Archive                    <a href="https://community/download/attachments/4849980/dynaTrace_Peoplesoft8KSP_v1.0.zip?api=v2">dynaTrace_Peoplesoft8KSP_v1.0.zip</a>PeopleSoft 8 KSP v1.0    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Jun 21, 2008by<a href="    /community/display/~ted.feyler@compuware.com ">Ted Feyler</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
                </td>
                <td rowspan="1" colspan="2">
        <p>
    </p>
    <p>
Labels    </p>
<ul class="label-list has-pen "><li class="no-labels-message ">    <p>
No labels    </p>
</li><li class="labels-edit-container ">    <p>
<a href="PeopleSoft_8_Sensor_Pack.html">Edit Labels</a>    </p>
</li></ul>    <p>
    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
<ul class=" "><li class="drop-zone-text hidden ">    <p>
Drag and drop to upload or browse for files    </p>
            <img src="images_community/images/icons/wait.gif" alt="images_community/images/icons/wait.gif" class="plugin_attachments_dropzone_uploadwaiticon" />
        </li></ul>    <p>
Upload fileFile description    </p>
    </div>
            </div>
        </div>
        <div class="footer">
        </div>
    </div>
</body>
</html>
