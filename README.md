# Node groups

## Rounded Bracket

Can be used to generate bevelled brackets. The base is a trapezium, the top is an arc. The edges of the trapezium are tangent to the arc.

### Parameters

| Parameter            | Description                                             |
| -------------------- | ------------------------------------------------------- |
| Width                | The width of the bracket                                |
| Height               | The total height of the bracket                         |
| Thickness            | The thickness of the bracket                            |
| Angle                | The angle of the bracket                                |
| Bracket Vertex Color | The vertex color applied to the vertices of the bracket |
| Bracket Material     | The material applied to the bracket                     |

### Attributes

| Attribute  | Type       | Description                                                                         |
| ---------- | ---------- | ----------------------------------------------------------------------------------- |
| is_bracket | boolean    | Applied to all vertices                                                             |
| Col        | byte color | Vertex color applied to all vertices                                                |
| v_origin   | vector     | The origin point of the bracket, stored on every vertex, it's the center of the arc |
