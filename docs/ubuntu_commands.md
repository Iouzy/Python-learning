# Ubuntu Commands Cheat Sheet

`pwd` → show current directory  
`ls` → list files  
`ls -la` → list all files (including hidden)  
`cd folder` → enter folder  
`cd ..` → go up one level  

`cat file.txt` → display entire file  
`head -n 10 file.txt` → first 10 lines  
`tail -n 10 file.txt` → last 10 lines  
`sed -n '10,20p' file.txt` → display lines 10 to 20  

`touch file.txt` → create empty file  
`nano file.txt` → edit file  

`cp file.txt copy.txt` → copy file  
`mv file.txt new.txt` → move or rename file  
`rm file.txt` → delete file  
`rm -r folder/` → delete folder  

`grep "text" file.txt` → search for text  

`clear` → clear terminal  
`history` → show command history  

`sudo apt update` → update package list  
`sudo apt install package_name` → install package  

---

## Typical Workflow

```bash
ls
cd 01_basics
nano 01_print.py
python3 01_print.py

---

# Final step

```bash
git add .
git commit -m "Separated README and ubuntu commands documentation"
git push
