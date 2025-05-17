# Stego Messenger

## Project Overview

Stego Messenger is a secure messaging application that combines cryptography and steganography to hide encrypted messages inside images. The project encrypts text messages using AES (Advanced Encryption Standard) and then embeds the encrypted data into image files using steganographic techniques.

## Features

- AES-based encryption for strong message security.
- Message hiding inside images without visible changes.
- Extraction and decryption of hidden messages with the correct key.
- User-friendly interface (to be integrated with Streamlit/Flask).
- Python-based implementation using Cryptography, OpenCV/Pillow.

## How It Works

1. The user inputs a secret message.
2. The message is encrypted using AES symmetric encryption.
3. The encrypted message is hidden inside an image file using steganography.
4. The receiver extracts the encrypted message from the image.
5. Using the correct AES key, the receiver decrypts the message to reveal the original text.

## Requirements

- Python 3.x
- cryptography library (`pip install cryptography`)
- OpenCV or Pillow for image processing (`pip install opencv-python` or `pip install pillow`)
- Streamlit or Flask for UI (optional)

## Usage

1. Generate or load an AES key (`secret.key` file).
2. Encrypt and hide messages inside images.
3. Extract and decrypt messages using the AES key.

## License

MIT License

---

# Stego Messenger

## Proje Özeti

Stego Messenger, kriptografi ve steganografiyi birleştirerek şifrelenmiş mesajları görüntü dosyalarının içine gizleyen güvenli bir mesajlaşma uygulamasıdır. Projede, mesajlar AES (Advanced Encryption Standard) ile şifrelenir ve ardından steganografi teknikleri kullanılarak şifreli mesaj görüntü içine gömülür.

## Özellikler

- Güçlü mesaj güvenliği için AES tabanlı şifreleme.
- Görüntü üzerinde görünür değişiklik olmadan mesaj gizleme.
- Doğru anahtar kullanılarak gizli mesajın çıkarılması ve çözülmesi.
- Kullanıcı dostu arayüz (Streamlit/Flask ile entegre edilebilir).
- Python ile Cryptography, OpenCV/Pillow kullanılarak geliştirilmiştir.

## Çalışma Prensibi

1. Kullanıcı gizli mesajını girer.
2. Mesaj AES simetrik şifreleme ile şifrelenir.
3. Şifrelenmiş mesaj görüntü dosyasına steganografi ile gömülür.
4. Alıcı görüntüden şifreli mesajı çıkarır.
5. Doğru AES anahtarı ile mesaj çözülerek orijinal metin elde edilir.

## Gereksinimler

- Python 3.x
- cryptography kütüphanesi (`pip install cryptography`)
- OpenCV veya Pillow görüntü işlemleri için (`pip install opencv-python` veya `pip install pillow`)
- Streamlit veya Flask (arayüz için, opsiyonel)

## Kullanım

1. AES anahtarını oluştur veya yükle (`secret.key` dosyası).
2. Mesajları şifreleyip görüntü içine göm.
3. Mesajları çıkar ve doğru anahtar ile çöz.

## Lisans

MIT Lisansı
