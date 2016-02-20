# paper-input based widget for entering a vector

##goal
The objective is to provide a macro widget enabling user to specify a vector (dimension can be 2, 3, 4). This is typically needed for applications where position, direction, or color like input is needed.
##properties
| property | type | default value | description |
| --- | --- | --- | --- |
| vector | Array | [0,0,0,0] | value of vector |
| normalized | Boolean | false | to enforce normalization |
| label | String | 'vector input' | label of widget |
| dimension | Integer | 3 | dimension |
| units | String | '' | suffix |
| type | String | 'Float' | type of data |
| error-message | String | Invalid Input | error message for invalid entry |
| label-comp1 | String | 'component 1' | label of component 1 |
| label-comp2 | String | 'component 2' | label of component 2 |
| label-comp3 | String | 'component 3' | label of component 3 |
| label-comp4 | String | 'component 4' | label of component 4 |
