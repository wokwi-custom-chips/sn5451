# Wokwi sn5451 Chip

This is a custom chip for [Wokwi](https://wokwi.com/). It implements the sn5451 IC.

## Usage

To use this chip in your project, include it as a dependency in your `diagram.json` file:

```json
  "dependencies": {
    "chip-sn5451": "github:wokwi-custom-chips/sn5451@0.1.0"
  }
```

Then, add the chip to your circuit by adding a `chip-sn5451` item to the `parts` section of diagram.json:

```json
  "parts": {
    ...,
    { "type": "chip-sn5451", "id": "chip1" }
  },
```

For a complete example, see [The sn5451 chip test project](https://wokwi.com/projects/399517911231968257).
