# 🚀 Transposition Cipher Project 🚀

Welcome to our Transposition Cipher Project! This project is all about implementing the classic transposition cipher in Python. 

## 📚 What is a Transposition Cipher? 📚

A transposition cipher is a method of encryption by which the positions held by units of plaintext are shifted according to a regular system, so that the ciphertext constitutes a permutation of the plaintext. 🔄

## 💻 How to Use 💻

1. Clone the repository to your local machine. 💾
2. Navigate to the project directory. 📁
3. Run the `TranspositionCipher.py` file in your Python environment. 🐍
4. To decrypt a message, create an instance of the `TranspositionCipher` class with the correct key and call the `decrypt_message` method with the encrypted message.

```python
# Initialize the key
key = 7  # Replace with the correct key

# Initialize encrypted message
message = 'pe\nlwy crt h iarmpeo akohw hncosrmr\nt veo\nigkb ostot\neirbt .l\nb hfap rtytb' 

# Create a TranspositionCipher instance with the key
cipher = TranspositionCipher(key)

# Decrypt the message
decrypted_message = cipher.decrypt_message(message)

# Print the decrypted message
print(decrypted_message)

## 📝 Requirements 📝

- Python 3.10.11 
- Jupyter Notebook 📓

## 🙏 Contributing 🙏

Contributions are welcome! 
