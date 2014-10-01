<html xmlns="http://www.w3.org/1999/xhtml">
<head>
    <title>JBoss 7 Datasource Monitoring Plugin</title>
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
                <h1>JBoss 7 Datasource Monitoring Plugin</h1>
    <div class="section-2"  id="120128668_JBoss7DatasourceMonitoringPlugin-Overview"  >
        <h2>Overview</h2>
    <p>
            <img src="images_community/download/attachments/120128668/icon.png" alt="images_community/download/attachments/120128668/icon.png" class="confluence-embedded-image" />
            </p>
    <p>
Starting &quot;Jboss 7&quot; or &quot;Jboss EAP 6&quot;, Jboss has stopped the support for exposing connection pool statistics via JMX beans. If you want to use the dynaTrace JMX based measure to monitor your datasource usage/statistics you wont be able to do so.This plugin will help you capture the datasource statistics in &quot;Jboss 7&quot; or &quot;Jboss EAP 6&quot; using the new REST based Jboss management console. Once you capture the measure you can chart on the data.    </p>
    <p>
Here is a screen shot of a dashboard, which monitors the active Connection on individual data-sources.    </p>
    <p>
    </p>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
            <img src="images_community/download/attachments/120128668/DataSource.JPG" alt="images_community/download/attachments/120128668/DataSource.JPG" class="" />
            </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
                </td>
        </tr>
</tbody>        </table>
            </div>
    <p>
    </p>
    </div>
    <div class="section-2"  id="120128668_JBoss7DatasourceMonitoringPlugin-PluginDetails"  >
        <h2>Plugin Details</h2>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Plug-In Versions    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_120422520_1_com.jboss7.ds.statistics_1.0.0.jar">JBoss 7 Datasource Monitoring Plugin</a> (compatible with dynaTrace 4.2+)    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Author    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Muthu Madialagan    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Download    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_120422520_1_com.jboss7.ds.statistics_1.0.0.jar">com.jboss7.ds.statistics_1.0.0.jar</a>    </p>
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
<a href="https://community/display/DL/Support+Levels#SupportLevels-Community">Not Supported </a><br/>If you have any questions or suggestions for these plugins, please add a comment to this page, use our <a href="https://community.dynatrace.com/community/pages/viewpage.action?pageId=46628918">forum</a>, or drop us an email at <a href="mailto:apmcommunity@compuware.com">apmcommunity@compuware.com</a>!    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Known Problems    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Release History    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
2013-05-08 Initial Release    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
    <div class="section-2"  id="120128668_JBoss7DatasourceMonitoringPlugin-Configuration"  >
        <h2>Configuration</h2>
    <div class="tablewrap">
        <table>
<thead class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Name    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Value    </p>
            </td>
        </tr>
</thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
datasourceName    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Name of the datasource    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
DSMeasure    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
The datasource measure/statistics that you want to capture.<br/>    <span style="color: #ff0000;">
<strong class=" "><u class=" ">NOTE:</u></strong>    </span>
 This value is case-sensitive    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
jbossusername    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Jboss admin username    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
jbosspassword    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Jboss admin password    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
managementPort    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Jboss management console port    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
    <div class="section-2"  id="120128668_JBoss7DatasourceMonitoringPlugin-Installation"  >
        <h2>Installation</h2>
    <p>
Import the Plugin into the dynaTrace Server. For details how to do this please refer to the <a href="https://community.dynatrace.com/community/display/DOCDT50/Manage+and+Develop+Plugins#ManageandDevelopPlugins-ManageandDevelopPlugins">dynaTrace documentation</a>.    </p>
    </div>
            </div>
        </div>
        <div class="footer">
        </div>
    </div>
</body>
</html>