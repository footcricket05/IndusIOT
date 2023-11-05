# ADC Demonstration using Potentiometer

## Goal of Experiment

The goal of this experiment is to vary the analog voltage value (in Volt) using a potentiometer and monitor that analog voltage value using an analog-to-digital converter (ADC).

## Description

In this experiment, we will vary the analog voltage value at a particular GPIO pin using a potentiometer. The analog value is then converted into a digital value by configuring the built-in ADC in the INDUS board's microcontroller. This digital value is printed on the UART terminal.

UART1 is used to communicate between the user PC and the INDUS board, with the baud rate set as required. This experiment demonstrates how to use a potentiometer to generate varying analog voltages, which are then converted to digital values using the ADC. The converted values are displayed over UART for monitoring.


## Usage

1. Clone or download this repository.
2. Open the project in your preferred IDE or development environment.
3. Build and upload the code to your INDUS board's microcontroller.
4. Configure your terminal software (e.g., HyperTerminal) to communicate with the board using the same baud rate.
5. Run the experiment to vary the analog voltage using a potentiometer, convert it to a digital value using the ADC, and display the value over UART.

## Contributing

Contributions to this experiment or code are welcome. Feel free to submit pull requests.

## License

This code is provided under the MIT License. See the [LICENSE](LICENSE) file for details.


Enjoy experimenting with ADC using a potentiometer on your INDUS board! If you have any questions or encounter any issues, please feel free to reach out. Happy experimenting! 🚀
