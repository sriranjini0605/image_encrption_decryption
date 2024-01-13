# image_encryption_decryption

## Project Overview:
This project aims to implement a robust image encryption system using the Advanced Encryption Standard (AES) algorithm. The system ensures the secure transmission of images over networks by reducing the risk of data loss and unauthorized access. At the receiving end, an effective and safe image decryption process is executed to preserve the integrity of the original image. The development includes a user-friendly application that seamlessly combines encryption and decryption processes for user convenience. By providing a practical solution to protect private image files, this project makes a valuable contribution to the field of data security. It emphasizes the significance of encryption in the digital era, promoting safe data practices. The project also serves to showcase the efficiency and usefulness of the AES algorithm in safeguarding the privacy of digital assets, particularly pictures.

## Functional Requirements:
Encryption: Encrypts the given image using the AES encryption function, rendering it
unreadable.
Decryption: Decrypts the received encrypted image back into its original readable format.

## Non-Functional Requirements:
Performance Requirements:
Image Size: Efficient encryption supports images up to 5MB in size.
Decryption Speed: Decryption completes within a maximum of 10 seconds.
Safety and Security Requirements:
Decryption Failure: If decryption exceeds 10 seconds, the system assumes data corruption and
discards the message, prompting the sender to resend it.
Key-Based Encryption: Encryption requires a specific key, and decryption only succeeds when the same key is used at both the sender and receiver ends.
Software Quality Attributes:
Reliability: Algorithm Reliability: The universally accepted AES algorithm consistently generates accurate results, minimizing errors.
Transmission Resilience: External factors, such as transmission glitches, rarely impact system performance.
Usability: User-Friendly GUI: A Python-based GUI provides intuitive buttons for easy navigation and operation, making it accessible to users with basic computer knowledge.
Modular Design: The system's modular architecture facilitates individual testing of each module, enabling efficient defect identification

# Tools Used:
1. Programming Language:Python
2. Libraries and Frameworks:
Tkinter: Tkinter is used for creating the graphical user interface (GUI) of the application.
Pillow (PIL): Pillow is used for image processing tasks, including loading, resizing, and saving images.
Crypto.Cipher (AES): The Crypto.Cipher module is used for implementing the Advanced Encryption Standard (AES) algorithm for encryption and decryption.
NumPy: NumPy is used for numerical operations, particularly in the generation of random values for the secret image.
3. IDE (Integrated Development Environment): The IDE used for coding and debugging is Visual Studio Code (VSCode)
4. Version Control:Git is the version control system used to track changes in the code.
5. Dependency Management: Pip for Python package management
6. Collaboration Tools: Slack for team communication


