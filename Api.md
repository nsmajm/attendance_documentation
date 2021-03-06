

> # Get Device List

### Api Endpoint : http://portal.xtimetracker.com/api/v1/device/list

# Parameter
```

   <table>
<thead>
<tr style="background-color: rgb(64, 158, 255); color: rgb(255, 255, 255);">
<th style="text-align: left; width: 188px;">Param</th>
<th style="text-align: left; width: 188px;">Required</th>
<th style="text-align: left; width: 188px;">Type</th>
<th style="width: 188px;">Description</th>
</tr>
</thead>
<tbody>
<tr ">
<td style="text-align:left;">email</td>
<td style="text-align:left;">yes</td>
<td style="text-align:left;">string</td>
<td>your email</td>
</tr>
<tr ">
<td style="text-align:left;">password</td>
<td style="text-align:left;">yes</td>
<td style="text-align:left;">string</td>
<td>your password</td>
</tr>
</tbody>
</table>
```
# Response :

```json
 {
        "user_id": 9,
        "school_name": "Khilgaon Govt High School",
        "device_location": "Khilgaon",
        "device_serial": "ZXNH01281716",
        "device_status": 1
    },
    {
        "user_id": 9,
        "school_name": "Khilgaon Model High School",
        "device_location": "Khilgaon",
        "device_serial": "ZXNH27288658",
        "device_status": 1
    },
```


> # Get Data By Device


### Api Endpoint : http://portal.xtimetracker.com/api/v1/device/data

```

   <table>
<thead>
<tr style="background-color: rgb(64, 158, 255); color: rgb(255, 255, 255);">
<th style="text-align: left; width: 188px;">Param</th>
<th style="text-align: left; width: 188px;">Required</th>
<th style="text-align: left; width: 188px;">Type</th>
<th style="width: 188px;">Description</th>
</tr>
</thead>
<tbody>
<tr ">
<td style="text-align:left;">email</td>
<td style="text-align:left;">yes</td>
<td style="text-align:left;">string</td>
<td>your email</td>
</tr>
<tr ">
<td style="text-align:left;">password</td>
<td style="text-align:left;">yes</td>
<td style="text-align:left;">string</td>
<td>your password</td>
</tr>
<tr ">
<td style="text-align:left;">deviceId</td>
<td style="text-align:left;">yes</td>
<td style="text-align:left;">string</td>
<td>your deviceId</td>
</tr>
</tbody>
</table>
```

# Reponse :

```json
[
    {
        "att_id": "1",
        "att_date": "2019-12-14",
        "att_time": "14:36:56",
        "device_serial": "ZXNH01281716"
    },
    {
        "att_id": "1",
        "att_date": "2019-12-14",
        "att_time": "14:38:36",
        "device_serial": "ZXNH01281716"
    }
]
```



> # Get Data according to Start Date and End Date


### Api Endpoint : http://portal.xtimetracker.com/api/v1/device/data/bydate

```

   <table>
<thead>
<tr style="background-color: rgb(64, 158, 255); color: rgb(255, 255, 255);">
<th style="text-align: left; width: 188px;">Param</th>
<th style="text-align: left; width: 188px;">Required</th>
<th style="text-align: left; width: 188px;">Type</th>
<th style="width: 188px;">Description</th>
</tr>
</thead>
<tbody>
<tr ">
<td style="text-align:left;">email</td>
<td style="text-align:left;">yes</td>
<td style="text-align:left;">string</td>
<td>your email</td>
</tr>
<tr ">
<td style="text-align:left;">password</td>
<td style="text-align:left;">yes</td>
<td style="text-align:left;">string</td>
<td>your password</td>
</tr>
<tr ">
<td style="text-align:left;">deviceId</td>
<td style="text-align:left;">yes</td>
<td style="text-align:left;">string</td>
<td>your deviceId</td>
</tr>
<tr ">
<td style="text-align:left;">startDate</td>
<td style="text-align:left;">yes</td>
<td style="text-align:left;">string</td>
<td>your startDate</td>
</tr>
<tr ">
<td style="text-align:left;">endDate</td>
<td style="text-align:left;">yes</td>
<td style="text-align:left;">string</td>
<td>your endDate</td>
</tr>
</tbody>
</table>
```

# Reponse :



```json
[
    {
        "att_id": "1",
        "att_date": "2019-12-14",
        "att_time": "14:36:56",
        "device_serial": "ZXNH01281716"
    },
    {
        "att_id": "1",
        "att_date": "2019-12-14",
        "att_time": "14:38:36",
        "device_serial": "ZXNH01281716"
    }
]
```
