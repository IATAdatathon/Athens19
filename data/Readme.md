# Datasets Description


## METAR

<table border="1" class="dataframe">  
    <thead>    
        <tr style="text-align: right;">
            <th>Element</th>
            <th>Format</th>
            <th>Example</th>
            <th>Description</th>
        </tr>  
    </thead>  
    <tbody>
        <tr>      
            <td>AIRPORT_IATA</td>      
            <td>String</td>
            <td>LHR</td>
            <td>Airport IATA Code</td>    
        </tr>    
        <tr>      
            <td>AIRPORT_ICAO</td>      
            <td>String</td>
            <td>EGLL</td>
            <td>Airport ICAO Code</td>    
        </tr>    
        <tr>      
            <td>UTC DATE/TIME</td>      
            <td>%Y-%m-%d %H:%M:%S</td>
            <td>2019-05-18 23:50:00</td>
            <td>META effective date time</td>    
        </tr>    
        <tr>      
            <td>METAR</td>      
            <td>String</td>
            <td>EGLL 182350Z AUTO 01003KT 9999 NCD 11/09 Q1009 NOSIG</td>
            <td>METAR Message</td>    
        </tr>    
        <tr>      
            <td>DESCRIPTION</td>      
            <td>String</td>
            <td>Day: 18th Time: 23:50 UTC Wind direction: 10 Wind speed: 3kt Temperature: 11C Dew point: 9C Pressure: 1009 hPa Visibility: 9999 m</td>
            <td>Decoded METAR message</td>    
        </tr>    
    </tbody>

</table>
