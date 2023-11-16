## AWPS (Automatic Wifi Penetration System) Bridge Rest API

This Rest API server is used to receive hashes from the AWPS Command Launch Module (Android app) via HTTP protocol. It uses lite SQL database to store the hashes. To run the server, first create a virtual environment using the command `pip -m venv venv` then install the required packages `pip install requirements.txt`. After installing the packages do not forget to change the host in main.py depending on the assigned IPv4 on your device. Activate the environment `venv\Scripts\activate` then create the database `python create_database.py` after creating the database, you can now launch the script `python main.py`.

## DISCLAIMER

The project AWPS is intended for educational purposes, with the primary goal of raising awareness and understanding of cybersecurity in a legal and ethical context. It is essential to clarify that this tool is NOT INTENDED to encourage or promote any form of unauthorized or unethical hacking activities. Ethical hacking, conducted with proper authorization and consent, plays a crucial role in enhancing the security of digital systems. This project seeks to promote responsible use of technology and responsible disclosure of vulnerabilities to help protect and secure digital environments.

USAGE OF ALL TOOLS on this project for attacking targets without prior mutual consent is ILLEGAL. It is the end user’s responsibility to obey all applicable local, state, and federal laws. I assume no liability and are not responsible for any misuse or damage caused by this project or software.