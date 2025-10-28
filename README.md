# Audio Forensics Lab – Carroll Bell Education Center
Instructor: Daniel Peña

## 📘 What this lab includes
- `Audio_Forensics_Student_Handout_Carroll_Bell_v2.pdf` → full student guide  
- `student_attack.sh` → bash script for the dictionary attack  
- `small_wordlist.txt` → sample wordlist  

## 🎵 Download large files
To get the audio and Audacity:
Go to the **Releases** page (right sidebar or https://github.com/YOURNAME/YOURREPO/releases)  
Download:
- harlandale1.wav  
- harlandale2.wav  
- Audacity-x86_64.AppImage  

## 🧠 Student quick start
```bash
chmod +x Audacity-x86_64.AppImage
./Audacity-x86_64.AppImage

chmod +x student_attack.sh
./student_attack.sh | tee attack_attempts.log


