USART2 LED Control - STM32F446RE
🎯 Description:

This project demonstrates how to use USART2 on the Nucleo-F446RE development board to receive simple UART commands ('1' or '0') and control an onboard LED connected to pin PA5 accordingly.

✨ Features:
⚙️ Initializes USART2 at 9600 baud rate.

💬 Sends a welcome message via UART on startup.

📥 Receives characters using interrupts (IRQ) without DMA.

💡 Controls an LED based on the received character:

'1' → LED ON 🔛

'0' → LED OFF 🔴

🔌 Pin Configuration:
TX (PA2) – Transmit data to terminal 📨

RX (PA3) – Receive data from terminal 📥

LED (PA5) – Output control for LED 💡



🧰 Requirements:
Nucleo-F446RE Board

STM32CubeIDE or compatible development environment

USB cable (for power + UART communication)

Serial terminal (e.g., PuTTY, Tera Term)

🛠️ How to Use:
🧠 Flash the code to your Nucleo board.

🖥️ Open a serial terminal (baud rate: 9600).

⌨️ Type '1' → LED turns ON.

⌨️ Type '0' → LED turns OFF.

✅ Check feedback messages in the terminal.

