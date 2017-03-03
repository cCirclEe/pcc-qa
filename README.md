# PCC-QA
Quality assurance phase for Privacy Crash Cam

<p align="left">
  <img src="Portrait_camera_view_car.jpg"/>
</p>

<p>In Germany and Austria the Data Protection Legislation forbids car drivers to use Dash Cams as evidence in case of car accidents. Dash Cams usually record faces and car tags. Tough, these are private information and should not be recorded unless one has permission to do so.</p>
<p>This project focuses on developing a solution which allows Dash Cams to be used as evividence in case of car accidents while ensuring that the requirements stated by the Data Protection Law are met. The Privacy Crash Cam Smartphone App records one minute of videomaterial when a crash occours and encrypts it. After storing the encrypted media file to the device storage the user can upload it to a server which will decrypt and anonymize the video. This will render faces and car tags unrecognizable and offer the result as mp4 download to the user. Managing and downloading the anonymized video as well as managing user accounts is done via the web interface.</p>
<p>As such, this project consists of three parts (App, Web Service and Web Interface). You can find each part in a separate git repository.</p>

Test phases
===========

<p>In this test phase, we test the Privacy Crash Cam in 5 parts.</p>

<ul>
  <li>component tests</li>
  <li>performance tests</li>
  <li>integration tests</li>
  <li>system tests</li>
  <li>verification tests</li>
</ul>

<p>The code is sourced out to:</p>
<ul>
  <li><a href="https://github.com/cCirclEe/pcc-imp-app">App</a></li>
  <li><a href="https://github.com/cCirclEe/pcc-imp-webservice">Service</a></li>
  <li><a href="https://github.com/cCirclEe/pcc-imp-webinterface">Interface</a></li>
</ul>
<p> In this git repo you can find the document and the presentation of this phase.
Also you can find a presentation about the whole project we showcase on 13.03. at Fraunhofer IOSB. where all pse groups are attend.<p>
