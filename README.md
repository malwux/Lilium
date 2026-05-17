# Lilium

My biggest project launched for now, Lilium.

As a first version of the project, you may find some bugs or feel incomplete. More features may be added in the future (like file encryption), but for now, it's just a simple 2 MBRS and EFI partition.

Lilium is divided into 3 parts: Lucy, Kaede, and Nyuu (obviously inspired by GoldenEye, Mischa, and Petya, to my Elfen Lied theme).

# Lucy

Firmware: UEFI

Windows: 10/11

Dropper: Python (EFI/Microsoft/Boot)

Tested: VirtualBox

Algorithm: ChaCha20

Hash: SHA-256

Language: C++

Compiler: VS2022

Base: vathpela (Thanks to his repository I was able to create the EFI) -> [github.com/](https://github.com/vathpela)

# Kaede

Firmware: BIOS

Windows: 7/8/10

Dropper: C++ (gcc) and Python

Tested: VirtualBox

Algorithm: Lightweight ARX stream cipher

Hash: FNV-16b

Language: ASM

Compiler: NASM

# Nyuu

Firmware: BIOS

Windows: XP

Dropper: C++

Tested: VirtualBox

Algorithm: XOR

Hash: FNV-16b

Language: ASM

Compiler: NASM and VS2022

# Download

Each variant has its own strengths and weaknesses, which is why this is the first version of my project. Knowing myself, I don't think I'll update it due to my daily responsibilities. I did the best I could; it's always been my dream to create Lilium and my first EFI. And yes, I obviously had to ask the AI ​​for help. Feel free to leave negative reviews.

Well, that's all I have to say. It took me from the beginning of March to the end of April in 2026, but I planned the project over a year ago and always gave up. It's been an honor to at least finish the first version. Do I deserve a coffee?

Lilium: https://mega.nz/file/NtkDkLhK#6libmiNPt48cPm9MJ6ww0Voy4rEEsVq4qhchZZ3SpGY
_(I am not responsible for any damage caused; use a virtual machine)_

Keys: https://mega.nz/file/ktV02RTY#SSqu_P-jBgF3QKkrCuLJFUdgiHOxm6XaEcxCh3b8L1k
_(decrypter.exe id.txt key.pem/blob)_

UEFI Project example: https://mega.nz/file/RoVzwLIY#JmMozMWV6R6j0bF4QVuykxcKnq10KtMocWHg9Mz4N8k
_(named Bootrec purposely)_
