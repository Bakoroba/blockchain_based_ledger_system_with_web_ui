# Blockchain-based ledger system, complete with a user-friendly web interface

## Objective
Build a blockchain-based ledger system, complete with a user-friendly web interface. This ledger should allow partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.

## Tasks
1. Step 1: Create a Record Data Class
Create a new data class named `Record`.
- This class will serve as the blueprint for the financial transaction records that the blocks of the ledger

3. Step 2: Modify the Existing Block Data Class to Store Record Data
- Change the existing `Block` data class by replacing the generic `data` attribute with a `record` attribute that’s of type `Record`.

3. Step 3: Add Relevant User Inputs to the Streamlit Interface
- Create additional user input areas in the Streamlit application. These input areas should collect the relevant information for each financial record that you’ll store in the `PyChain` ledger.

4. Step 4: Test the PyChain Ledger by Storing Records
- Test your complete `PyChain` ledger.

## Test results
1. Screenshot of the Streamlit application page detailing blockchain that consists of multiple blocks.

2. Screenshot of the Streamlit application page indicating the validity of the blockchain.

## Technologies

The technologies used are:
1. Blockchain 
2. Streamlit
3. Githib
4. Git
5. dataclasses
6. hashlib
7. Python typing

---

## Usage
To run:
1. Open a terminal and navigate to the project folder where you've coded the
2. In the terminal, run the Streamlit application by using `streamlit run pychain.py`.
3. Enter values for the sender, receiver, and amount, and then click the "Add Block" button. Do this several times to store several blocks in the ledger.
4. Test the blockchain validation process by using the web interface button 'Validate Chain'

![image](https://github.com/Bakoroba/blockchain_based_ledger_system_with_web_ui/assets/7796158/a4619499-a01f-4073-8c30-1dade11dfa32)


---

## License

MIT
