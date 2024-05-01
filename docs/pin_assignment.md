# Pin Assignment

Pins for the UMB are assigned according to a tiered "priority" system.
Four groups of pins are available:
- Reserved: pins that all UMBs must have
- Priority I/O: pins that UMBs should prioritize
- Vendor specific: pins that may function as I/O or serve another vendor defined purpose
- General I/O: pins intended for use in keyboard matrix

The pinout is given as:

| Priority     | Pin Group | Pin    | Pin Type      | Description              | Voltage        |
|--------------|-----------|--------|---------------|--------------------------|----------------|
| Reserved     | Power     | VCC    | Power input   | System power input       | 1.8V           |
| Reserved     | Power     | GND    | Power input   |                          |                |
| Reserved     | Power     | VBUS   | Power input   | USB power input          | 5V typical     |
| Reserved     | Power     | VBUS   | Power input   | USB power input          | 5V typical     |
| Reserved     | Power     | VBAT   | Power input   | Battery input            | 4.2V max       |
| Reserved     | Power     | VBAT   | Power input   | Battery input            | 4.2V max       |
| Reserved     | Power     | NTC    | Power input   | Battery thermistor input |                |
| Reserved     | Power     | VREF   | Power input   | Analog reference         | Vendor defined |
| Reserved     | Power     | GND    | Power input   |                          |                |
| Reserved     | USB       | USB_DP | Bidirectional | USB data                 |                |
| Reserved     | USB       | USB_DM | Bidirectional | USB data                 |                |
| Reserved     | USB       | CC1    | Bidirectional | USB PD                   |                |
| Reserved     | USB       | CC2    | Bidirectional | USB PD                   |                |
| Reserved     | Power     | GND    | Power input   |                          |                |
| Priority I/O | I2C       | SCL    | Bidirectional | I2C clock                | 1.8V           |
| Priority I/O | I2C       | SDA    | Bidirectional | I2C data                 | 1.8V           |
| Priority I/O | SPI       | SCK    | Output        | SPI clock                | 1.8V           |
| Priority I/O | SPI       | MOSI   | Output        | SPI master out           | 1.8V           |
| Priority I/O | SPI       | MISO   | Input         | SPI master in            | 1.8V           |
| Priority I/O | SPI       | CS     | Output        | SPI chip select          | 1.8V           |
| Priority I/O | Analog    | A0     | Input         | Analog input             | 1.8V           |
| Priority I/O | Analog    | A1     | Input         | Analog input             | 1.8V           |
| Priority I/O | Analog    | A2     | Input         | Analog input             | 1.8V           |
| Priority I/O | Analog    | A3     | Input         | Analog input             | 1.8V           |
| Priority I/O | Analog    | A4     | Input         | Analog input             | 1.8V           |
| Priority I/O | Analog    | A5     | Input         | Analog input             | 1.8V           |
| Priority I/O | Analog    | A6     | Input         | Analog input             | 1.8V           |
| Priority I/O | Analog    | A7     | Input         | Analog input             | 1.8V           |
| Reserved     | Power     | GND    | Power input   |                          |                |
| Vendor I/O   | Vendor    | V0     | Bidirectional | Vendor defined           | 1.8V           |
| Vendor I/O   | Vendor    | V1     | Bidirectional | Vendor defined           | 1.8V           |
| General      | GPIO      | D0     | Bidirectional | Matrix GPIO              | 1.8V           |
| General      | GPIO      | D1     | Bidirectional | Matrix GPIO              | 1.8V           |
| General      | GPIO      | D2     | Bidirectional | Matrix GPIO              | 1.8V           |
| General      | GPIO      | D3     | Bidirectional | Matrix GPIO              | 1.8V           |
| General      | GPIO      | D4     | Bidirectional | Matrix GPIO              | 1.8V           |
| General      | GPIO      | D5     | Bidirectional | Matrix GPIO              | 1.8V           |
| General      | GPIO      | D6     | Bidirectional | Matrix GPIO              | 1.8V           |
| General      | GPIO      | D7     | Bidirectional | Matrix GPIO              | 1.8V           |
| General      | GPIO      | D8     | Bidirectional | Matrix GPIO              | 1.8V           |
| General      | GPIO      | D9     | Bidirectional | Matrix GPIO              | 1.8V           |
| General      | GPIO      | D10    | Bidirectional | Matrix GPIO              | 1.8V           |
| General      | GPIO      | D11    | Bidirectional | Matrix GPIO              | 1.8V           |
| General      | GPIO      | D12    | Bidirectional | Matrix GPIO              | 1.8V           |
| General      | GPIO      | D13    | Bidirectional | Matrix GPIO              | 1.8V           |
| General      | GPIO      | D14    | Bidirectional | Matrix GPIO              | 1.8V           |
| General      | GPIO      | D15    | Bidirectional | Matrix GPIO              | 1.8V           |
| General      | GPIO      | D16    | Bidirectional | Matrix GPIO              | 1.8V           |
| General      | GPIO      | D17    | Bidirectional | Matrix GPIO              | 1.8V           |
| General      | GPIO      | D18    | Bidirectional | Matrix GPIO              | 1.8V           |
| General      | GPIO      | D19    | Bidirectional | Matrix GPIO              | 1.8V           |
| General      | GPIO      | D20    | Bidirectional | Matrix GPIO              | 1.8V           |
| General      | GPIO      | D21    | Bidirectional | Matrix GPIO              | 1.8V           |
| General      | GPIO      | D22    | Bidirectional | Matrix GPIO              | 1.8V           |
| General      | GPIO      | D23    | Bidirectional | Matrix GPIO              | 1.8V           |
| General      | GPIO      | D24    | Bidirectional | Matrix GPIO              | 1.8V           |
| General      | GPIO      | D25    | Bidirectional | Matrix GPIO              | 1.8V           |
| General      | GPIO      | D26    | Bidirectional | Matrix GPIO              | 1.8V           |
| General      | GPIO      | D27    | Bidirectional | Matrix GPIO              | 1.8V           |
| General      | GPIO      | D28    | Bidirectional | Matrix GPIO              | 1.8V           |
| General      | GPIO      | D29    | Bidirectional | Matrix GPIO              | 1.8V           |
| General      | GPIO      | D30    | Bidirectional | Matrix GPIO              | 1.8V           |
| General      | GPIO      | D31    | Bidirectional | Matrix GPIO              | 1.8V           |
| General      | GPIO      | D32    | Bidirectional | Matrix GPIO              | 1.8V           |
| General      | GPIO      | D33    | Bidirectional | Matrix GPIO              | 1.8V           |
| General      | GPIO      | D34    | Bidirectional | Matrix GPIO              | 1.8V           |
| General      | GPIO      | D35    | Bidirectional | Matrix GPIO              | 1.8V           |
