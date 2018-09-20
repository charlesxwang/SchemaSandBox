# The Root Schema



### Example

```json
{
  "GeneralInformation": {
    "name": "",
    "revision": 0,
    "type": "",
    "year": 0,
    "stories": 0,
    "height": 0,
    "volume": 0,
    "area": 0,
    "location": {
      "name": "",
      "latitude": 0,
      "longitude": 0
    },
    "units": {
      "force": "",
      "length": "",
      "time": "",
      "temperature": ""
    },
    "engineer": "",
    "URL": null,
    "DOI": null
  },
  "StructuralInformation": {
    "type": "",
    "layout": {
      "floors": [
        {
          "name": "",
          "elevation": 0
        }
      ],
      "clines": [
        {
          "name": "",
          "location": [
            {}
          ]
        }
      ]
    },
    "properties": {
      "materials": [
        {}
      ],
      "wallsections": [
        {
          "name": "",
          "material": "",
          "type": "",
          "length": 0,
          "thickness": 0,
          "boundaryElementLength": 0,
          "longitudinalRebar": {
            "material": "",
            "numBarsThickness": 0,
            "barArea": 0,
            "spacing": 0,
            "cover": 0
          },
          "transverseRebar": {
            "material": "",
            "numBarsThickness": 0,
            "barArea": 0,
            "spacing": 0,
            "cover": 0
          },
          "longitudinalBoundaryElementRebar": {
            "material": "",
            "numBarsLength": 0,
            "numBarsThickness": 0,
            "barArea": 0,
            "cover": 0
          },
          "transverseBoundaryElementRebar": {
            "material": "",
            "numBarsLength": 0,
            "numBarsThickness": 0,
            "barArea": 0,
            "spacing": 0
          }
        }
      ]
    },
    "geometry": {
      "walls": [
        {
          "name": "",
          "cline": [
            {}
          ],
          "floor": [
            {}
          ],
          "segment": [
            {
              "section": "",
              "ratio": [
                {}
              ],
              "angle": 0
            }
          ]
        }
      ]
    }
  },
  "ExteriorInformation": {
    "type": null
  },
  "ContentInformation": {
    "type": null
  }
}
```


### Documentation

### `.GeneralInformation`

**The Generalinformation Schema**

*Type*: object

### `.GeneralInformation.name`

**The Name Schema**

*Type*: string

*Pattern*: `^(.*)$`

*Examples*: `RCWall_BerteroS6`

### `.GeneralInformation.revision`

**The revision Schema**

*Type*: number

*Examples*: `1`

### `.GeneralInformation.type`

**The Type Schema**

*Type*: string

*Pattern*: `^(.*)$`

*Examples*: `ExperimentalTest`

### `.GeneralInformation.year`

**The Year Schema**

*Type*: number

*Examples*: `2003`

### `.GeneralInformation.stories`

**The Stories Schema**

*Type*: number

*Examples*: `3`

### `.GeneralInformation.height`

**The Height Schema**

*Type*: number

*Examples*: `120`

### `.GeneralInformation.volume`

**The Volume Schema**

*Type*: number

*Examples*: `51141.6576`

### `.GeneralInformation.area`

**The Area Schema**

*Type*: number

*Examples*: `300`

### `.GeneralInformation.location`

**The Location Schema**

*Type*: object

### `.GeneralInformation.location.name`

**The Name Schema**

*Type*: string

*Pattern*: `^(.*)$`

*Examples*: `unknown`

### `.GeneralInformation.location.latitude`

**The Latitude Schema**

*Type*: number

*Examples*: `37.916872`

### `.GeneralInformation.location.longitude`

**The Longitude Schema**

*Type*: number

*Examples*: `-122.329703`

### `.GeneralInformation.units`

**The Units Schema**

*Type*: object

### `.GeneralInformation.units.force`

**The Force Schema**

*Type*: string

*Pattern*: `^(.*)$`

*Examples*: `kip`

### `.GeneralInformation.units.length`

**The Length Schema**

*Type*: string

*Pattern*: `^(.*)$`

*Examples*: `in`

### `.GeneralInformation.units.time`

**The Time Schema**

*Type*: string

*Pattern*: `^(.*)$`

*Examples*: `sec`

### `.GeneralInformation.units.temperature`

**The Temperature Schema**

*Type*: string

*Pattern*: `^(.*)$`

*Examples*: `F`

### `.GeneralInformation.engineer`

**The Engineer Schema**

*Type*: string

*Pattern*: `^(.*)$`

*Examples*: `Bertero`

### `.GeneralInformation.URL`

**The Url Schema**

*Type*: null

*Examples*: `null`

### `.GeneralInformation.DOI`

**The Doi Schema**

*Type*: null

*Examples*: `null`

### `.StructuralInformation`

**The Structuralinformation Schema**

*Type*: object

### `.StructuralInformation.type`

**The Type Schema**

*Type*: string

*Pattern*: `^(.*)$`

*Examples*: `A1 - SpecialReinforcedConcreteShearWall`

### `.StructuralInformation.layout`

**The Layout Schema**

*Type*: object

### `.StructuralInformation.layout.floors`

**The Floors Schema**

*Type*: array

### `.StructuralInformation.layout.floors[]`

**The Items Schema**

*Type*: object

### `.StructuralInformation.layout.floors[].name`

**The Name Schema**

*Type*: string

*Pattern*: `^(.*)$`

*Examples*: `0`

### `.StructuralInformation.layout.floors[].elevation`

**The Elevation Schema**

*Type*: number

*Examples*: `0`

### `.StructuralInformation.layout.clines`

**The Clines Schema**

*Type*: array

### `.StructuralInformation.layout.clines[]`

**The Items Schema**

*Type*: object

### `.StructuralInformation.layout.clines[].name`

**The Name Schema**

*Type*: string

*Pattern*: `^(.*)$`

*Examples*: `1`

### `.StructuralInformation.layout.clines[].location`

**The Location Schema**

*Type*: array

### `.StructuralInformation.layout.clines[].location[]`

**The Items Schema**

*Type*: number

*Examples*: `0` `0`

### `.StructuralInformation..`

**The Properties Schema**

*Type*: object

### `.StructuralInformation...materials`

**The Materials Schema**

*Type*: array

### `.StructuralInformation...materials[]`

**The Items Schema**

*Type*: object

### `.StructuralInformation...materials[].name`

**The Name Schema**

*Type*: string

*Pattern*: `^(.*)$`

*Examples*: `Concrete`

### `.StructuralInformation...materials[].type`

**The Type Schema**

*Type*: string

*Pattern*: `^(.*)$`

*Examples*: `concrete`

### `.StructuralInformation...materials[].masspervolume`

**The Masspervolume Schema**

*Type*: number

*Examples*: `0.0000860914`

### `.StructuralInformation...materials[].fpc`

**The Fpc Schema**

*Type*: number

*Examples*: `5.032632342`

### `.StructuralInformation...materials[].E`

**The E Schema**

*Type*: number

*Examples*: `4043.639756`

### `.StructuralInformation...materials[].nu`

**The Nu Schema**

*Type*: number

*Examples*: `0.2`

### `.StructuralInformation...materials[]anyOf0`

### `.StructuralInformation...materials[]anyOf0.type`

*Allowed values*: `concrete`

### `.StructuralInformation...materials[]anyOf1`

### `.StructuralInformation...materials[]anyOf1.type`

*Allowed values*: `steel rebar`

### `.StructuralInformation...materials[]anyOf2`

### `.StructuralInformation...materials[]anyOf2.type`

*Allowed values*: `other material 1` `other materials 2`

### `.StructuralInformation...framesections`

**The Framesections Schema**

*Type*: array

### `.StructuralInformation...slabsections`

**The Slabsections Schema**

*Type*: array

### `.StructuralInformation...decksections`

**The Decksections Schema**

*Type*: array

### `.StructuralInformation...wallsections`

**The Wallsections Schema**

*Type*: array

### `.StructuralInformation...wallsections[]`

**The Items Schema**

*Type*: object

### `.StructuralInformation...wallsections[].name`

**The Name Schema**

*Type*: string

*Pattern*: `^(.*)$`

*Examples*: `Wall`

### `.StructuralInformation...wallsections[].material`

**The Material Schema**

*Type*: string

*Pattern*: `^(.*)$`

*Examples*: `Concrete`

### `.StructuralInformation...wallsections[].type`

**The Type Schema**

*Type*: string

*Pattern*: `^(.*)$`

*Examples*: `concrete rectangular wall`

### `.StructuralInformation...wallsections[].length`

**The Length Schema**

*Type*: number

*Examples*: `94.96`

### `.StructuralInformation...wallsections[].thickness`

**The Thickness Schema**

*Type*: number

*Examples*: `4.488`

### `.StructuralInformation...wallsections[].boundaryElementLength`

**The Boundaryelementlength Schema**

*Type*: number

*Examples*: `10.984`

### `.StructuralInformation...wallsections[].longitudinalRebar`

**The Longitudinalrebar Schema**

*Type*: object

### `.StructuralInformation...wallsections[].longitudinalRebar.material`

**The Material Schema**

*Type*: string

*Pattern*: `^(.*)$`

*Examples*: `Steel Web Vert`

### `.StructuralInformation...wallsections[].longitudinalRebar.numBarsThickness`

**The Numbarsthickness Schema**

*Type*: number

*Examples*: `2`

### `.StructuralInformation...wallsections[].longitudinalRebar.barArea`

**The Bararea Schema**

*Type*: number

*Examples*: `0.04908738521`

### `.StructuralInformation...wallsections[].longitudinalRebar.spacing`

**The Spacing Schema**

*Type*: number

*Examples*: `4`

### `.StructuralInformation...wallsections[].longitudinalRebar.cover`

**The Cover Schema**

*Type*: number

*Examples*: `0.25`

### `.StructuralInformation...wallsections[].transverseRebar`

**The Transverserebar Schema**

*Type*: object

### `.StructuralInformation...wallsections[].transverseRebar.material`

**The Material Schema**

*Type*: string

*Pattern*: `^(.*)$`

*Examples*: `Steel Web Horz`

### `.StructuralInformation...wallsections[].transverseRebar.numBarsThickness`

**The Numbarsthickness Schema**

*Type*: number

*Examples*: `2`

### `.StructuralInformation...wallsections[].transverseRebar.barArea`

**The Bararea Schema**

*Type*: number

*Examples*: `0.04908738521`

### `.StructuralInformation...wallsections[].transverseRebar.spacing`

**The Spacing Schema**

*Type*: number

*Examples*: `4`

### `.StructuralInformation...wallsections[].transverseRebar.cover`

**The Cover Schema**

*Type*: number

*Examples*: `0.25`

### `.StructuralInformation...wallsections[].longitudinalBoundaryElementRebar`

**The Longitudinalboundaryelementrebar Schema**

*Type*: object

### `.StructuralInformation...wallsections[].longitudinalBoundaryElementRebar.material`

**The Material Schema**

*Type*: string

*Pattern*: `^(.*)$`

*Examples*: `Steel BE Vert`

### `.StructuralInformation...wallsections[].longitudinalBoundaryElementRebar.numBarsLength`

**The Numbarslength Schema**

*Type*: number

*Examples*: `4`

### `.StructuralInformation...wallsections[].longitudinalBoundaryElementRebar.numBarsThickness`

**The Numbarsthickness Schema**

*Type*: number

*Examples*: `2`

### `.StructuralInformation...wallsections[].longitudinalBoundaryElementRebar.barArea`

**The Bararea Schema**

*Type*: number

*Examples*: `0.3097484693`

### `.StructuralInformation...wallsections[].longitudinalBoundaryElementRebar.cover`

**The Cover Schema**

*Type*: number

*Examples*: `0.25`

### `.StructuralInformation...wallsections[].transverseBoundaryElementRebar`

**The Transverseboundaryelementrebar Schema**

*Type*: object

### `.StructuralInformation...wallsections[].transverseBoundaryElementRebar.material`

**The Material Schema**

*Type*: string

*Pattern*: `^(.*)$`

*Examples*: `Steel BE Conf`

### `.StructuralInformation...wallsections[].transverseBoundaryElementRebar.numBarsLength`

**The Numbarslength Schema**

*Type*: number

*Examples*: `4`

### `.StructuralInformation...wallsections[].transverseBoundaryElementRebar.numBarsThickness`

**The Numbarsthickness Schema**

*Type*: number

*Examples*: `2`

### `.StructuralInformation...wallsections[].transverseBoundaryElementRebar.barArea`

**The Bararea Schema**

*Type*: number

*Examples*: `0.0163539454`

### `.StructuralInformation...wallsections[].transverseBoundaryElementRebar.spacing`

**The Spacing Schema**

*Type*: number

*Examples*: `1.34`

### `.StructuralInformation...connections`

**The Connections Schema**

*Type*: array

### `.StructuralInformation...panelzones`

**The Panelzones Schema**

*Type*: array

### `.StructuralInformation...links`

**The Links Schema**

*Type*: array

### `.StructuralInformation...points`

**The Points Schema**

*Type*: array

### `.StructuralInformation.geometry`

**The Geometry Schema**

*Type*: object

### `.StructuralInformation.geometry.columns`

**The Columns Schema**

*Type*: array

### `.StructuralInformation.geometry.beams`

**The Beams Schema**

*Type*: array

### `.StructuralInformation.geometry.braces`

**The Braces Schema**

*Type*: array

### `.StructuralInformation.geometry.floors`

**The Floors Schema**

*Type*: array

### `.StructuralInformation.geometry.walls`

**The Walls Schema**

*Type*: array

### `.StructuralInformation.geometry.walls[]`

**The Items Schema**

*Type*: object

### `.StructuralInformation.geometry.walls[].name`

**The Name Schema**

*Type*: string

*Pattern*: `^(.*)$`

*Examples*: `W1S1`

### `.StructuralInformation.geometry.walls[].cline`

**The Cline Schema**

*Type*: array

### `.StructuralInformation.geometry.walls[].cline[]`

**The Items Schema**

*Type*: string

*Pattern*: `^(.*)$`

*Examples*: `1` `2`

### `.StructuralInformation.geometry.walls[].floor`

**The Floor Schema**

*Type*: array

### `.StructuralInformation.geometry.walls[].floor[]`

**The Items Schema**

*Type*: string

*Pattern*: `^(.*)$`

*Examples*: `0` `1`

### `.StructuralInformation.geometry.walls[].segment`

**The Segment Schema**

*Type*: array

### `.StructuralInformation.geometry.walls[].segment[]`

**The Items Schema**

*Type*: object

### `.StructuralInformation.geometry.walls[].segment[].section`

**The Section Schema**

*Type*: string

*Pattern*: `^(.*)$`

*Examples*: `Wall`

### `.StructuralInformation.geometry.walls[].segment[].ratio`

**The Ratio Schema**

*Type*: array

### `.StructuralInformation.geometry.walls[].segment[].ratio[]`

**The Items Schema**

*Type*: number

*Examples*: `0` `1`

### `.StructuralInformation.geometry.walls[].segment[].angle`

**The Angle Schema**

*Type*: number

*Examples*: `0`

### `.StructuralInformation.geometry.panelzones`

**The Panelzones Schema**

*Type*: array

### `.StructuralInformation.geometry.links`

**The Links Schema**

*Type*: array

### `.StructuralInformation.geometry.points`

**The Points Schema**

*Type*: array

### `.ExteriorInformation`

**The Exteriorinformation Schema**

*Type*: object

### `.ExteriorInformation.type`

**The Type Schema**

*Type*: null

*Examples*: `null`

### `.ContentInformation`

**The Contentinformation Schema**

*Type*: object

### `.ContentInformation.type`

**The Type Schema**

*Type*: null

*Examples*: `null`