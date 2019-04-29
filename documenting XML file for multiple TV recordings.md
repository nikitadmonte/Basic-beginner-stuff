---


---

<p>Documenting XML file for multiple TV Recordings</p>






<table>
<thead>
<tr>
<th>Elements</th>
<th>Attributes</th>
<th>Description</th>
<th>Type</th>
<th>Required</th>
<th>Notes</th>
</tr>
</thead>
<tbody>
<tr>
<td>recordTV</td>
<td></td>
<td>Top level</td>
<td>TV program data</td>
<td>Required</td>
<td></td>
</tr>
<tr>
<td>&nbsp;&nbsp; when</td>
<td></td>
<td></td>
<td></td>
<td>Required</td>
<td></td>
</tr>
<tr>
<td></td>
<td>date</td>
<td>date</td>
<td>string</td>
<td>optional</td>
<td>Date format YYYY-MM-DD; default would be today’s date</td>
</tr>
<tr>
<td></td>
<td>time</td>
<td>time</td>
<td>string</td>
<td>required</td>
<td>Date format would be HH-MM with am or pm afterwards for 12 hour format</td>
</tr>
<tr>
<td></td>
<td>format</td>
<td>format for time either 24 or 12</td>
<td>string</td>
<td>required</td>
<td>valid values 24 or 12</td>
</tr>
<tr>
<td>&nbsp;&nbsp; duration</td>
<td>hours</td>
<td>time of recording</td>
<td>Number</td>
<td>Required</td>
<td>in hours</td>
</tr>
<tr>
<td>&nbsp;&nbsp; station</td>
<td>channel</td>
<td>channel to record</td>
<td>Number</td>
<td>Required</td>
<td></td>
</tr>
</tbody>
</table>
