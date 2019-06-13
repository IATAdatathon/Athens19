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



## ARRIVALS / DEPARTURES

<table>
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
            <td>mode</td>
            <td>String</td>
            <td>arrivals</td>
            <td>[arrivals] or [departures] indicator</td>
        </tr>
        <tr>
            <td>flight_number</td>
            <td>String</td>
            <td>JL41</td>
            <td>Operating Airline Flight Number</td>
        </tr>
        <tr>
            <td>callsign</td>
            <td>String</td>
            <td>JAL41</td>
            <td>Operating Flight Callsign</td>
        </tr>
        <tr>
            <td>aircraft_model_code</td>
            <td>String</td>
            <td>B788</td>
            <td>Operating aircraft model code</td>
        </tr>
        <tr>
            <td>aircraft_model_description</td>
            <td>String</td>
            <td>Boeing 787-8 Dreamliner</td>
            <td>Operating aircraft model</td>
        </tr>
        <tr>
            <td>aircraft_registration</td>
            <td>String</td>
            <td>JA837J</td>
            <td>Operating aircraft registration</td>
        </tr>
        <tr>
            <td>airline_name</td>
            <td>String</td>
            <td>Japan Airlines</td>
            <td>Operating Airline Name</td>
        </tr>
        <tr>
            <td>airline_iata</td>
            <td>String</td>
            <td>JL</td>
            <td>Operating Airline IATA code</td>
        </tr>
        <tr>
            <td>airline_icao</td>
            <td>String</td>
            <td>JAL</td>
            <td>Operating Airline ICAO code</td>
        </tr>
        <tr>
            <td>flight_origin_code_iata</td>
            <td>String</td>
            <td>HND</td>
            <td>Departure airport IATA code</td>
        </tr>
        <tr>
            <td>flight_origin_code_icao</td>
            <td>String</td>
            <td>RJTT</td>
            <td>Departure airport ICAO code</td>
        </tr>
        <tr>
            <td>flight_origin_name</td>
            <td>String</td>
            <td>Tokyo Haneda International Airport</td>
            <td>Departure airport name</td>
        </tr>
        <tr>
            <td>flight_origin_time_offset</td>
            <td>Integer</td>
            <td>32400</td>
            <td>UTC/Zulu - origin timezone difference in seconds</td>
        </tr>
        <tr>
            <td>flight_destination_code_iata</td>
            <td>String</td>
            <td>LHR</td>
            <td>Departure airport IATA code</td>
        </tr>
        <tr>
            <td>flight_destination_code_icao</td>
            <td>String</td>
            <td>EGLL</td>
            <td>Destination airport ICAO code</td>
        </tr>
        <tr>
            <td>flight_destination_name</td>
            <td>String</td>
            <td>London Heathrow Airport</td>
            <td>Destination airport IATA code</td>
        </tr>
        <tr>
            <td>flight_destination_time_offset</td>
            <td>Integer</td>
            <td>3600</td>
            <td>UTC/Zulu - destination timezone difference in seconds</td>
        </tr>
        <tr>
            <td>flight_departure_scheduled</td>
            <td>Integer</td>
            <td>1558284900</td>
            <td>scheudled departue time in seconds since 1970-01-01 00:00</td>
        </tr>
        <tr>
            <td>flight_departure_real</td>
            <td>Integer</td>
            <td>1558287066.0</td>
            <td>actual departure time in seconds since 1970-01-01 00:00</td>
        </tr>
        <tr>
            <td>flight_arrival_scheduled</td>
            <td>Integer</td>
            <td>1558329900</td>
            <td>scheduled arrival time in seconds since 1970-01-01 00:00</td>
        </tr>
        <tr>
            <td>flight_arrival_real</td>
            <td>Integer</td>
            <td>1558329002.0</td>
            <td>actual arrival time in seconds since 1970-01-01 00:00</td>
        </tr>
        <tr>
            <td>flight_duaration</td>
            <td>Integer</td>
            <td>41940.0</td>
            <td>Flight duration in seconds</td>
        </tr>
    </tbody>
</table>




