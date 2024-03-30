##  ATM Simulator  **(Node.js)**

This is a Node.js script that simulates a basic ATM functionality. It allows users to:

* Verify their PIN code for account access.
* Check their current account balance.
* Withdraw cash (with balance validation).

**Note:** This is a simplified example for educational purposes and wouldn't be secure for a real ATM system. 

## Usage

**Prerequisites:**

* Node.js and npm (or yarn) installed on your system.

**Steps:**

1. Clone this repository:

   ```bash
   git clone https://github.com/IBRXH1M/atm-machine
   ```

2. Navigate to the project directory:

   ```bash
   cd atm-simulator
   ```

3. Install dependencies:

   ```bash
   npm install inquirer
   ``` 

4. Run the script:

   ```bash
   node index.js
   ```

5. The script will guide you through entering your PIN, selecting an operation (check balance or withdraw), and following further prompts based on your chosen operation.
