---


---

<p>Documenting JSON file for Meeting<br>
String | Required | Format is YYYY-MM-DD HH-MM |</p>
<p>{<br>
“meeting” : {<br>
“time”: “2015-09-01 10:00”,<br>
“duration”: 60,<br>
“description”: “2016 Strategic Planning Meeting”,<br>
“location”: “Building 23, Room 206”,<br>
“reminder”: 15,<br>
“invitees”: [“michael@example.com”, <a href="mailto:%22thelma@example.com">"thelma@example.com</a>",<br>
<a href="mailto:%22david@example.com">"david@example.com</a>", <a href="mailto:%22leon@example.com">"leon@example.com</a>"]<br>
}<br>
}</p>

<table>
<thead>
<tr>
<th>Element</th>
<th>Description</th>
<th>Type</th>
<th>Required</th>
<th>Notes</th>
</tr>
</thead>
<tbody>
<tr>
<td>Meeting</td>
<td>Top Level</td>
<td>String</td>
<td></td>
<td></td>
</tr>
<tr>
<td>&nbsp; &nbsp; Time</td>
<td>The date and time of the meeting</td>
<td>String</td>
<td>Required</td>
<td>The format is YYYY-MM-DD HH-MM; follows Greenwich Meridian Time</td>
</tr>
<tr>
<td>&nbsp; &nbsp; Duration</td>
<td>Duration of the meeting</td>
<td>Number</td>
<td>Required</td>
<td></td>
</tr>
<tr>
<td>&nbsp; &nbsp; Description</td>
<td>What is the meeting about</td>
<td>String</td>
<td>Required</td>
<td>Title of the meeting</td>
</tr>
<tr>
<td>&nbsp; &nbsp; Location</td>
<td>Where is the meeting being held</td>
<td>String</td>
<td>optional</td>
<td>The default is an empty string</td>
</tr>
<tr>
<td>&nbsp; &nbsp; Reminder</td>
<td>Reminder for meeting</td>
<td>Number</td>
<td>Optional</td>
<td>The default is 15 mins</td>
</tr>
<tr>
<td>&nbsp; &nbsp; Invitees</td>
<td>People attending the meeting</td>
<td>Array of String</td>
<td>Optional</td>
<td>Value: A valid email ID, default is an empty string</td>
</tr>
</tbody>
</table>
