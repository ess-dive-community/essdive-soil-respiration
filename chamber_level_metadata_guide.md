# ESS-DIVE Soil Respiration Chamber Level Metadata Guide

Here you will find proposed guidelines for standardizing chamber level soil respiration data

---
## Chamber Level Metadata Content - Link to More Details
[Chamber ID](#chamber-id) | [Measurement variable](#measurement-variable) |[Treatment](#treatment)

[Longitude](#longitude) | [Latitude](#latitude) | [Area](#area)

[Volume](#volume) | [Collar depth](#collar-depth) | [Opaque](#opaque)

[Plants removed](#plants-removed) | [Fan](#fan) | [Species](#species)

[Sensor depths](#sensor-depths) | [Instrument](#instrument) | [Notes](#notes)

---

### Chamber ID
|**field name**|CHAMBER_ID|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement level**|required|
|**description**|Unique chamber label; must appear in flux data table as well|
|**format**|character|
|**units**||

### Measurement variable
|**field name**|MSMT_VAR|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement level**|required|
|**description**|Flux should be interpreted as: "Rs" (soil respiration, whether CO2 or CH4), "Rh" (heterotrophic respiration only), "Reco" (ecosystem respiration), or "NEE" (net ecosystem exchange)|
|**format**|character|
|**units**||

### Treatment
|**field name**|TREATMENT|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement level**|required|
|**description**|Soil or ecosystem treatment applied at measurement location; default is "None"|
|**format**|character|
|**units**||

### Longitude
|**field name**|LONGITUDE|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement level**|optional|
|**description**|Decimal longitude of measurement location, positive = east|
|**format**|numeric|
|**units**|degrees|

### Latitude
|**field name**|LATITUDE|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement level**|optional|
|**description**|Decimal latitude of measurement location, positive = north|
|**format**|numeric|
|**units**|degrees|

### Area
|**field name**|AREA|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement level**|optional|
|**description**|Soil surface measurement area|
|**format**|numeric|
|**units**|cm2|

### Volume
|**field name**|VOLUME|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement level**|optional|
|**description**|Volume of measurement chamber|
|**format**|numeric|
|**units**|cm3|

### Collar depth
|**field name**|COLLAR_DEPTH|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement level**|optional|
|**description**|Depth of collar insertion|
|**format**|numeric|
|**units**|cm|

### Opaque
|**field name**|OPAQUE|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement level**|required|
|**description**|Opaque chamber?|
|**format**|logical|
|**units**||

### Plants removed
|**field name**|PLANTS_REMOVED|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement level**|required|
|**description**|Plants removed from inside collar?|
|**format**|logical|
|**units**||

### Fan
|**field name**|FAN|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement level**|optional|
|**description**|Mixing fan in chamber?|
|**format**|logical|
|**units**||

### Species
|**field name**|SPECIES|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement level**|optional|
|**description**|Comma-separated list of dominant species at measurement location|
|**format**|character|
|**units**||

### Sensor depths
|**field name**|SENSOR_DEPTHS|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement level**|optional|
|**description**|Comma-separated depths of solid-state sensors, gradient method only|
|**format**|character|
|**units**|cm|

### Instrument
|**field name**|INSTRUMENT|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|required|
|**description**|Measurement instrument (i.e. model)|
|**format**|character|
|**units**||

### Notes
|**field name**|NOTES|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|optional|
|**description**|Additional information about this measurement location|
|**format**|character|
|**units**||