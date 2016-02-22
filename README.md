# paper-input based widget for entering a vector

##goal
The objective is to provide a macro widget enabling user to specify a vector (dimension can be 2, 3, 4).

This is typically needed for 3D applications where position, direction, or color inputs are needed.

##examples
```
<paper-input-vector units="%"
                    label="Scale"
                    label-comp1="X"
                    label-comp2="Y"
                    label-comp3="Z"></paper-input-vector>

<paper-input-vector units="m"
                    label="Position"
                    label-comp1="X"
                    label-comp2="Y"
                    label-comp3="Z"></paper-input-vector>

<paper-input-vector min-value=0
                    max-value=1
                    dimension=4
                    label="Diffuse"
                    label-comp1="R"
                    label-comp2="G"
                    label-comp3="B"
                    label-comp4="A"></paper-input-vector>
```

##properties
| property | type | default value | description |
| --- | --- | --- | --- |
| min-value | Number | undefined | to specify min value |
| max-value | Number | undefined | to specify max value |
| label | String | 'vector input' | label of widget |
| dimension | Integer | 3 | dimension |
| units | String | '' | suffix |
| type | String | 'Float' | type of data |
| label-comp1 | String | 'component 1' | label of component 1 |
| label-comp2 | String | 'component 2' | label of component 2 |
| label-comp3 | String | 'component 3' | label of component 3 |
| label-comp4 | String | 'component 4' | label of component 4 |
| value-comp1 | Number | 0 | value of component 1 |
| value-comp2 | Number | 0 | value of component 2 |
| value-comp3 | Number | 0 | value of component 3 |
| value-comp4 | Number | 0 | value of component 4 |

## methods
| method | description |
| --- | --- |
|setVector ()|to set vector values as an array|
|getVector ()|to get vector values as an array|
