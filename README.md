# MetaGuardian
MetaGuardian is a passive voice assistant protection system based on 3D-printed acoustic metamaterials. It is designed to effectively defend against inaudible ultrasonic attacks, adversarial audio commands, and laser injection attacks—all without requiring any modification to the target device.
This repository provides everything needed to reproduce the experiments from our paper, including:

🧩 CAD files of the custom-designed acoustic metamaterial structures

CAD File Descriptions

The MetaGuardian system includes 8 CAD files, each corresponding to a specific structural design or use case. These files enable the construction of different defense configurations for mobile devices and smart speakers:

Mobile Device Defense Structures (Assembled Versions)

`MoblieDevices-OneMic`

  Fully assembled defense structure designed for mobile devices (e.g., smartphones, tablets) with a **single microphone opening**.

`MoblieDevices-TwoMics`

  Assembled defense structure tailored for mobile devices with **dual microphone openings**, compatible with devices that have multiple mic placements.

 
 Mobile Device Structures (Unassembled – without AADM)

`(Without AADM) MoblieDevices-OneMic`

  Unassembled version of the single-mic structure **without the built-in Adversarial Audio Defense Metamaterial (AADM)**. Recommended for post-3D-print **manual polishing and fine-tuning** before installing AADM.

`(Without AADM) MoblieDevices-TwoMics`

  Unassembled version of the dual-mic structure, also meant for **manual assembly** after cleaning or modifying printed parts.

 Core Defense Components (Metamaterial Units)

`AADM`

  Standalone acoustic metamaterial unit designed to defend against **adversarial audio attacks**. This is a **core module**, not including the outer casing.

`IADM`
  
  Intelligent acoustic metamaterial unit specialized for **inaudible (ultrasonic) attack defense**. Also a core component requiring integration into an outer structure.

 Mounting & Support Component

`A fixed button`

  A positioning fixture to **stabilize mobile devices** within the defense structure. Used in combination with the mobile defense designs above.

 Smart Speaker Defense Structure

`SmartSpeaker`

  A fully assembled defense structure specifically designed for **smart speakers** (e.g., Amazon Echo, Google Home). Includes integrated metamaterials and enclosure.



🎧 Audio samples used for attack testing

(1) CommanderSong: A Systematic Approach for Practical Adversarial Voice Recognition. (https://sites.google.com/view/commandersong/)

(2) ALIF: Low-Cost Adversarial Audio Attacks on Black-Box Speech Platforms using Linguistic Features. (https://taser2023.github.io/)

(3) Kenku: Towards Efficient and Stealthy Black-box Adversarial Attacks against ASR Systems. (https://github.com/Xinghui-Wu/KENKU)

(4) Devil’s Whisper: A General Approach for Physical Adversarial Attacks against Commercial Black-box Speech Recognition Devices. (https://sites.google.com/view/devil-whisper)

(5) SMACK: Semantically Meaningful Adversarial Audio Attack. (https://sites.google.com/view/smack)

(6) Inaudible attack: attack audio at 18 kHz, 25 kHz, and 40 kHz.

🎥 Demonstration videos showing the experimental setup and process

https://youtu.be/BgMgL4QQH0A and https://youtu.be/y7qM-yOHKwE

With these materials, researchers and developers can accurately replicate our experimental workflow and validate the key mechanisms and defense performance described in the paper：MetaGuardian: Enhancing Voice Assistant Security through Advanced Acoustic Metamaterials

