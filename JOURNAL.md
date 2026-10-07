# Day 1 (1 Hour 44 Minutes)
Started with learning about keyboard matricies(Shout out ScottoKeebs) and learning KiCad
Made first version of the PCB
<img width="1987" height="924" alt="Screenshot 2026-09-16 234547" src="https://github.com/user-attachments/assets/47e88772-132e-4dc8-9882-53484f5651db" />
<img width="1205" height="848" alt="Screenshot 2026-09-16 235343" src="https://github.com/user-attachments/assets/c57d585a-3f4e-48bf-977e-011f3179b45e" />
<img width="1438" height="800" alt="image" src="https://github.com/user-attachments/assets/bf615305-677a-418c-9366-8f626effc12e" />

# Day 2 (2 Hours 41 Minutes
Figured out how to make a plate for the PCB using Keyboard Layout Editor and Plate & Case Builder
<img width="541" height="367" alt="image" src="https://github.com/user-attachments/assets/028a40bd-ee33-48e6-9a07-866edacdf10f" />

Also started modeling a case around it in Fusion
<img width="1102" height="510" alt="image" src="https://github.com/user-attachments/assets/7f8ce2c3-b5c9-4816-b8b9-9650d267749d" />

# Day 3 (1 Hour 51 Minutes)
My friend told me the PCB looked messy, so I redid the traces and added an extra switch. I also changed it from an Arduino Pro microcontroller to the Seeed XIAO RP2040 with an MCP23017, so I had to start over the plate and case :(
<img width="1314" height="680" alt="image" src="https://github.com/user-attachments/assets/82a6106f-fe8f-45e0-bcd6-bbe41ef7401a" />
<img width="1277" height="696" alt="image" src="https://github.com/user-attachments/assets/579a5566-6a43-4e4c-adc5-fea173305ecb" />

# Day 4 (5 Hours 10 Minutes)
Got working on a case for the new pcb, but realized I didn't like the layout and redid it AGAIN along with a new plate, so great use of my time
Before Change
<img width="1744" height="1178" alt="image" src="https://github.com/user-attachments/assets/5ea25560-5370-4cec-9bbe-964e98ddfe9f" />
After Change
<img width="1928" height="827" alt="Screenshot 2026-09-19 182304" src="https://github.com/user-attachments/assets/dc9eb598-fda7-4f58-bd46-5aaa2ee559cd" />
<img width="1334" height="819" alt="Screenshot 2026-09-19 182422" src="https://github.com/user-attachments/assets/dddbb3d3-13f1-4c2c-a5fa-1c8162c78ff1" />
<img width="1432" height="960" alt="image" src="https://github.com/user-attachments/assets/4f0e57b7-4b94-4c71-96d3-48660067ccac" />
<img width="1509" height="856" alt="image" src="https://github.com/user-attachments/assets/81a5f3ac-9b8b-4f3d-af6e-20225f047372" />
<img width="1087" height="886" alt="Screenshot 2026-09-19 181834" src="https://github.com/user-attachments/assets/e2c59722-bcf6-453c-9a35-b2af17613dfe" />

# Day 5 (2 Hours 54 Minutes)

Started working on QMK firmware and found out that my PCB schematic was partially wrong, so I had to fix it. Then I redid the firmware.
Added two 4.7k pull up resistors for the MCP23017 and fixed the I2C connections.
<img width="955" height="808" alt="image" src="https://github.com/user-attachments/assets/3ef7b9ab-3aef-4ebd-bec4-35eed29edf8e" />
<img width="1466" height="928" alt="image" src="https://github.com/user-attachments/assets/316ce8e9-1880-4250-900f-13866ad262a9" />
<img width="1461" height="1012" alt="image" src="https://github.com/user-attachments/assets/34f3ddea-2164-4006-8de8-77577e56a30b" />
<img width="1403" height="940" alt="image" src="https://github.com/user-attachments/assets/66cb8188-d0a8-4020-b4fd-f8d11e242bcc" />

Firmware Before:
<img width="863" height="867" alt="image" src="https://github.com/user-attachments/assets/1112163b-840c-4fc9-b9db-bd1532041390" />
<img width="1631" height="1297" alt="image" src="https://github.com/user-attachments/assets/83119465-f775-4f5f-9761-38be52fe54b4" />

Firmware After:
<img width="883" height="1316" alt="image" src="https://github.com/user-attachments/assets/00f407f6-df0e-4c6b-baa8-0924190fb435" />
<img width="1498" height="1343" alt="image" src="https://github.com/user-attachments/assets/1953c1e0-9732-45c1-8579-cbf12be6657e" />
<img width="582" height="269" alt="image" src="https://github.com/user-attachments/assets/c037bc60-775a-4088-8434-d55e55c9ec11" />
