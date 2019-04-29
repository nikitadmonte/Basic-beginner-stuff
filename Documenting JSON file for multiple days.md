---


---

<p>Documenting JSON file for Multiple days weather forecast:</p>
<p>{<br>
“longitude”: 47.60,<br>
“latitude”: 122.33,<br>
“forecasts”: [<br>
{<br>
“date”: “2015-09-01”,<br>
“description”: “sunny”,<br>
“maxTemp”: 22,<br>
“minTemp”: 20,<br>
“windSpeed”: 12,<br>
“danger”: false<br>
},<br>
{<br>
“date”: “2015-09-02”,<br>
“description”: “overcast”,<br>
“maxTemp”: 21,<br>
“minTemp”: 17,<br>
“windSpeed”: 15,<br>
“danger”: false<br>
},<br>
{<br>
“date”: “2015-09-03”,<br>
“description”: “raining”,<br>
“maxTemp”: 20,<br>
“minTemp”: 18,<br>
“windSpeed”: 13,<br>
“danger”: false<br>
}<br>
]<br>
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
<td>Longitude</td>
<td>Longitude of the location where the forecast is taking place</td>
<td>Number</td>
<td></td>
</tr>
<tr>
<td>Latitude</td>
<td>Latitude of the place where the forecast is taking place</td>
<td>Number</td>
<td></td>
</tr>
<tr>
<td>Forecast</td>
<td>Daily forecast</td>
<td>array of daily forecast objects</td>
<td></td>
</tr>
<tr>
<td>&nbsp; &nbsp; date</td>
<td>date of the forecast</td>
<td>String</td>
<td>format should be YYYY-MM-DD</td>
</tr>
<tr>
<td>&nbsp; &nbsp; description</td>
<td>text description of weather</td>
<td>String</td>
<td>Valid values include sunny, cloudy, partly cloudy, raining, overcast, snowing</td>
</tr>
<tr>
<td>&nbsp; &nbsp; maxTemp</td>
<td>Highest Temperature</td>
<td>Number</td>
<td>format should be degree Celsius</td>
</tr>
<tr>
<td>&nbsp; &nbsp; minTemp</td>
<td>Lowest Temperature</td>
<td>Number</td>
<td>format should be degree Celsius</td>
</tr>
<tr>
<td>&nbsp; &nbsp; windSpeed</td>
<td>Wind Speed</td>
<td>Number</td>
<td>format should be km/hr</td>
</tr>
<tr>
<td>&nbsp; &nbsp; danger</td>
<td>If weather is dangerous true; otherwise, false</td>
<td>Boolean</td>
<td></td>
</tr>
</tbody>
</table>
