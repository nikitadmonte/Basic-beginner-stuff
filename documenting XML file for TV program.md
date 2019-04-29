---


---

<p>Documenting XML file:<br>
<br>
2015-06-01<br>
<time>18:00</time><br>
1.5<br>
54<br>
</p>

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
<td>recordTV</td>
<td>Top Level</td>
<td>String</td>
<td>Required</td>
<td></td>
</tr>
<tr>
<td>&nbsp; &nbsp; date</td>
<td>date of recording</td>
<td>String</td>
<td>Optional</td>
<td>Format has to be YYYY-MM- HH-MM-SS, default is today’s date</td>
</tr>
<tr>
<td>&nbsp; &nbsp; time</td>
<td>time the program begins</td>
<td>Number</td>
<td>Required</td>
<td>Attributes <strong>format</strong> has values either 24 or 12. Format is HH-MM followed by am or pm is following a 12 hour format</td>
</tr>
<tr>
<td>&nbsp; &nbsp; duration</td>
<td>duration of recording</td>
<td>number</td>
<td>Required</td>
<td>In hours</td>
</tr>
<tr>
<td>&nbsp; &nbsp; channel</td>
<td>channel to record</td>
<td>number</td>
<td>Required</td>
<td></td>
</tr>
</tbody>
</table>
