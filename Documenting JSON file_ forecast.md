---


---

<p>Documenting JSON file for a Weather forecast:</p>
<p>{<br>
“date”: “2015-09-01”,<br>
“description”: “sunny”,<br>
“maxTemp”: 22,<br>
“minTemp”: 20,<br>
“windSpeed”: 12,<br>
“danger”: false<br>
}</p>

<table>
<thead>
<tr>
<th>Element</th>
<th>Description</th>
<th>Type</th>
<th>Notes</th>
</tr>
</thead>
<tbody>
<tr>
<td>date</td>
<td>Date of weather forecast</td>
<td>String</td>
<td>Format is YYYY-MM-DD</td>
</tr>
<tr>
<td>description</td>
<td>text description of the weather</td>
<td>String</td>
<td>Valid values include: Sunny, Rainy, Cloudy, Overcast, Partly Cloudy, Snowing</td>
</tr>
<tr>
<td>maxTemp</td>
<td>High Temperature</td>
<td>Number</td>
<td>In degree celsius</td>
</tr>
<tr>
<td>minTemp</td>
<td>Low Temperature</td>
<td>Number</td>
<td>In degree celsius</td>
</tr>
<tr>
<td>windspeed</td>
<td>Wind speed</td>
<td>Number</td>
<td>In km/hr</td>
</tr>
<tr>
<td>danger</td>
<td>True if the weather conditions are dangerous, else false.</td>
<td>Boolean</td>
<td></td>
</tr>
</tbody>
</table>
