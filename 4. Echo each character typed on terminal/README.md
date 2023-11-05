# Echo Each Character Typed on Terminal

## Goal of Experiment

The goal of this experiment is to understand how UART communication can be used to echo received data. The user inputs data through a terminal (e.g., HyperTerminal), which INDUS UART receives and prints on the INDUS (IDE) terminal and sends (echoes) back to the User PC, where it is printed on the terminal.

## Description

In this experiment, UART communication is configured to UART1 of the INDUS board's microcontroller, and the baud rate is set as required. The experiment echoes each character input through a terminal, providing a simple communication test.

## Usage

1. Clone or download this repository.
2. Open the project in your preferred IDE or development environment.
3. Build and upload the code to your INDUS board's microcontroller.
4. Configure your terminal software (e.g., HyperTerminal) to communicate with the board using the same baud rate.
5. Type characters in your terminal, and the board will echo each character back to the terminal.

## Contributing

Contributions to this experiment or code are welcome. Feel free to submit pull requests.

## License

This code is provided under the MIT License. See the [LICENSE](LICENSE) file for details.


Enjoy experimenting with echoing characters typed on your terminal using UART communication on your INDUS board! If you have any questions or encounter any issues, please feel free to reach out. Happy coding! 🚀
