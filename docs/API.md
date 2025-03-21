**API Message:**

| Bytes: | **Byte #1** |    **Byte #2**    |  **Byte #3**  | **Byte #4** |   **Byte #5**  |      **Byte #6**      |
| ------ | ----------- | ----------------- | ------------- | ----------- | -------------- | --------------------- |
| Name:  | Motor_ON    | Motor_Direction   | Ready For Arm | E-Stop      | Web_Command_ON | Web_Command_Direction |
| Type:  | uint8       | uint8             | uint8         | uint8       | uint8          | uint8                 |
| Min:   | 0 (OFF)     | 0 (OFF)           | 0 (OFF)       | 0 (OFF)     | 0 (OFF)        | 0 (OFF)               |
| Max:   | 1 (ON)      | 1 (ON)            | 1 (ON)        | 1 (ON)      | 1 (ON)         | 1 (ON)                |
| Ex:    | 1 (ON)      | 1 (ON)            | 0 (OFF)       | 0 (OFF)     | 0 (OFF)        | 0 (OFF)               |
