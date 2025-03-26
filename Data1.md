# Example usage
if __name__ == "__main__":
    key = "thisisaverysecretkey!"  # Must be 16, 24, or 32 bytes long
    aes = AESCipher(key)
    
    message = "Hello, Crypto! This is a secure encryption test."
    encrypted_message = aes.encrypt(message)
    decrypted_message = aes.decrypt(encrypted_message)
    
    print(f"Original: {message}")
    print(f"Encrypted: {encrypted_message}")
    print(f"Decrypted: {decrypted_message}")
