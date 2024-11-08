# Automatic_Drug_Dispenser

This automated drug dispensing system encodes a doctor's prescription as a QR code, which is generated using Python. The QR code is then scanned and stored in a MySQL database for easy retrieval and verification. When a patient presents the QR code, the system checks the availability of the prescribed medication in its inventory. If the medicine is in stock, the system sends a command to an Arduino, which controls the hardware mechanism to dispense the correct dosage of the prescribed drug. This setup streamlines the dispensing process, ensuring accuracy and efficiency in medication delivery.
