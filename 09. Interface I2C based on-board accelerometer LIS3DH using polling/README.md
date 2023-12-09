# Interface I2C-based On-Board Accelerometer LIS3DH using Polling

## Goal of Experiment

The goal of this experiment is to interface the on-board accelerometer LIS3DH using polling technique.

## Description

In this experiment, we will interface the on-board accelerometer LIS3DH using polling. The following steps will be performed:

1. Read the Device ID of the LIS3DH.
2. Use I2C to read raw data from the accelerometer.
3. Convert the raw data into a user-understandable format.
4. Continuously receive and print the data over UART.

UART1 is used to communicate between the user PC and the INDUS board, with the baud rate set as required. This experiment demonstrates how to interface the LIS3DH accelerometer using polling and display the data over UART.

## Usage

1. Clone or download this repository.
2. Open the project in your preferred IDE or development environment.
3. Build and upload the code to your INDUS board's microcontroller.
4. Configure your terminal software (e.g., HyperTerminal) to communicate with the board using the same baud rate.
5. Run the experiment to interface the LIS3DH accelerometer using polling and receive and print the data over UART.

## Contributing

Contributions to this experiment or code are welcome. Feel free to submit pull requests.

## License

This code is provided under the MIT License. See the [LICENSE](LICENSE) file for details.


Enjoy experimenting with I2C-based accelerometer interfacing using polling on your INDUS board! If you have any questions or encounter any issues, please feel free to reach out. Happy experimenting! 🚀
